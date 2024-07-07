**NAME     :** VALLAMDASU NIRANJAN
**COMPANY  :** CODTECH IT SOLUTIONS
**ID       :** CT6ES607
**DOMAIN   :** EMBEDDED SYSTEMS
**DURATION :** June - Aug 2024
**MENTOR   :** - 

## Project Overview: Blinking of LED Using Arduino
Objective:
The primary goal of this project is to understand the basic functionality of an Arduino microcontroller by implementing a simple program to blink an LED. This project serves as an introductory exercise to familiarize oneself with Arduino programming, hardware interfacing, and the use of the Arduino Integrated Development Environment (IDE).

## Components Required:
1. Arduino Board (e.g., Arduino Uno) 
2. LED (Light Emitting Diode)
3. Resistor (220 ohms or appropriate value for the LED)
4. Breadboard (optional, for easy circuit assembly)
5. Jumper Wires
   
## Key Concepts:
Arduino Board: A microcontroller platform used for building digital devices and interactive objects that can sense and control physical devices.
Digital Pins: Pins on the Arduino board that can be configured as either input or output.
Sketch: The name given to programs written using the Arduino IDE.

## Steps to Implement the Project:

## Setting Up the Hardware:

1. Connect the long leg (anode) of the LED to a digital pin on the Arduino (e.g., pin 13,12,8).
2. Connect the short leg (cathode) of the LED to one end of the resistor.
3. Connect the other end of the resistor to the ground (GND) on the Arduino board.
   
## Writing the Arduino Sketch:

1.Open the Arduino IDE on your computer.
2.Write a simple program to control the LED (which is uploaded in above file Arduino-LED)

## Uploading the Sketch:

1.Connect the Arduino board to your computer using a USB cable.
2.Select the appropriate board and port from the Tools menu in the Arduino IDE.
3.Click the "Upload" button to compile and upload the code to the Arduino board.

## Observing the Output:

1. Once the sketch is uploaded, the LED's connected to pin 13,12,8 will start blinking with a one-second interval.
2. The digitalWrite function sets the pin to HIGH (5V) or LOW (0V), turning the LED on or off.
3. The delay function pauses the program for the specified number of milliseconds.
 
https://github.com/vallamdasuniranjan/CODETECH-Task1/assets/174948070/f189a497-efca-4182-aa1b-3dd73bd866a2

## Learning Outcomes:
1. **Basic Understanding of Arduino:** Gain knowledge of the Arduino board and its capabilities.
2. **Hardware Interfacing:** Learn how to connect and control external components (LED and resistor) with the Arduino.
3. **Programming Skills:** Develop fundamental skills in writing and uploading Arduino sketches.
4. **Circuit Design:** Understand the basics of electronic circuit design and the importance of using resistors with LEDs to limit current.

This project is a foundational exercise that paves the way for more complex and interactive projects involving sensors, actuators, and other components. By mastering this basic LED blink project, you can build confidence in working with Arduino and gradually move on to more advanced topics in electronics and programming.
