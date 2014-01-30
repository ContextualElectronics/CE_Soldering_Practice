CE_Soldering_Practice
=====================

A board for learning how to solder without breaking anything.  This one is supposed to act as a little example circuit to show the amplication effect of a 741 opamp on an oscillating signal.  The 555 outputs a squarewave at around 100hz, which then passes through an RC filter to soften the edges of the square and then another capacitor to remove the DC component of the signal.

Because the signal that is fed into the 741 isn't a true square anymore, you can actually see when the amp gets saturated, and see the variations in amplification due to changing the resistor values more easily on an oscilloscope.

As of 27-JAN-2014, the headers are designed as follows...

Middle board 3 socket header: +9v, -9v and Ground (two 9v batteries in series, with the center as ground reference).

End Board 7 pin header: 1. Oscilloscope test point: pre-amp
                        2. Oscilloscope test point: post-amp
                        3. Oscilloscope Ground
                        4. Signal Resistor IN 
                        5. Signal Resistor OUT 
                        6. Feedback Resistor IN 
                        7. Feedback Resistor OUT 
