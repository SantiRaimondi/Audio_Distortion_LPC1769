# Audio_Distortion_LPC1769
---
Here is the sample code of an audio distortioner implemented in the NXP LPC1769 breakout board using some drivers.

## Main code description

This example is basically a guitar peda, which takes a signal from the guitar into an 12-bit ADC and performs some operations to it.

The final circuit has an operational amplifier circuit (to range the input signal between 0V and 3.3V) as shown in the Ltspice schematic circuit.

The code provided has all proper comments about the effects but in summary this project is a version of the Arduino pedalshield (https://www.electrosmash.com/pedalshield).

For more information about the effects you can visit: https://www.electrosmash.com/forum/pedalshield-uno/114-how-to-start-programming-pedalshield-uno?lang=en
 
For a Drivers managing tutorial visit: https://gitlab.com/GabrielEValenzuela/electronicadigital_iii
