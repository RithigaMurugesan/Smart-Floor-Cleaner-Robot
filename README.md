SMART FLOOR CLEANER ROBOT

  The Smart Floor Cleaner Robot is an Arduino-based autonomous robotic system designed to clean floor surfaces while avoiding obstacles. This project demonstrates the practical application of embedded systems, sensor integration, and motor control to build a simple yet effective cleaning robot.

PROJECT OVERVIEW
 
  This robot moves automatically across the floor and collects dust using a suction mechanism. It continuously monitors its surroundings using an ultrasonic sensor. Based on the detected distance, the robot decides whether to move forward or change direction. The Arduino microcontroller acts as the control unit that processes sensor input and controls all the connected components in real time.
 
PROJECT OBJECTIVE
 
  The main objective of this project is to design and develop a low-cost autonomous floor cleaning robot that can operate without human intervention. It aims to reduce manual cleaning effort and demonstrate how basic robotics and embedded programming can be used to automate household tasks.

 HARWARE COMPONENTS
- Arduino UNO– Central controller that processes sensor data and controls motors  
- Ultrasonic Sensor (HC-SR04) – Detects obstacles by measuring distance  
- Motor Driver (L298N / L293D) – Controls the speed and direction of DC motors  
- DC Motors (2 units) – Provide movement to the robot  
- Suction Fan Motor – Used to collect dust and debris  
- Battery Pack– Supplies power to the system  
- Robot Chassis – Physical body of the robot  

 SOFTWARE & TECHNOLOGIES
- Embedded C (Arduino IDE)
- Sensor Interfacing
- Motor Control using Digital Signals
- Real-Time Decision Making

WORKING PRINCIPLE
 
  The ultrasonic sensor sends sound waves and receives the reflected signal to calculate the distance to nearby objects. If the path is clear, the Arduino instructs the motor driver to move the robot forward. When an obstacle is detected within a predefined range, the robot automatically changes direction to avoid collision. The suction fan operates continuously to collect dust while the robot navigates the area.

SYSTEM ARCHITECTURE

Ultrasonic Sensor → Arduino UNO → Motor Driver → DC Motors  → Suction Fan 

 Features

- Fully autonomous movement  
- Obstacle detection and avoidance  
- Continuous floor cleaning  
- Simple and low-cost design  
