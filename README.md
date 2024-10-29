# Spy Master Fix

By Sonneveld

## What is it

This removes the copy protection from the game Spy Master by L.K. Avalon,
published 1994.

If the copy protection detects an unauthorised installation, it removes bombs,
disables level exits, disables save games and clamps your score to 100.

You can hopefully find latest version at:

https://github.com/sonneveld/spy-master-fix


# How to use it

Run SPYFIX.COM to load the TSR. 

Run SPYFIX.COM /R to remove the TSR.

Once TSR is loaded, run the game as you normally would (SPY.EXE)


## The game

Spy Master by L.K. Avalon, published 1994.

https://www.mobygames.com/game/59567/spy-master/

The player controls a CIA special agent, Charles Cat, who has to fight his
way to the heart of a fortress in the Andes through ranks of soldiers,
automatic tanks and traps.

PC AT, 1 MB RAM, VGA. 

Sound: PC Speaker, Covox, Sound Blaster, Gravis UltraSound, General MIDI.


## Controls

During Title Screen:

* F1,F2,F3,F4 - restore game slots 
* F10 - exit to dos

During Gameplay:

* LEFT/RIGHT - walk left, right
* UP - jump up or across if holding LEFT/RIGHT
* DOWN - pickup bomb
* ENTER - use bomb
* SPACE/INS - shoot
* K - toggle keyboard/joystick
* T - toggle background
* M - toggle music
* P - pause
* F5,F6,F7,F8 - save game slots
* F10 - suicide

You have 5 lives. When your energy drops to 0, you lose a life.

You can hold a maximum of 8 bombs. Bombs can be used to destroy rocks or disable photocells.


## Building TSR

8 spaces for tabs, file encoding: DOS CP 437

Built with MASM 6. Other versions may work.

Use BUILD.BAT to build.
