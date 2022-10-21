[RetroPie]: https://retropie.org.uk/docs/

## Setup
The raspberry pi has [RetroPie] installed on it. When the Pi is plugged in it should start up into RetroPie, and display a welcome screen. From there you can plug in your controller, and configure it. Each player on the button board is an individual controller, and player 2 does not have a Start, Select, or HotKey button.
## Hardware
### Buttons
Each button can have the cap removed to change the letter inside of it. The buttons are wired with a 3 pin female adapter. This connects to the [board](#board).
### Joysticks
The Joystick on it's own has no cable, but a 5 pin male port. A cable for this is required to connect it to the [board](#board), and we would recommend having a spare or 2. 
### Board
Each "player", aka the left and and right sides of the arcade controls has a board that the buttons and the joystick plug into. This board connects to the Pi through a USB a - USB b (2.0) cable. The Start, Select, and hotkey buttons are associated with player 1, and player 2 does not have those buttons.
### Configuring a Contoller
If the controller becomes un-synced or you unplug any of the buttons, you will need to reconfigure the controller. If neither of your controllers work, you need to plug an Xbox controller into the the Pi, and with the controller, go to the menu by pressing the select button, and select "Configure Inputs." Hold a button on the player you want to reconfigure until it recogizes it, and press the buttons on that controller in order. The joystick should be configured as the D-pad, and for all of the buttons that the board doesn't have (ie. right & left shoulder) use the xbox controller's joystick to skip them.
