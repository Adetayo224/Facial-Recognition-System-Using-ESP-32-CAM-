Facial Attendance System Using ESP32-CAM
This project implements a facial attendance system using the ESP32-CAM module. It captures faces in real time, recognizes them, and logs attendance automatically. This compact and low-cost solution is ideal for IoT-based attendance and access control systems.

Features
Real-time face detection and recognition

Automatic attendance logging

Low-cost and compact hardware solution

Wi-Fi connectivity for remote monitoring

Easy integration with existing IoT systems

Requirements
Hardware:

ESP32-CAM module

FTDI programmer (for uploading code)

Jumper wires

Breadboard or direct wiring setup

Software:

Arduino IDE (with ESP32 board support installed)

Required libraries:

ESP32 board package

esp32-camera library

Any face recognition or server-based face matching setup

Wiring Diagram
ESP32-CAM to FTDI Programmer:

U0R → TX

U0T → RX

GND → GND

5V → VCC

IO0 → GND (for programming mode)

Setup
Install the ESP32 board package in Arduino IDE.

Connect ESP32-CAM to FTDI programmer using the wiring above.

Select AI Thinker ESP32-CAM as the board in Arduino IDE.

Upload the facial attendance code to the ESP32-CAM.

Open Serial Monitor to view the assigned IP address.

Access the web interface via the IP in a browser to view the camera feed and attendance log.

Usage
Mount the ESP32-CAM in the desired location.

Access the live feed through the web interface.

The system will automatically recognize faces and log attendance.

Applications
School and workplace attendance tracking

Smart access control systems

Visitor logging in offices or secure areas
