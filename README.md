# Remote-Controlled Obstacle Detection Car 🚗

This project involves building a remote-controlled car that can detect obstacles in its path using an ultrasonic sensor. The car is controlled via Bluetooth using a mobile application and uses an LED to indicate when an object is detected within a certain distance. This project is built using an Arduino microcontroller, making it suitable for beginners interested in IoT and robotics.

---

<p float="left">
   <img src="https://github.com/YajneshKumar2004/IoT-Project/blob/main/image-1.jpg" width="500"/>
   <img src="https://github.com/YajneshKumar2004/IoT-Project/blob/main/image-2.jpg" width="500"/>  
</p>

## 📜 Project Overview

Traditional remote-controlled cars rely on the user for navigation and are prone to collisions, especially in cluttered environments. This project integrates automatic obstacle detection to improve safety, ensuring the car halts and alerts the user when an obstacle is nearby. This combination of manual control and autonomous safety features provides a versatile and educational project for learning about IoT, sensors, and motor control.

---

## 🛠 Components Used

- **Arduino UNO**: Microcontroller to process Bluetooth commands and manage obstacle detection.
- **HC-05 Bluetooth Module**: Allows remote control from a mobile device via Bluetooth.
- **Ultrasonic Sensor**: Detects obstacles in the car’s path.
- **L298N Motor Driver**: Controls the motors for car movement.
- **LED**: Indicates when an obstacle is detected.
- **DC Motors**: Drive the wheels for forward, backward, and directional movement.
- **Battery Pack**: Powers the entire system.

---

## 🔧 Setup and Installation

1. **Hardware Setup**:
   - Connect the ultrasonic sensor, Bluetooth module, motor driver, and LED to the Arduino according to the circuit diagram provided.
   - Ensure all connections are secure, and verify power requirements for each component.

2. **Code Upload**:
   - Install the [Arduino IDE](https://www.arduino.cc/en/software).
   - Open the code file `obstacle_detection_car.ino` in the Arduino IDE.
   - Connect your Arduino UNO to your computer, select the correct COM port, and upload the code.

3. **Mobile App Control**:
   - Use a Bluetooth controller app (such as **Bluetooth RC Controller**) to connect to the HC-05 module.
   - Control the car's movement using the app’s interface, sending commands for forward, backward, left, and right directions.

---

## 🚀 Features

- **Bluetooth Control**: Allows the user to control the car remotely from a mobile device.
- **Obstacle Detection**: The ultrasonic sensor continuously monitors the path for obstacles, halting the car and turning on an LED when an obstacle is detected.
- **Safe Navigation**: The car resumes movement once the path is clear, ensuring safe navigation.

---

## 📝 Usage

- **Obstacle Detection Logic**:
  - The ultrasonic sensor detects obstacles within a 20 cm range.
  - If an obstacle is detected, the LED indicator turns on, and the car halts.
  - The car resumes movement and turns off the LED when the path is clear.

---



