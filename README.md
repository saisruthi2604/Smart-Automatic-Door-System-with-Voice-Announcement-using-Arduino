# Smart Automatic Door System with Voice Announcement

## 📌 Project Overview

The Smart Automatic Door System with Voice Announcement is an Arduino-based mini project designed to automate door operation using an IR sensor and a voice announcement system.

The system detects a person approaching the door using an IR sensor. Once a person is detected, the DC motor rotates through an L298N motor driver to simulate the opening of the door. At the same time, a welcome voice message is played through a speaker using the DFPlayer Mini audio module.

After a predefined delay, the motor rotates in the opposite direction to simulate the automatic closing of the door.

## 🎯 Objectives

- To develop a basic automatic door mechanism using Arduino.
- To detect approaching people using an IR sensor.
- To control the opening and closing mechanism using a DC motor.
- To integrate voice announcements using the DFPlayer Mini audio module.
- To gain practical experience in embedded systems and hardware interfacing.

## ⚙️ Components Used

- Arduino Uno
- IR Sensor
- L298N Motor Driver
- DC Motor
- DFPlayer Mini MP3 Module
- Speaker (8Ω, 5W)
- MicroSD Card
- 9V Battery / Motor Power Supply
- Jumper Wires
- USB Cable

## 🔄 Working Principle

1. The IR sensor continuously monitors the area near the door.
2. When a person approaches, the IR sensor detects the presence of an object.
3. The Arduino receives the sensor signal and activates the motor through the L298N motor driver.
4. The DC motor rotates to simulate the opening of the door.
5. Simultaneously, the DFPlayer Mini plays a pre-recorded welcome voice message through the speaker.
6. After a predefined delay, the motor rotates in the opposite direction to simulate closing the door.
7. The system returns to its initial state and waits for the next detection.

## 🔌 Technologies Used

- Embedded Systems
- Arduino Programming
- Embedded C/C++
- Sensor Interfacing
- DC Motor Control
- Audio Module Integration

## 💡 Applications

- Smart homes
- Office entrances
- Educational institutions
- Automated entry systems
- Basic contactless door automation prototypes

## 🚀 Future Enhancements

- Integrate Raspberry Pi and a camera for face recognition.
- Recognize registered individuals and announce their names.
- Provide a guest announcement for unregistered visitors.
- Add IoT-based monitoring and remote access.
- Integrate access control and security features.

