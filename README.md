# Party-Super-Bash
An Arduino-Nano and DFPlayer-Mini device to spice-up your pinball games, board games and any other games in that matter!
------------------
(based on Aerao's Bartop-Super-Bash, visit https://github.com/aerao/Bartop-Super-Bash)
 
 
###### ENG
You've got three big iluminated slam-buttons at your disposal:
- Blue to bring up the heat and ambiance things up!
- Green to highlight your wins!
- Red to bash your opoments when they miserably fail!!
(one extra sound folder exists so you can activate an additional set of adults-only sounds to ultra-bash at your will - requires hiden activation).

Note that one output is configured to power flashing/strobe lights when Blue, Green and Ultra-bash are activated.
All 4 outputs can be jumper-configured to output 5v or 12v (make sure your power supply can cope with the current draw..)

One 'hiden' system button allows access to the system-menu for 1-sound level, 2-activate/deactivate the ultra-bash sounds.

For normal use, nothing special to do, just power it up, wait for the boot sequence to complete, and start having fun!

To access the system menu, once booted-up, press and hold the menu switch a few seconds until first menu sound (for volume configuration), or way further for the Ultra-Bash menu.
In either menu, use de Red and Green buttons to change the setting, then wait for the timeout to exit back to user-mode.

The system requires:
- Arduino-Nano (or Arduino-uno if you decide not to use the provided PCB design)
- DFPlayer-Mini
- microSD card
- 12v power supply
- a 12vDC to 5vDC buck module
- x4 IRF840 Mosfets
- a few LEDs and resistors
- a couple of capacitors
- x3 slam buttons with built-in LEDs
- one small button for the menu access
- a loud speaker
- based on your personal preference, you might also want to use an audio pozer amplifier 
- some connectors and cables
- Bright flashing/strobe lights

A minimum set of audio samples is provided. Put them 'as is' on a FAT32 formated microSD card.
Let me know of your created audio files so we can share..

PCB
All the required Geberit files are provided for you to get your PCB printed.
I have designed the PCB to make it as universal and versatile as possible. This whay it can be used for many other projects...
