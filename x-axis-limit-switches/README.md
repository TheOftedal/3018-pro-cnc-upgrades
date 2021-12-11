# SainSmart Genmitsu 3018-PRO x-axis limit switch

X-axis limiter is based on two sub miniature leaf spring switches to sense when the spindle has reached the edge of the x-axis.
This leaves only a couple of millimeters to the edge of the x-axis on either side.
The switches are mounted to the frame with the original M5x16 screws and can thus be fitted with no manipulation of the frame.

## Files

This design consists of two files; x-axis-limit-switch-left and x-axis-limit-switch-right. These pieces are near identical but the right switch has a 2mm longer extrusion to accompany for the stepper motor screws.

## Parts

### Switch

The limit switch holder is designed around a sub miniature leaf spring switch with dimensions of approx. 6.5 x 12.8 x 5.8mm.
Example model that should fit this design: [CYT1073](https://www.amazon.com/Cylewet-25Pcs-Switch-Arduino-CYT1073/dp/B073TYWX86).

### Cables

Any pair of low power cables should suffice for this application. However it is recommended to use a maximum cable dimension of 1.5mm2 to make it easier to solder them onto the tiny switch contacts.

### Contacts

The original Genmitsu 3018-PRO control board has a standard dupont pinout for the limit switch connectors and it is therefore recommended to use a dupont crimping tool and connectors to connect the switches to the control board.

## How to

### Step 1 - 3D-print the holders

Print both 'x-axis-limit-switch-left' and 'x-axis-limit-switch-right' with your choice of printer and filament.

I have successfully printed the design with PLA and with the following settings:

- Extruder Temperature: 230c
- Platform Temperature: 50c
- Layer Height: 0.18mm
- First Layer Height: 0.22mm
- Infill: 15%
- Raft: No
- Supports: No

Due to printing without supports there may be some stringing in the screw holes but this can be easily scraped out with a knife.

### Step 2 - Solder the switches

Solder the cables to the C (Common) and NO (Normally Open) pins of the switch. I recommend to place a small piece of shrink tubing over the solder joints to avoid shortint the pins.

![Soldering](https://github.com/TheOftedal/3018-pro-cnc-upgrades/blob/main/x-axis-limit-switches/Images/step-2.jpg)

### Step 3 - Mount the switches to the 3D-printed holders

Fit the cables and switches through the hole of the 3D-printed holders making sure the switch leaf spring is pointing downwards.

![Fitting](https://github.com/TheOftedal/3018-pro-cnc-upgrades/blob/main/x-axis-limit-switches/Images/step-3.jpg)

### Step 4 - Mount the switches to the frame

Unscrew the middle two bolts holding the bottom guide rail and frame and mount the 3D-printed holders with the switches pointing inwards with the original M5x16mm bolts.

![Fitting](https://github.com/TheOftedal/3018-pro-cnc-upgrades/blob/main/x-axis-limit-switches/Images/step-4.jpg)

## Credits

The micro switch model used for illustration is created by Igor Lirtsman over at [GRABCAD](https://grabcad.com/library/dm1_series-limit-switch-1a-125v-1)

## Like this design?

[!["Buy Me A Coffee"](https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png)](https://www.buymeacoffee.com/TheOftedal)
