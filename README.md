# Gesture-Voice-SmartHome
Gesture and Voice Controlled Smart Home System

---

## 📌 Overview

The Gesture and Voice Controlled Smart Home System is an intelligent home automation solution that allows users to control electrical appliances using natural human inputs such as voice commands and hand gestures.

The system eliminates the need for traditional remote controls or mobile applications and provides an accessible, user-friendly, and efficient automation experience.

---

## ❓ Problem Statement

Most existing home automation systems rely heavily on smartphones or physical remotes, which may not be intuitive or accessible for all users.

This project aims to develop a smart home system that responds to voice commands and hand gestures, offering a more natural and interactive way of controlling appliances.

---

## ✨ Features

- Voice-based appliance control (Offline recognition)
- Gesture-based appliance control
- Real-time response system
- Safe appliance switching using relay module
- Motor control using L298 driver
- User-friendly and accessible design

---

## 🛠 Technologies Used

### Software
- C++ (Arduino IDE)

### Hardware
- Arduino Uno
- SEN0539 Gravity Voice Recognition Module
- SEN0285 Gesture and Touch Sensor Module
- 1-Channel 5V Relay Module
- L298 Motor Driver
- Power Supply Unit

---

## ⚙️ Working Flow

1. The user gives a voice command or performs a hand gesture.
2. The respective input module detects the command.
3. The detected input is sent to the Arduino Uno.
4. The Arduino processes the input and identifies the required action.
5. A control signal is sent to the relay module or motor driver.
6. The appliance or motor responds accordingly.

---

## 🔌 Hardware Description

### Arduino Uno
Acts as the central controller of the system. It receives inputs and controls output devices.

### SEN0539 Voice Recognition Module
- Offline voice recognition
- 121 built-in commands
- Supports 17 custom commands
- Communicates via I2C/UART

### SEN0285 Gesture Sensor
- Detects 7 types of gestures
- Adjustable range (0–30 cm)
- Built-in gesture recognition algorithm

### 1-Channel 5V Relay Module
- Controls high-voltage appliances
- Provides electrical isolation
- LED status indicators

### L298 Motor Driver
- Drives DC motors
- Supports high voltage and current
- Over-temperature protection
- Bidirectional motor control

---

## 📂 Project Structure

Gesture-Voice-SmartHome/
├── main.ino
├── gesture_module.ino
├── voice_module.ino
├── relay_control.ino
├── motor_driver.ino
├── README.md
└── images/
├── setup.png
├── gesture.png
└── voice.png

