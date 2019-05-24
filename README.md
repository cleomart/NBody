# NBody
![](https://github.com/cleomart/NBody/blob/master/planetspartyimage.png)

This program simulates N motion of objects in a plane which accounts for the gravitational forces mutually affecting each object as demonstrated by Sir Isaac Newton’s Law of Universal Gravitation.

This project was created for CS 61BL (Data Structures) at UC Berkeley Summer 2018.

## Installations
To run the application, clone the repository on your local machine.
```
git clone https://github.com/cleomart/NBody.git
```
Then go inside the repository and compile `Nbody.java`.
```
javac NBody.java
```
Run the simulation with the following template:
```
java NBody <T> <dt> data/<file>
```
where 

- `T` is the time interval in which we update the position of our planets and redraw the universe

- `dt` is a small period of time when planet's velocity changes

- `file` is the name of the file that contains the universe we want to stimulate. There are many other universes you can choose from in `data` folder.

Here are a couple of examples:

```
java NBody 166880000.0 100000.0 data/planets.txt

java NBody 20000000 20000 ./data/massive-squirrel-battle.txt

java NBody 20000000 20000 ./data/illusion.txt 

java NBody 20000000 20000 ./data/kaleidoscope.txt 

```
