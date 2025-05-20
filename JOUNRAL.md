# DAY 1: Understanding what I want to make, and creating rough requirements
I spent today, figuring out what I actually want with Zebrex. This is what I came up with:
+ Zebrex will be a handheld console.
+ It should be capable of running SNES level games, with a game framework of sorts built for it.
+ It should be able to run SNES games, provided a ROM.
+ The primary mechanism of view will be through the in-built screen, but will also be able to be viewed on a screen through HDMI.

I have spent the entire day(1.5 hrs only due to homework, but, still) designing *roughly* what I want, on a whiteboard. See: Figure 1.1(Is this professional?).

I also saw the [PCB Schematic of Sprig](https://github.com/hackclub/sprig/blob/main/hardware/mainboard_PCB/schematic.png) to get some more idea.

![image](https://github.com/user-attachments/assets/6a68c57d-7710-4644-8021-1755c4579def) Figure 1.1

## Brief Explanations of Buttons:
### Lateral Button Left and Lateral Button Right(LBL and LBR):
These are equivalent to RB and LB on a regular console(not sure what the right term is). I love these buttons. I'm not sure why, but I love shooting mechanics which use them, so the are here.

### The Joysticks
The joysticks will be primarily used for movement in-game. Maybe even for shooting.

### The DPads
Will be used for regular controls.

### Reset Buttons
There are two reset buttons - 
1. Reset Game - Will be used to reset the state of the current game.
2. Reset Console - Will be used to reset the entire console.


# Day 2
Today was mostly spent on figuring out, specifically, what would be used so I can start making the PCB.

## Controller
I spent a lot of time comparing different microcontrollers. These are the options I considered:

1. Rasberry Pi 4/5
2. RPi Pico
3. Rpi z2w
4. ESP 32

I reasearched a lot about thir clock speed and RAM, and, in the end, decided on the RPi z2w. It offers similar performance to the first option, and provides significantly more power than the other ones.

## Joystick
I found KY-023 joystick available widely online, so thats what I'm going with.

## Screen
I have decided to use a 2.8 inch screen. It might be slightly small, but, if need be, the console may be connected to another screen. Plus, the cost difference between a 2.8 inch and 3.2 inch is a lot.
