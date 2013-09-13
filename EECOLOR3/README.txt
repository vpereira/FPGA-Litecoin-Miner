FPGA provided by EECOLOR3 devices (Cyclone 4, EP4CE30F23C6)

more information you can find here:

http://www.taylorkillian.com/2013/04/using-fpga-of-eecolor-color3.html

To mine, I had to change the mine.tcl (you can find it on the EECOLOR3/scripts directory), to add a timeout otherwise after sometime, the mine.tcl crashes

I'm mining on Linux, using a terasic usb blaster and I'm getting around 2.10KH/s locally and (2KH/s-5KH/s) on my pool statistics


I'm basically using the files from ../source/*, the files that I have to change, specifically for EECOLOR3 I'm copying to ./source and updating them on the project settings
