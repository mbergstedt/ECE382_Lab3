ECE382_Lab3
===========
##SPI - "I/O"
###Purpose
Practice communicating with the MSP through external devices.
###Preliminary Design
The mega pre-lab can be found in the repository, along with the answers on the charts in the middle of the lab.
###Hardware Design
The hardware for this lab is the LCD display on top of the MSP chip.
###Debugging
I ran the debugger to allow the program to be put on the chip.
###Testing Methodology/Results
I was able to get the program to draw an 8x8 box on the display, but I was not able to get it to move around in time.  It also took me awhile to figure out how to get the logic analyzer to function, primarily because I was initially forgetting to connect to the CS pin.  I was also unsure what all I needed to capture from the logic analyzer.

My waveform from the logic analyzer is:
![alt text](https://github.com/mbergstedt/ECE382_Lab3/blob/master/Waveform.JPG?raw=true)

My answers for the writing modes section are:
![alt text](https://github.com/mbergstedt/ECE382_Lab3/blob/master/Writing%20Modes.jpg?raw=true)
###Observations/Conclusions
Adding the a functionality to the program does not seem like it would take much longer to complete, however, I'm occasionally having trouble when setting the location for the box, where it will initialize at the edge of the display and only show half of the box.
###Documentation
None
