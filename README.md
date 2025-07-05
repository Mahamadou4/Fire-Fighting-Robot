# Firefighting Robot

![image](https://github.com/user-attachments/assets/2ea07175-4bdd-4875-a418-f43e32ea15e9)


This project is a flame-detecting robot built using Arduino. The robot uses three IR flame sensors to detect the direction of a flame and a submersible water pump to extinguish it.

## Features

- Detects flame direction (left, right, center)
- Moves toward flame automatically
- Uses a servo to sweep water across the flame
- Fully autonomous behavior based on sensor input

## Components

- Arduino Uno R3  
- 2 DC motors with wheels  
- 3 IR flame sensor modules  
- L298N motor driver  
- L293D motor driver shield  
- SG90 servo motor  
- Submersible water pump  
- Vinyl tube  
- 9V battery  
- Breadboard and wires  
- Car chassis  
- Soda can (used as water tank)

## How It Works

The robot continuously checks its IR sensors. Based on which sensor detects the flame, it turns in that direction. When the front sensor detects the flame, the robot moves forward and stops. It then activates the water pump and sweeps the servo to spray water side-to-side.

## Demo

- Demo Video: [YouTube](https://youtube.com/shorts/Bu0i_9VdLD8?feature=share)  

## Skills Used

Arduino, C/C++, Embedded Systems, Sensor Integration, Circuit Design, AutoCAD, 3D Printing

## Team

Mahamadou Nimaga  
Edward Serrano-Rodriguez  
Muhaimin Ali
