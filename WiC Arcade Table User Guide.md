# WiC Arcade Table User Guide

#### Guide Written by
Lauren DiDonato (‘20)
#### Arcade Created by
David Quach (‘19)
Bill Krodthoff (‘18)
Lauren DiDonato (‘20)
#### Maintained By
Kevin Barnett (‘20)

The WiC arcade table was made by a team in the Projects Committee for the 2017 ImagineRIT

*** 

## Contents
* The TV
    * Volume
    * Monitor Settings
* The Pi
    * Adding Games
    * Removing Games
    * Configuring Buttons
* Daily Tasks
    * Turning it on
    * Marquee Light
    * Games
    * Arcade Controls

*** 

# The TV

## About
The tv in a 19” Insignia HDTV. The Pi is plugged into it via an HDMI cable and it gets power
from being plugged into the extension cable in the back of the cabinet.
The remote is in the cabinet, but it does not work because there is an inch of wood above the
censor.

## Volume
Currently set on Max
To change the volume of the tv you need to reach your hand into the cabinet from the back
door, lift the TV slightly out of the cradle. Facing the back of the cabinet the controls are on the
left side. Hit the volume buttons there, it should be 4rd and 5th from the top.

## Other Settings
Adjusting anything else using the TV’s menu probably needs 2 people, one to look and the other
to hit buttons. Good Luck.

![image](https://user-images.githubusercontent.com/60679049/197279516-8baa1b2e-b6bc-4a1a-81c4-fe3458156017.png)

***

# The Pi

## About
The Raspberry Pi is a Pi 3 Model B. It is plugged into the extension cable for power and the TV
via HDMI for display. It has 4 USB ports, 2 have the microcontrollers that control the buttons
plugged in, 1 for the keyboard, and one for a mouse if needed.

## Adding Games
There is a USB drive labeled “Arcade” in the back of the cabinet.
1. Locate the ROM you want to use, and download it. Leave it in zip form. Take note of
the type of system it runs on. Do not use MAME roms, the pi does not like them. Some
might work but most don’t.
2. Plug the USB drive into your computer. Use a Mac if possible- like the one in the WiC
space. It will be called “P D”. Do not alter the file structure of the drive. Don’t change
any folders or files, only add.
3. Go into the “retropie” folder, then the “roms” folder. There you will see a list of folders
that represent the emulators Retropie has. Drag the zip file of your ROM into the correct
system folder.
4. Unplug your USB and plug it back into the pi
5. Restart the pi. Best way to do that is from retropie hit Menu → Quit → Restart System
6. The games should be on the pi when you restart the system.

## Using a non-preformatted drive:
1. Create a folder on the drive labeled retropie
2. Plug drive into pi while booted and wait 1 minutes
3. Plug the drive in to computer
4. Continue step 3 above

## Deleting Games
1. Similarly to the “Adding Games” , Go into the USB on your computer, navigate to the
game you no longer want in the arcade.
2. Delete the zip. This is done so if you ever add more new games, the old ones won’t go
back on.
3. In retropie, navigate to the game you want to delete. The hit Option → Edit This Games
Metadata → Scroll to the bottom and hit DELETE → OK

***

# Daily Tasks

## Turning it On
* Plug the (white) extension cable into an outlet
* Wait for the TV to turn on, it will say “no input found”
* Unplug just the pi and plug it back in (the blue lenel piece)
* Choose your game using the green joystick and the top left green button
* To quit out of the game and back to the retropie menu, press and hold the center green
and yellow at the same time

## The Marquee Light
* Get a thin handed person to reach under the plastic
* The button is on the left side of the light
    * It has 4 settings- high, medium, low, off
    * Keep pushing the button to cycle through
* If the battery is charged through the orange USB cable, just plug it in to charge

***

# Games
Galaga
Megaman 2
Sonic the Hedgehog
Frogger
Street Fight 2
Pac-man
Dig Dug
Super Mario Bros

# Arcade Controls
To Exit Game Press Start and HotKey

# Controller Layout
![image](https://user-images.githubusercontent.com/60679049/197279638-4f213525-efc0-452c-84e0-bd6396aab49b.png)
