# chitu3d
FFF FDM 3D Printer Controller
Chitu V1.3.16

Support for direct update.cbd print file to be updated to support the Japanese, Traditional, French, German and other languages, an increase of two-servo support, modify the firmware to adapt to the new 2.8 screen

Chitu V1.3.15

More in one out of the back to optimize, you can multi-nozzle simultaneously designated length, more into a drawing will be improved. The display of the screen to do a certain program of adaptation, when the firmware and the screen or firmware and Ui does not match, there will be more user-friendly tips. Double-headed double supplies detection support. Modified the pre-extrusion length can not be zero bug.

Chitu V1.3.14

Fixed a two rounded out a circular gradient effect of the poor bugs, an increase of the three into a support, an increase of the configuration M8027 S0; 0: 1 into more than one out: more into a out, so you can more out of a Share a temperature sensor

Chitu V1.3.13

Fixed some of the motherboard update to V1.3.12 can not start the problem, repair the “restore factory” can not clear the leveling data bug, mini board to increase the power to save features to improve a number of other small details

Chitu V1.2.1

Fixed the movement of the core code, so there is no scope of movement restrictions. Makerbot limit the structure of the cura slice zero, so that it will first to 0. Perfect with the new wifi module support

Chitu V1.2.0

Fixed the double-head makerware slow back bug, fix the double-headed ABS heating bug, a complete test of the single-headed, a variety of slicing software compatibility

 

Chitu V1.1.9

Fix the makerbot hit ABS heating bug, 3.5-inch screen perfectly compatible

 

Chitu V1.1.8
Increase the ban hotbed of the code, modify the timing, so that the band line and narrow line can be displayed properly, modify the pause and stop the bug

Chitu V1.1.7
PID algorithm to improve the PWM output, better, increase the support of the Delta, the increase of the normally closed limit switch support, fix the makerbot primer when the problem of speed too fast, remove the wire back down the code Z,
Added the delta setting code on the interface and modified the mask settings at the beginning of the limit

Chitu V1.1.6
Modify the acceleration and deceleration algorithm, turn smoother, increase the screen saver, increase the shutdown interface,

Chitu V1.1.5
Increase the beautiful interface support, fix the number of saved parameters bug, an increase of the E2 as a function of Z, an increase of the motherboard with the extrusion head temperature switch function.
Increased V3.2 board EEPROM write protection function, the XY step number separated

 

Chitu V1.1.4
Increase M8031, M8032 instructions, used to set the second extrusion head offset, mainly used to compatible ReplicatorG and Makerware software, repair speed before xy, z speed is not limited by parameter settings bug
Restrictions on the re-optimized way to increase the cycle of debugging, temporary set parameters such as functions. Increase the cycle function, an increase sd card print documents function, repair suspended print bugs, …
The temperature algorithm is optimized to support M303 temperature auto-modulation

Chitu V1.1.3
Add two new instructions M8027 and M8029, were used to configure the number of extrusion head and limit type, the software has been fully support the K-type thermocouple and double extrusion head settings
But also for a variety of limit types are slic3r, cura, replicatorG, makerware for a better compatibility
In this case,

Chitu V1.1.2
The M8020 parameter will M8020 Ixxx into M8020 Sxxx, the original M8020 Ixxx is also compatible to support the kisser slices relative E slicing

Chitu V1.1.1  2014 09 26
Increased support for H-bot models

Chitu V1.1 2014 09 25
Interface, multi-color customization, support MAX_6675, boot logo customization
