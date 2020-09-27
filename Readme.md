## Simple Engraver

A simple X/Y plotter for use with a laser diode.

<img src="https://user-images.githubusercontent.com/45019189/88856522-07f0a880-d1cb-11ea-8b37-6dba98c19da6.jpg" height="300">
<img src="https://user-images.githubusercontent.com/45019189/88856968-d2988a80-d1cb-11ea-8baa-74b1b8c8df84.jpg" height="300">
<img src="https://user-images.githubusercontent.com/45019189/88859044-5e5fe600-d1cf-11ea-9cb4-e3b57fb75890.gif" height="300">

https://www.youtube.com/watch?v=ll7KeXLQTyo


### Printed parts:

* 2x Y-Axis Carriage
* 1x X-Axis Carriage
* 4x Feet



### BoM:

* 1x Pair of Good Laser Goggles
* 10x 5mm ID roller wheels - Either 21.5mm OD or 24mm OD
* 10x M5x30mm Bolts
* 10x M5 Nuts
* 34x M3x10mm Bolts
* 28x M3 T-Nuts
* 6x M3 Nuts
* 34x M3 Washers
* 3x 2040 Extrusion - T-Slot if using 21.5mm Wheels otherwise V-Slot for 24mm OD Wheels
* 1x GRBL Control board*
* 1x PWM Laser Diode with Heatsink
* 3x A4988 Stepper Drivers
* 3x Nema-17 Stepper Motors (Low power motors are fine)
* 1x Stepper motor splitter (To drive 2x Y-Axis motors)
* 3x 20-tooth GT2 5mm ID Motor Pulley
* 1x 5m GT2 Belt (Length required will depend on your 2040 extrusions)


You can use washers to help protect your printed parts, it's optional. 

For the 2040 extrusion, the longer the extrusions the bigger your engraving area will be. 
You can mix/match pieces or use two pieces of 2020 extrusion together to get 2040. I used 3x 500mm 2040 for my build.


There are lots of options for the control board. You can find Arduino UNO and Arduino Nano CNC shields for a very low cost. 
For my build, I used a Keyestudio KS0288. If your control board doesn't have two Y-Axis outputs, you will need a splitter.


For stepper motor drivers, I chose A4988 because I have a lot of them.
You could opt for something like DRV8255 or TMC drivers if that is more readily available.


I use software endstops, so I haven't bothered to add physical limit switches yet. 
You could always just stick some endstops on with epoxy or modify the models.


I use a 12V PWM switchable, adjustable focus laser. There is not a Z axis yet so adjustments are done manually.
Make sure the wavelength of your laser is protected by your safety glasses!


You can fasten the feet to a sheet of plywood or a table to increase rigidity of the assembly. 
Tension the belts by pulling the belt tight and tensioning the M3 bolt on top so that it bites into the belt.

https://www.thingiverse.com/thing:4556472

Adam's Lab<br>
www.adamslab.ca<br>
@adamsprints on Instagram
