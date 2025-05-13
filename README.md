# Welcome!

Patch78 is my low profile split wireless keyboard design. 
If that hasnt put you off then scroll down to learn more!


## Why?

Well I'm a bit of a keyboard sicko, I also enjoy making things. 
I have used a Lily58 for about a year now and I love the splitboard lifestyle but there was some limitations for me personally. 
While I utilise layers as much as I can certain things I use more than I can justify for layers for example I added an extra row for the function keys something that many keyboard sickos feel the need to remove but I really need.

Additionally I felt the need for some extra coulmns for more function keys layer shifts ect, really you can think of this as a Lily58's bigger bother. 
However unlike the original Lily58 this design comes out the box with Nice!Nano v2 and Nice!View Support. 

## What?

Here is what you will need. 

- A left and right PCB
- Gateron Low Profile Switches of your choice (This board is ONLY compatible with Gateron LP *not* choc or MX)
- Two Nice!Nano v2 Controllers
- Two Batterys with JST-XHP-2 connectors
- Two Nice!View screens (Optional)
- 3D printed case. (for best result a resin print is recomended but FDM also produces good results.)
- 3D Printed TPU Wrist rests. (Optional)
- Keycaps. nSA profile is reccomended

If you are DIYing the board assembly you will also need
- onsemi 1N4148WS diodes x 78
- gateron low profile hot swap sockets x78
- JST Battery connector or equivelent.
- A 2 pole switch
- A Tactile Switch

In terms of tools for the DIY version you will need
- A soldering iron (preferibly with temp control)
- Some solder
- Some flux
- A pair of tweezers
- A heatproof soldering mat
- Some soldering clamps/helping hands

## How?

First of all this entirely depends on if you have opted to completly DIY or have a pre assembled board. If you have a pre assembled board skip to step 4

### Step 1
First we need to add Diodes to the board the diodes are on the back side of the board and only go in one direction. 
There should be a line etched on the diode closer to one side than the other.
This side should face towards the north side of the pad the easiest way to solder these is to hold it in place with a pair of tweezers and tac down one side of the diode then you can tac down the other side. 
Repeat this for all the diodes on both boards.

### Step 2
Now we need to solder down the hotswap sockets in place these should only fit one way around. 
Again if you hold them in place while you tac one side down then you should be able to come back for the second pad aftwards. 

### Step 3
Next is the remaing components to make the board nice nano capabile, the toggle switch the battery connector and the tactile button. these are a lot easier to solder as they are through hole components, but again the easiest thing to do is to hold it in place and tac down one pin then you can solder the other pins as it will hold itself in place. 

### Step 4
Finally its time to add the Nice!Nano and Nice!View if you are choosing to add that. Either you can solder them directly to the pcb or you can use some MillMax connectors so they are hot swap. 
Its important to note that the Nice!Nano is attached to the board upside down or optionally you can attach the Nice!Nano to the underside of the board. 
When soldering the Nice!Nano please ensure your soldering iron is set to no more than 270 C as it has been known to cause damage to the Nice!Nano if you solder it at a higher temprature. 

### Step 5
Now its time to upload the firmware to the Nice!Nano, if its fresh out the box simply plug in the controller and it will show up as a USB drive on your computer, the Nice!Nano has been used before you will need to hold down the tactile switch while plugging it in. Then simply drag the firmware file onto that usb drive then it will copy over and dissapear! Do this for each side using the appropriate firmwares then you will need to connect the batteries to both sides press the tactile button on both sides at the same time to get them to pair together. Now go to your computers bluetooth settins and you should see Patch78 as a device avilable to pair. 

### Step 6
Now its time to test the board is working, add a couple of the keys to the hotswap sockets and press it down to see if it types anything. If it does youre good to go put the PCB into the case then add the keys. You can then use ZMK Studio to reconfigure the layout to your liking. 
