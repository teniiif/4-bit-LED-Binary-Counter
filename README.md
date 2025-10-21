# 4 bit LED Binary Counter
## Overview
This is a simple binary counter which counts from 0 to 15 in binary (0s and 1s). When an LED is off it signifies a '0' and when it is on, it signifies a '1'.
The program returns the time taken for the count is 15 seconds and with this, it could also be used as a timer. When all LEDs come on, you know that 15 seconds have passed. The code makes use of 4 'if loops' for the count. If the condition of the if loop is met, an LED comes on or else, if goes off.

## Materials Used
* Raspberry Pi
* Breadboard
* 4 LEDs (1 red, 1 yellow, 1 blue and 1 green)
* 4 resistors (220 ohms)
* 4 male-to-male jumper wires
* 5 male-to-female jumper leads

## Wiring 
The wiring of the circuit is based on a simple LED connection where the cathode is connected to a GPIO pin while the anode is conncted to a resistor which is then connected to the ground. The table below ahows what the GPIO pins on the Raspberry Pi are connected to.
GPIO pin  | Component
------------- | -------------
GPIO 17 | Red LED
GPIO 27 | Yellow LED
GPIO 23 | Green LED
GPIO 24 | Blue LED



The images below show the wiring diagram as well as the schematics for the binary counter

<p align="center">
<img width="500" src="https://user-images.githubusercontent.com/85775364/174626870-f469d54c-2496-4523-bd9d-f1c53b705f16.jpg" alt="Binary Counter" >
</p> <p align="center">
  Wiring Diagram
</p> <p align="center">
<img width="500" src="https://user-images.githubusercontent.com/85775364/174626832-b73d8133-ba9c-477c-8a4d-08e605ccc339.jpg" alt="Binary Counter" >
</p><p align="center">
  Schematic
</p>



## Demo
Click the image below to play the video
<p align="center">
<a href="https://youtube.com/shorts/vSGquoHtdK4?feature=share" target="_blank"><img src="https://user-images.githubusercontent.com/85775364/174626281-6e4fda75-5f98-45d0-9ea6-804ef18a3ef5.JPG" alt="Binary Counter" width="400" height="400" /></a>
</p>
