This is a C++ and SFML gravity simulation made by Oscar Pritchard. 
It is using real world numbers for everything. One pixel is currently 800000km but can be changed in the code. 
The radius is based off the mass of the planets at Earth's density. 

Controls:
  Left mouse down:
    Holding down the mouse on the screen will create a new planet.
    The longer your hold down the mouse the more mass the planet has.
    You can press space to pause the radius while still increasing the mass. This is effectively increasing the density of the planet. The white outline shows the virtual mass of the planet. This can be used to simulate black holes. 
    You then drag the mouse while still holding down to create the starting velocity of the planet. The planet will then move that distance every 2 seconds.
    Release the mouse to finish creating the planet.
  C:
    Pressing C toggles clearing the screen or not. By default the screen is cleared every frame. This is useful for seeing the orbits of the planets.
