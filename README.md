# Smart-Hand-Sanitizer
A IOT Based Smart Sanitizer using IR Sensor and Servo Motor.


## Overview
This project focuses on creating an automatic hand sanitizer dispenser using IoT, Arduino, an IR sensor, and a servo motor. The system is designed to provide a contactless and efficient solution for hand sanitization. The motivation behind embarking on this project lies in addressing the pressing need for advanced and hygienic solutions in the era of heightened health consciousness, particularly during the COVID-19 pandemic. As traditional methods of hand sanitization prove to be cumbersome and potentially less effective in public spaces, the integration of cutting-edge technologies such as IoT, Arduino, IR sensor, and servo motor presents an exciting opportunity to revolutionize this essential aspect of public health. The motivation is fueled by the desire to contribute to a safer and more convenient environment, enabling individuals to adhere to stringent hygiene practices effortlessly.

## Problem Statement
In the wake of global health concerns, there is a need for touch-free solutions to promote hand hygiene. This project addresses the challenge of providing a convenient and automatic hand sanitization process.

## Proposed Solution
The proposed solution involves the use of Arduino for control, an IR sensor for hand detection, and a servo motor for dispensing the sanitizer. IoT connectivity allows for remote monitoring and control.

Demo Video: 
https://github.com/Nishu2903/Smart-Hand-Sanitizer-/assets/117971452/ee96582f-8559-41df-b610-27c27f753d01


## Features
- Contactless hand sanitization
- IoT integration for remote monitoring
- Efficient use of sanitizer with servo-controlled dispensing
- User-friendly and automated operation

## Hardware Used
- Arduino board
- IR sensor
- Servo motor
- Sanitizer reservoir and dispensing mechanism
- IoT module (e.g., ESP8266)

## Software Technologies Used
- Arduino IDE for programming the Arduino board
- IoT platform (e.g., Blynk, ThingSpeak) for remote monitoring
- Circuit simulation software.

## Block Diagram
![block](https://github.com/Nishu2903/Smart-Hand-Sanitizer-/assets/117971452/a1c0d9ee-460c-42b5-8872-08ec664203ff)

## Circuit Diagram
![image](https://github.com/Nishu2903/Smart-Hand-Sanitizer-/assets/117971452/a44b50a8-c1f8-4bdc-bd4e-60dd7a8051fb)

## IR Sensor 
![image (1)](https://github.com/Nishu2903/Smart-Hand-Sanitizer-/assets/117971452/df18a9a4-68bb-451f-98b1-81817abc029a)

The IR Sensor Module consists of the following components:The infrared receiver Led and the photo diode constitute the main parts of this sensor module. The photo diode emits the infrared radiations which strike any object and reflect back with some angle. The IR receiver TSFF5210 detects these reflected radiations.
1. IR receiver TSFF5210
2. Photodiode
3. 100 ohm resistor
4. 10k resistor
5. 10k variable resistor
6. LM358 IC


## Workflow
1. IR sensor detects the presence of hands.
2. Arduino processes the signal and activates the servo motor.
3. Servo motor dispenses the sanitizer.
4. IoT module enables remote monitoring and control.

## Result and Discussion
The system successfully provides a touch-free hand sanitization experience. Challenges faced during implementation and potential improvements are discussed in detail.

## Scope of the Project
Future enhancements may include:
- Integration with a cloud-based analytics platform for usage statistics.
- Addition of multiple dispensing points for public spaces.
- Implementation of a feedback mechanism for low sanitizer levels.

Feel free to contribute, report issues, or suggest improvements!

