# Line Follower Robot

A simple autonomous robot that detects and follows a line path using infrared (IR) sensors. This project is designed for beginners to learn about basic robotics, sensor integration, and control systems.

## 🚀 Project Overview

The Line Follower Robot uses IR sensors to detect a black line on a white surface (or vice versa) and follows the path accordingly. Based on the readings from the sensors, the robot adjusts its movement using motors controlled by a microcontroller.

## 🔧 Components Used

- 1x Microcontroller (e.g., Arduino UNO)
- 2x IR Sensors (or a sensor array)
- 2x DC Motors
- 1x Motor Driver Module (e.g., L298N)
- 1x Chassis (robot body)
- 1x Battery Pack (6V–12V)
- Jumper Wires, Wheels, and Casters

## ⚙️ How It Works

The robot continuously reads data from the IR sensors:
- If both sensors detect white: the robot moves forward.
- If the left sensor detects black: the robot turns left.
- If the right sensor detects black: the robot turns right.
- If both detect black: the robot stops or realigns.

More advanced versions can use PID control for smoother turns and higher accuracy.
