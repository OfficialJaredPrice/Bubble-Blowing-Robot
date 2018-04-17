# Bubble-Blowing-Robot
A robot that blows bubbles

This repository is the documentation of the creation of the bubble-blowing robot. The design was to create an autonomous bubble-blowing robot but was altered to be more dependent. The machine will use motors to dip a bubble wand into bubble solution and then manuever it to a fan which will blow the bubble. Also comes equipped with wheels to transport itself. Currently only moves straight, but changes are to come soon. 

REPOSITORY CONTENTS:

The contents of this repository are:

img - folder containing relevant images such as build and circuit diagram

LICENSE - contains licensing information

scr - contains project source code


MATERIALS:

You will need the Arduino IDE installed on your computer to do this project. As far as material goes there is a great deal of flexibility. In the case of this project, the following materials were used:

Arduino Uno

Breadboard

Novelty children's fan

Bubble wand

Bubble solution

Baking tray

10 quarter-inch wooden dowel 30cm long

Popsicle sticks (~70)

Hot glue with gun

9 AA batteries

2 9V batteries

string of 10 red solo cup novelty LED's

3 IR sensors

A 12V motor capable of moving this contraption

A1015 transistor

560Ohm resistor


BUILD INSTRUCTIONS:

Most of the build has little impact on the overall functionality of the machine. However, key building notes are provided below.
The dimensions of the machine's frame are 23*45*9cm for the frame (w*l*h). The trusses of the frame span ~15cm each to provide a uniform support system to the frame. The bottom IR sensor is placed adjacent to the wheel to prevent accidental bumping and to provide signal if the wheel loses contact with the ground. Other information about build, such as the wiring, can be inferred from images provided in img file or by commenting questions which will be responded to.


FIRMWARE INSTRUCTIONS:

To install the software on this device simply copy and paste the code at src into the arduino IDE


USAGE:

To use this project simply upload the code provided at src to the arduino. Once this code is uploaded there are several other points to mention. The code for the servo arm provided in src may not be calibrated to the build. It will likely require some trial and error as position zero may be a different location depending on build. The fan and LED's run on a circuit entirely independent of the arduino and will require manual input to change these switches. The servo arm and drive motor should run according to input from the IR sensors. A final source of maintenance will be the management of the bubble-solution reservoir. To maintain maximum efficiency, the reservoir should be kept full and in the path of the moving bubble wand. 
 
 
TEAM:

Jared Price - Sole contributer to project

If you wish to contribute to this project, simply add a pull request


CREDITS:


 Bernard Glass - An Instructables user that provided the inspiration for this project as well as some ideas about design. 
                 His project can be found at: http://www.instructables.com/id/Bubblesteen-Bubble-Machine/
