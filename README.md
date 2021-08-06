# Gravity Simulation in C++ & SFML

This is a C++ and SFML gravity simulation made by Oscar Pritchard. 
It is using real world numbers for everything. One pixel is currently 800000km but can be changed in the code. 
The radius is based off the mass of the planets at Earth's density. 

## Controls:

### Left mouse down:

Holding down the mouse on the screen will create a new planet.
This will clear the screen.
The longer your hold down the mouse the more mass the planet has.
You can press SPACE to pause the radius while still increasing the mass. 
This is effectively increasing the density of the planet. The white outline shows the virtual mass of the planet. This can be used to simulate black holes. 
You then drag the mouse while still holding down to create the starting velocity of the planet. 
The planet will then move that distance every 2 seconds.
The white line shows the velocity of the planet.
Release the mouse to finish creating the planet.

### C:

Pressing C toggles if the planet's trails should be shown.

### R:

Pressing R will reset the simulation. This will delete all the planets and clear the screen.

## Get Started

### Linux

First download SFML. Type `sudo apt-get install libsfml-dev` into terminal.
Then download the vinary gravity file from releases. Make sure that under the file permissions that the program can be executed.
Open terminal and navigate to the directory that the gravity file is downloaded to. Then type `./gravity`.
The program should now work!

### Windows

I have no idea how to compile this for Windows, sorry. If you know how, please let me know.
