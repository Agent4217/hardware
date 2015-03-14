# hardware
The repo for BBP hardware.

License: CC-BY-SA
http://creativecommons.org/licenses/by-sa/4.0/

Features:
Microcontroller
-	Texas Instrument Sitara AM335x, 1GHZ Cortex-A8 ARM
-	2 Programmable Realtime Units (PRU) to generate really high frequency step and dir signals
-	4GB eMMC
-	512M DDR3 memory
-	10/100M ethernet
-	microSD card
-	USB Host to connect USB disk, WiFi, Camera .etc
-	USB Device interface, shows to the computer as a mass storage device
Stepper drivers
-	5 to 6 DRV8825 stepper drivers
-	1/32 microsteps per step
-	Each capable of driving bipolar steppers up to 45V and 2.5A
-	Digital control of the current setting for each driver
Outputs
-	3 heaters, 2 for extruder and 1 for HBP
-	6 connectors for fan or LED light belt, all adjustable
Inputs
-	3 Thermistor (ADC) inputs
-	2 Thermalcouple (MAX6675) inputs
-	6 endstops
-	1 connector for external power button
Extensibility
-	50 pins FFC connector for 24 bits TFT LCD and touch screen
-	connector for 2 extended steppers
-	connector for 3 extended heaters
-	Serial connector to print debug log
-	Lots of pins broken out, including step, direction and enable pins for the stepper drivers

Inspired by the priors who have done a lot of great jobs before.

BeagleBone Black
Author: Beagleboard.org
http://beagleboard.org/

replicape
Author: Elias Bakken
http://www.thing-printer.com/

