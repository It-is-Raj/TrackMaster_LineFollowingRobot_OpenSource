**Project Overview**

This project is a Line Following Robot designed to autonomously follow a black line on a white surface using PID control for smooth and accurate navigation. 
The robot is designed to use analog sensors to detect the line's position, and the PID controller adjusts the motors' speed to maintain a steady course,
correcting any deviation from the path in real time.

Key Features:
>PID Control: A proportional-integral-derivative (PID) controller is used to calculate the appropriate motor adjustments based on sensor input,
enabling smooth and precise line-following behavior.
>Sensor-based Navigation: The robot utilizes infrared (IR) sensors to detect the line and adjust its movement accordingly.
>Autonomous Operation: Once set up, the robot can run completely autonomously, following the line without human intervention.

This project serves as an excellent example of integrating robotics, control systems, and sensor technologies to achieve real-time decision-making and movement control.

**Hardware**
Microcontroller-
Arduino Nano: The Arduino Nano serves as the central controller for the robot. It processes sensor data and adjusts the motor speeds based on the PID algorithm to ensure accurate line-following behavior.

Motor Drivers-
TB6612FNG Motor Driver: Two TB6612FNG motor drivers control the N20 geared motors. 
Each motor driver allows for independent control of the left and right motors, enabling precise movement and turning.

Motors-
N20 Geared Motors: These small, high-torque motors are used to drive the robot. They provide enough power for smooth movement while being compact and efficient for the robot's size.

Sensors-
8-Channel IR Array: The robot uses an 8-channel infrared sensor array to detect the line. 
These sensors scan for the contrasting color of the line, providing feedback to the microcontroller for real-time navigation adjustments.

Custom 3D Printed Part-
Suction Impeller: A custom 3D-printed impeller is designed to generate suction for stabilizing the robot.
N20 wheels: A 20mm dia wheel for N20 motors.  
The STL files for the impeller(fan+mount) and wheels are included in this repository for easy printing.

Power Supply-
Can run on any  battery of suitable size from 2s to 3s.

Battery: A battery(e.g., lipo/lihv/li-on) 2s to 3s provides power to the Arduino Nano, drivers and motors. 

**Code**
The code for the Line Following Robot is still under active development.
It is being written for the Arduino Nano and uses a PID control algorithm to process inputs from the 8-channel IR sensor array and adjust the motor speeds accordingly.

however, this is perfectly compatible with the 8 array lfr code provided on the robojunkies website 
provided you change the switch pins according to the provided schematic in the repo.
