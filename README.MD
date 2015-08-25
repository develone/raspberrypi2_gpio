08/24/15
This repo is RPi GPIO Code Samples
http://elinux.org/RPi_GPIO_Code_Samples

08/25/15
Modified the example code for Raspberry Pi 2 B
http://elinux.org/RPi_GPIO_Code_Samples
Note: For Raspberry Pi 2, change BCM2708_PERI_BASE to 0x3F000000 for the code to work.


Tested the example code code by using 3 470 ohm resistors & 3 leds.
The resistor were connected to PMOD3 CHAN23, PMOD3 CHAN24, and PMOD3 CHAN25
with the leds anodes connected to grd. 
/*
#define BCM2708_PERI_BASE        0x20000000
This code was for Raspberry Pi
Note: For Raspberry Pi 2, change BCM2708_PERI_BASE to 0x3F000000 for the code to work. 
*/
#define BCM2708_PERI_BASE        0x3F000000

GPIO11 PMOD3 CHAN23 net s0 loc = h2;
GPIO09 PMOD3 CHAN24 net s1 loc = f1;
GPIO10 PMOD3 CHAN25 net s2 loc = f2;


