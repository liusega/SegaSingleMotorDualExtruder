# SegaSingleMotorDualExtruder

The is my dual extruder with only one extrusion step motor for 3d printing.
Now is a working prototype.

Most dual extruder needs two step motors for each hotend to do the job.
But i think it's way too heavy for an extruder.So I try just use one step motor to do the job.

The other problem with dual extruder is when one hotend is working, the second would cause ooze.
Ooze will make printing model caught a lot of unwanted results.
My solution is letting the second hotend to dock on a metal plate to block hot plastic drops from nozzel.
To do that first the second nozzel need to swing and raise above metal plate.
At the same time one filament need to be caught in between idler and extrusion gear teeth with enough pressure.

This project have to design a brand new extruder and different firmware to acomplish goals above.
Current firmware is fork from Marlin (https://github.com/MarlinFirmware/Marlin)
I will release them later.

Check out these video of this extruder
https://youtu.be/eSuJrgT880I?list=PL3762XmLwPYKiBUytoDqkcSuJ-bVJyzTX

