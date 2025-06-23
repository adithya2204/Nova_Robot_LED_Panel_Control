# Nova Robot LED Panel Control

## Overview

This repository contains the code and documentation for the LED panel control system developed as part of the Nova Robot project in the Microcontrollers and Embedded Systems course at Amrita Vishwa Vidyapeetham. The Nova Robot is a fully 3D-printed, open-source interactive robot designed to foster engagement and learning in educational, home, and therapeutic settings. The included ledcontrol.ino file is a custom Arduino sketch enabling expressive facial animations on a five-panel 8×8 LED matrix array, forming the robot’s “face.” The code supports multiple eye and mouth expressions, responding to serial commands for dynamic feedback. The repository also documents the assembly process for the LED panels, including wiring and integration with the robot’s electronics. This contribution demonstrates practical skills in embedded programming, hardware assembly, and open-source collaboration, and serves as a resource for students and hobbyists interested in robotics, Arduino, and interactive display systems.

## Repository Structure

- **ledcontrol.ino**  
  Arduino sketch for controlling a five-panel LED matrix array, enabling dynamic eye and mouth expressions via serial commands.

- **/docs/**  
  (Optional) Add assembly instructions, wiring diagrams, and integration notes here.

## Key Features

- Supports multiple facial expressions (neutral, happy, sad, surprised, etc.)
- Serial command interface for real-time control of eyes and mouth
- Designed for MAX7219-based 8×8 LED matrices (x5)
- Easily extendable for new animations or expressions

## Assembly Highlights

- Five 8×8 LED matrices are connected in series and mounted to form the robot’s face
- Arduino UNO is used for driving the panels, with connections for DIN, CLK, and CS pins
- Careful orientation and wiring ensure correct panel sequencing and animation flow

## How to Use

1. Connect five MAX7219-based 8×8 LED matrices to an Arduino UNO as per the wiring in the code comments.
2. Upload `ledcontrol.ino` using the Arduino IDE.
3. Send serial commands to the Arduino to change facial expressions.

## Applications

- Educational robotics
- Interactive displays for STEM workshops
- Open-source hardware projects

## Acknowledgments

- LED control and assembly: Adithya Pothula
- Project developed at Amrita School of Engineering, Amritapuri Campus

## License
