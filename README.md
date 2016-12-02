4digit-7segment-12pin-arduino
=============================

Multiplexed 4 digit 7-segment display for arduino
code example from @rafaelzaleski

**Coded for common Anode display**
If you have a common cathode display refer to @rafaelzaleski original repo
OR change all the "HIGH" to "LOW" & "LOW" to "HIGH"

I'm using a basic 4-dig 7seg Display (Blue) from https://www.sparkfun.com/products/9481
NOTE** 16 pins, opposed to 12, so you may need to redirect your pins
use 330 ohms resistors to protect your display.
** (I used 220 ohms resistors and they worked just fine.)

I also changed the order of the multiplexing of 5ms from D1 to D4
 * So the timer builds up quickly from right to left, rather than left to right.
 
