# Power Wash 2600

## About

Power Wash 2600 is a fan adaptation of the satisfying Power Wash Simulator originally by FuturLab and Square Enix for the Atari 2600 console. 

This project is part of my Year 3 Dissertation project at Swansea University, which hoped to adapt a modern game to an 8-bit console. 
In this case, it is an adaption of Power Wash Simulator to the Atari VCS/2600 console. 

Coded in 6502 assembly, the game combines many of the learnings from segments in the book "Making Games for the Atari 2600" by Steven Hugg. 
Much of the code as been originally taken from this book and altered to suit the specification of this project. 

## Running the Game

### Assembling 

It is recommended that the game be assembled in the [8BitWorkshop IDE](https://8bitworkshop.com) by Steven Hugg. Go to 'Menu->Download->Download ROM Image' to generate a26 binary file. 

Alternatively, the [DASM Assembler](https://dasm-assembler.github.io) may be used to generate a binary locally. 

### Physically

It is recommended to play the game on a physical Atari 2600 or Atari 2600+ console with Joystick controllers for the intended experience. Understandably, this may not be accessible for most so emulators are available.

To run the game on a physical console, a Harmony Cartridge is recommended or similar device. Using an Atari 2600+ and Harmony Cartridge, the Harmony Cartridge will need to be put into development mode to run properly. Simply insert the cartridge into the console and the game should load.

### Emulators

To run the game, emulators may be used to run the game on your device, such as Stella  or Javatari. For ease, [Javatari](https://javatari.org/) is recommended as this runs in the browser. Simply press 'Open ROM File...' and select this ROM image.

Alternatively, [Stella](https://stella-emu.github.io) may be used, but requires a download and some setup.

As a final alternative, the original source code can be copied into [8bitworkshopIDE](https://8bitworkshop.com/v3.11.0/). Here the original source code can be viewed (and altered) alongside an embedded version of the Javatari emulator. 

## How to Play:
### Controls:

Preferably, Joystick Controllers are the intended experience, although the game is perfectly playable using a keyboard on an emulator.

- NOTE: Any controls for Keyboard presented are the common defaults. These may be edited in most emulators to suit your preference. Player 2 controls are commonly the arrow keys.

#### Moving the Power Washer


Move the Joystick UP (W) to move the power washer UP, and Joystick DOWN (S) to move it DOWN.

#### Moving the Player

Move the Joystick RIGHT (D) to move your player RIGHT, and Joystick LEFT (A) to move LEFT.

Players are not able to move off the screen bounds.
Players can move through each other. 

#### Firing

Hold the Joystick Button Down (Space) to fire the Power Washer. Releasing the button will turn the Power Washer off. 

### Objective

Clear away the dirt on screen by blasting it away with your Power Washer. Gain points by clearing rows of a building/vehicle (in Canvas and Random modes these are split into six segments made up 4-8-8-4-8-8 squares respectively).

The player with the Highest Score wins the round. 

After a round is won, a new round starts with new a procedurally generated selection of objects to wash. 

## Features:

* **Blast away dirt** - Position your power washer and fire to clear away the dirt!
* **Score**  - Gain points by completing rows of buildings!
* **Two player support** - Compete or work together to wash away dirt!
* **Procedural Generation** - Continue to clean up with randomly appearing buildings after every round!
* **Canvas Mode** - Flip to BW mode and reset the game to enter canvas mode to draw whatever you like!
* **Random Mode** - Flip to BW and P2 to Expert to wash away completely random dirt! 
* **Mute Button** - Flip the P1 difficulty switch to mute the sound if it gets annoying. I am no good at sound design.

## WARNING: 

The game contains some flashing colours and images which may affect some players.

## Extra Info

The final version of the project submitted and showcased at Swansea University.



