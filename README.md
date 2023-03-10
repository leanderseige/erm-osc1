# Simple Oscillator as Eurorack Module

I was looking for a small project for my first Eurorack module and I chose to build a simple (not voltage controlled) oscillator.

## Circuit

The circuit diagram that inspired me was: http://www.learningaboutelectronics.com/Articles/Function-generator-circuit.php

I was lucky and found all components in my already available stock from 30 years of DYI'ing electronics. For instance the OpAmp and the 33nF capacitor must  clearly be from the past century.

I changed some of the details and finally came out with this schematic:

![](schematic.png)

I added a 100nF capacitor on each output channel in order to remove DC components which seemed to be present in one or another form all the time.

It was clear from the beginning that I would need at least two potentiometers in order to allow comfortable access to the huge frequency spectrum.

## Panel

The file panel.stl contains a printable panel with a simple element to hold a standard eurocard PCB. I printed it just as it is and drilled the holes for the potentiometers and the audio-jacks later. 

