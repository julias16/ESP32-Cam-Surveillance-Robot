# ESP32-CAM Surveillance Robot

> A Wi-Fi-enabled surveillance robot powered by the ESP32-CAM module, designed for real-time video streaming, remote navigation, and intelligent environmental monitoring.

---

# Overview

The **ESP32-CAM Surveillance Robot** is a Wi-Fi-controlled robotic vehicle that combines real-time video streaming with wireless navigation. Built around the ESP32-CAM module, the robot allows users to remotely monitor environments while controlling movement through a web interface.

The system is designed as an affordable surveillance solution for educational, research, and IoT applications. In addition to live video streaming, the robot supports remote motor control and can be extended with additional sensors such as flame, gas, or ultrasonic sensors for autonomous monitoring. ESP32-CAM robots are commonly used for low-cost wireless surveillance and remote control applications. :contentReference[oaicite:0]{index=0}

---

# Objectives

## General Objective

Develop a low-cost wireless surveillance robot capable of live video streaming and remote navigation using the ESP32-CAM module.

## Specific Objectives

- Stream live video over Wi-Fi.
- Enable wireless robot movement.
- Build an affordable surveillance platform.
- Demonstrate IoT and embedded system concepts.
- Support future autonomous navigation.
- Provide a scalable robotics platform for research and learning.

---

# Features

- Live video streaming
- Wi-Fi remote control
- Mobile and desktop browser access
- Forward, backward, left and right movement
- Stop command
- Low-latency wireless communication
- ESP32-CAM onboard camera
- Portable battery-powered operation
- Expandable sensor support
- Compact robotic chassis

---

# Hardware Components

| Component | Purpose |
|-----------|---------|
| ESP32-CAM (AI Thinker) | Main controller & camera |
| FTDI Programmer | Upload firmware |
| L298N Motor Driver | Motor control |
| DC Gear Motors | Robot movement |
| Robot Chassis | Mechanical platform |
| Wheels | Navigation |
| Li-ion Batteries | Power supply |
| Battery Holder | Power management |
| Switch | Power control |
| Jumper Wires | Connections |

---

# Software Requirements

- Arduino IDE
- ESP32 Board Package
- C++
- HTML
- CSS
- JavaScript
- Wi-Fi Network

---

# System Architecture

```
                User Device
          (Mobile / Laptop)
                    │
               Wi-Fi Network
                    │
             ESP32-CAM Module
                    │
         ┌──────────┴──────────┐
         │                     │
   Camera Streaming      Motor Control
         │                     │
         │                L298N Driver
         │                     │
         └──────────┬──────────┘
                    │
                DC Motors
                    │
             Robot Movement
```

---

# Project Structure

```
ESP32-Cam-Surveillance-Robot/
│
├── Arduino_Code/
│   └── ESP32_CAM_Robot.ino
│
├── Web_Interface/
│   ├── index.html
│   ├── style.css
│   └── script.js
│
├── Images/
│
├── Circuit_Diagram/
│
├── Documentation/
│
├── README.md
└── LICENSE
```

---

# Working Principle

1. Power on the robot.
2. Connect the ESP32-CAM to a Wi-Fi network.
3. Open the ESP32-CAM IP address in a web browser.
4. View the live video stream.
5. Control the robot using the on-screen directional buttons.
6. Commands are transmitted over Wi-Fi to the ESP32-CAM.
7. The ESP32-CAM controls the motor driver to move the robot.
8. Live video continues streaming during robot operation.

---

# Pin Configuration

| Module | Connection |
|---------|------------|
| ESP32-CAM | Main Controller |
| L298N | Motor Driver |
| DC Motors | Robot Movement |
| Battery | Power Supply |

> Modify the GPIO mapping according to your hardware configuration.

---

# Installation

Clone the repository.

```bash
git clone https://github.com/julias16/ESP32-Cam-Surveillance-Robot.git
```

Open the Arduino sketch.

```text
Arduino_Code/ESP32_CAM_Robot.ino
```

### Install ESP32 Board

1. Open Arduino IDE.
2. Install the ESP32 board package.
3. Select **AI Thinker ESP32-CAM**.
4. Choose the correct COM port.

Upload the program using an FTDI programmer.

---

# Usage

1. Power the robot.
2. Connect it to your Wi-Fi network.
3. Find the IP address from the Serial Monitor.
4. Open the IP address in a browser.
5. Watch the live camera feed.
6. Control the robot remotely.

---

# Applications

- Home surveillance
- Office monitoring
- Educational robotics
- IoT learning
- Remote inspection
- Laboratory monitoring
- Security demonstrations
- Research projects

---

# Future Improvements

Future versions may include:

- Obstacle avoidance
- Flame detection
- Gas leak detection
- Motion detection
- Object tracking
- Face recognition
- Cloud video storage
- Mobile application
- Two-way audio communication
- AI-powered surveillance
- GPS navigation

---

# Technologies Used

## Hardware

- ESP32-CAM
- L298N Motor Driver
- DC Motors
- Li-ion Battery

## Software

- Arduino IDE
- Embedded C++
- HTML
- CSS
- JavaScript

---

# Acknowledgements

This project was developed to explore embedded systems, IoT, wireless communication, and robotics using the ESP32-CAM platform.

---

# Contributing

Contributions are welcome.

1. Fork the repository.
2. Create a new feature branch.
3. Commit your changes.
4. Push the branch.
5. Submit a Pull Request.

---

# License

This project is released for educational and research purposes.

---
