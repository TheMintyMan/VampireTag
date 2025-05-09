Go Back to [[Vampire Tag GDD]]

# Overview
The player controls will be inspired from games such as Gang Beasts, fall guys, humans fall flat and Party Animal.

Physics based characters that can be grabbed from anywhere.

```cpp
// Holds things such as the Camera, Mesh, etc
VTCharacter.h

// Just holds the inputs to reduce clutter on Pawn
VTController.h

// Holds all information about the player
VTPlayerState.h

// Used for setting up binding tags for ability inputs
VTInputComponent.h

// Data Asset for setting up modular inputs
VTInputConfig.h
```


# Control Scheme

Need an image of a keyboard and a controller with all the basic control scheme of the game


WASD movement

Left Click - Quick Melee/ Push Back
Hold Left - Heavy Melee (Throw grabbed object)
Right click - Grab
Shift - Quick Dash - 0.5 second invulnerability


# Player Level

No player level up. Unless?
Maybe pickup that gives players extra strength.


# Camera

Locked camera angle.

Camera can only move on the X and Y axis. 

The camera will follow the player.


## Vision Cone

The player has a vision cone. 

<span style="color:rgb(255, 192, 0)">Anything outside the vision cone will appear black?</span>

# Player Mechanics
All things the players can do
## Player Grabbing/Pushing

What happens when a player grabs another at the same rate and when they jump away from each other at the same time?

## Player Shove

## Player Quick Melee

## Player Heavy Melee

## Player Dash

## Player Throw


## Sunlight
Sunlight will damage the Vampire.

Ticks damage over time.

<span style="color:rgb(255, 0, 0)">0.5 heart per second</span> whilst in the sun out of 10 hearts.

