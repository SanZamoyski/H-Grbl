# H-Grbl
This project is intended to run Grbl on a system based on H-bridges and Arduino Nano (and clones): 
Grbl is a no-compromise, high performance, low cost alternative to parallel-port-based motion control for CNC milling.

More informations and files can be found here: http://xn--zabaaganionemiejsce-8fd.pl/arduino/h-grbl/

Installation:
Just extract H-Grbl library into libraries folder and use H-Grbl example file.

TODO: 
* convert digital/analogWrite to port manipulations
* repair disable steppers function - propably will be repaired by converting to port manipulation
* check what in homing cycle can be problematic for X-microstepping
* Put some settings in defaul settings file.
* $H for non-modal/modal and other situations (motion_control.c, 252 line).

DONE:
* $H to set X=0, Y=0, Z=10 (motion_control.c, 258-260 lines)


If You like my work, please 

donate by PayPal: https://www.paypal.com/cgi-bin/webscr?cmd=_donations&business=XS8G3MZ896XNQ&currency_code=EUR&source=url

or directly: https://paypal.me/sanzamoyski
