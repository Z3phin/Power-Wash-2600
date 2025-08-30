# Power Wash 2600

![alt text](https://github.com/Z3phin/Power-Wash-2600/blob/main/img/area-1.jpg)


## About

Power Wash 2600 is a fan adaptation of the satisfying Power Wash Simulator originally by FuturLab and Square Enix for the Atari 2600 console. 

Originally, this project was submitted for my Year 3 Dissertation Project as part of the Sofware Engineering course at Swansea University. Inpsired by "Halo 2600" by Ed Fries, the project,  
entitled "Ninth Gen to Second Gen: Adapting a Modern Game to 8-bit", details the development of adapting a more modern game, Power Wash Simulator, by someone who was vaguely familier with the existence of the Atari VCS/2600 system, all the way producing a reasonably competent game. 

The paper went deeper into understanding the limited hardware architecture fully, learning (and crying) about 6502 Assembly programming, and navigating the many strange quirks of the system that meant I needed to "Race the Beam". Beyond the paper, it is possibly one of the most important projects I have done personally, pushing all the various skills needed as a programmer, including delving into unfamiliar systems and languages, reading documentation and experimentation, as well as patience. Even though it was one of the hardest projects I have worked on, it is also one of the most rewarding. 

As a consequence of being my first game for the system, the game does indeed have many limitations. Despite that, I am immensely proud of the result and I hope people have fun experiencing it! Hopefully, this project can inspire new people to create their own games for the system, to challenge their abilites to the fullest, and appreciate the console that went on to inspire so many of the epic games we see today!

### Tools

* **IDE** - 8BitWorkshopIDE by Steven Hugg
* **Language** - 6502 Assembly

### Resources

* **"Racing the Beam"** by Ian Bogost and Nick Montfort:   
Details the fascinating story Atari and the console's development, going in depth about several inspirational games that challenged the system to do amazing things. 

* **"Making Games for the Atari 2600"** by Steven Hugg  
Main learning resource for making the game, complete with code samples and examples of different game systems. Much of the code that made "Power Wash 2600" is originally from 
this book, altered to suit the game as needed. It is a much recommended read for anyone interested in making games for the system.

* **Stella Programmer's Guide**   
An invaluable resource for any Atari 2600 game developer, detailing all of the various chips, memory addresses and strange quirks of the original hardware.

## Running the Game

### Assembling 

It is recommended that the game be assembled in the [8BitWorkshop IDE](https://8bitworkshop.com) by Steven Hugg. Go to 'Menu->Download->Download ROM Image' to generate an `a26` binary file. 

Alternatively, the [DASM Assembler](https://dasm-assembler.github.io) may be used to generate a binary locally.

Either way, the final ROM image can be played on the original system or through an emulator. 

### Physically

For the intended play experience, it is recommended to play the game on a physical Atari 2600 or Atari 2600+ console with Joystick controllers. Understandably, this may not be accessible for most so emulators are available detailed in the Emulators section.

To run the game on a physical console, a [Harmony Cartridge](https://harmony.atariage.com/Site/Harmony.html) is recommended or similar device. Using an Atari 2600+ and Harmony Cartridge, the Harmony Cartridge will need to be put into development mode to run properly. Simply insert the cartridge into the console and the game should load.

### Emulators

To run the game, emulators may be used to run the game on your device, such as Stella  or Javatari. For ease, [Javatari](https://javatari.org/) is recommended as this runs in the browser. Simply press 'Open ROM File...' and select this ROM image.

Alternatively, [Stella](https://stella-emu.github.io) may be used, but requires a download and some setup.

As a final alternative, the original source code can be copied into [8bitworkshopIDE](https://8bitworkshop.com/v3.11.0/). Here the original source code can be viewed (and altered) alongside an embedded version of the Javatari emulator. 

## How to Play:
### Controls:

Preferably, Joystick Controllers are the intended experience, although the game is perfectly playable using a keyboard on an emulator (Phone controls are not recommeded as it will be single player only).

- NOTE: Any controls for Keyboard presented are the common defaults (pictured is the Javatari defaults). These may be edited in most emulators to suit your preference.

![Javatari Controls](https://github.com/Z3phin/Power-Wash-2600/blob/main/img/controls.png)

* Use UP and DOWN to move the Power Washer up and down respectively
* Use RIGHT and LEFT to move the player left and right respectively
  - Players are unable to move off the screen sides
  - Players can pass through each other
* Hold the FIRE button to fire the Power Washer. Releasing the button will turn the Power Washer off.
* TURBO FIRE is a common additional control used to rapidly fire the FIRE button. This is NOT recommended for this game.
 
### Objective

* Clear away the dirt on screen by blasting it away with your Power Washer. Gain points by clearing rows of a building/vehicle
  - In Canvas and Random modes these are split into six segments made up 4-8-8-4-8-8 squares respectively.
  - Be careful! Score is not added until the row is fully clean, your opponent might try to steal your points!
* The player with the Highest Score wins the round. 
* After a round is won, a new round starts with new a procedurally generated selection of objects to wash. 

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




