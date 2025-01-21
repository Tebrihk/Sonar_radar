# Sonar_radar
This project involves creating a radar system using an Arduino Uno, ultrasonic sensor, and a servo motor. The ultrasonic sensor is mounted on the servo motor, which rotates to scan the surroundings. The radar visualizes the distance of objects in its path using Processing software.

# Components

# Hardware

Arduino Uno: Microcontroller to control the system.

Ultrasonic Sensor: Measures the distance of objects.

Servo Motor: Rotates the ultrasonic sensor to scan the environment.

Breadboard: Used for wiring connections.

Jumper Wires: Connect components.

# Software

Arduino IDE: For writing and uploading the code to the Arduino.

Processing Software: To create a graphical radar interface.

# Features

Object Detection: The ultrasonic sensor detects objects and measures their distance.

Rotating Scan: The servo motor rotates the sensor to cover a range of angles.

Radar Visualization: Real-time distance data is sent to Processing software for graphical display.

# Software Setup

Install the Arduino IDE and Processing Software on your computer.

Upload the Arduino code to the Arduino Uno.

Run the Processing sketch to visualize the radar.

Code Overview

Arduino Code

Controls the servo motor to rotate the ultrasonic sensor.

Measures the distance of objects using the ultrasonic sensor.

Sends distance and angle data to the computer via serial communication.


# Steps to Build

Assemble the hardware according to the circuit diagram.

Write and upload the Arduino code to control the servo and ultrasonic sensor.

Open the Processing sketch and run it to view the radar visualization.

Power on the Arduino and observe the radar system in action.

# Applications

Object detection and distance measurement.

Learning project for interfacing sensors and motors with Arduino.

Visualization techniques using Processing software.

# Troubleshooting

No Data in Processing: Ensure the correct COM port is selected in both Arduino IDE and Processing.

Sensor Not Detecting Objects: Check the ultrasonic sensor connections and verify the code logic.

Servo Not Rotating: Confirm the servo motor is powered and properly connected to the control pin.

# Future Improvements

Add multiple ultrasonic sensors for a 360-degree radar.

Improve visualization with color-coded distance indicators.

Store data for analyzing object movement trends.

# Credits

Developed using Arduino and Processing software. Hardware includes components widely available for hobbyists and educational purposes.
