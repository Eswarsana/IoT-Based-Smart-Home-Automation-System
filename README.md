# IoT-Based Smart Home Automation System

## Project Overview

The IoT-Based Smart Home Automation System is developed using Arduino Uno, IR sensors, a Bluetooth module, and servo motors to automate household appliances.

The system detects a person's presence using IR sensors. When a person approaches a particular area, the system automatically switches ON the corresponding lights and fans and opens the door using a servo motor. Sensor data is transmitted to the Telnet mobile application through Bluetooth for monitoring and recording.

## Hardware Components

| S.No | Component | Purpose |
|---|---|---|
| 1 | Arduino Uno | Main controller |
| 2 | IR Sensors | Detect human presence |
| 3 | Bluetooth Module | Wireless communication |
| 4 | Servo Motor | Automatic door operation |
| 5 | Lights | Lighting control |
| 6 | Fans | Fan control |
| 7 | Connecting Wires | Hardware connections |
| 8 | Power Supply | System power |

## Software Requirements

- Arduino IDE
- Telnet Mobile Application
- Arduino Programming (C/C++)

## Arduino Pin Configuration

| S.No | Component | Arduino Uno Pin |
|---|---|---|
| 1 | Bluetooth RX | D2 |
| 2 | Bluetooth TX | D3 |
| 3 | IR Sensor – Light | D4 |
| 4 | IR Sensor – Fan | D5 |
| 5 | IR Sensor – Door | D6 |
| 6 | Light Control Output | D7 |
| 7 | Fan Control Output | D8 |
| 8 | Servo Motor Signal | D9 |

## Working Principle

1. IR sensors detect the presence of a person near the designated areas.
2. Arduino Uno processes the sensor signals.
3. When a person is detected, the corresponding lights and fans are switched ON.
4. The servo motor automatically opens the door when a person is detected near the entrance.
5. The Bluetooth module transmits sensor information to the Telnet mobile application.
6. The mobile application displays and records the received sensor data.

## Technologies Used

- Internet of Things (IoT)
- Arduino Uno
- IR Sensor Technology
- Bluetooth Communication
- Embedded C/C++
- Servo Motor Control

## Key Features

- Automatic person detection.
- Automatic light and fan control.
- Servo-based automatic door operation.
- Wireless Bluetooth communication.
- Mobile-based sensor data monitoring.

## Project Outcome

Developed an IoT-based Smart Home Automation prototype that automates household appliances based on human presence and provides wireless sensor-data monitoring through a mobile application.

## Author

**Sana Omkareswar**
