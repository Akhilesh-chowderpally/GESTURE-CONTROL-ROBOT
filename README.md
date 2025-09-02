# 🤖 Gesture Controlled Robot

A **tilt-to-drive rover** that reads **hand motion** with an **MPU6050** on an **Arduino Nano transmitter** and sends commands over an **NRF24L01** link to an **Arduino Uno receiver**, which drives four DC motors via an **L298N** for smooth forward, reverse, and precise turns.  

The MPU6050 fuses **accelerometer + gyroscope data** for stable gesture mapping, while **2.4 GHz communication** ensures **low-latency and power-efficient control**.

---

## 🌟 About The Project
This project demonstrates an **intuitive gesture-based control system** for robotics.  

- 🖐️ **Hand tilt → robot motion** mapping.  
- 📡 **Wireless communication** with NRF24L01 (2.4 GHz).  
- ⚙️ **Four DC motors** driven by L298N for accurate movement.  
- 🧭 **Sensor fusion** of accelerometer & gyroscope ensures stable control.  

Aimed at **robotics learning, assistive tech, and intuitive HMI (Human-Machine Interface)** development.

---

## 🛠️ Built With
- **Arduino Nano (Transmitter)** + **Arduino Uno (Receiver)**.  
- **MPU6050 IMU** (accelerometer + gyroscope, I²C).  
- **NRF24L01 transceivers** (3.3V, hardware SPI).  
- **L298N motor driver** + **4 geared DC motors** (PWM + direction control).  
- **C++ (Arduino)** using **Arduino IDE / PlatformIO**.  

---

## 📺 Demo
🎥 Click the preview below to watch the full video demonstration on YouTube:  

[![Watch the demo](https://img.youtube.com/vi/YOUR_VIDEO_ID/0.jpg)](https://youtube.com/shorts/mNUse7H-aHc?feature=share))

---

## ⚡ Features
- **Gesture-controlled navigation**: Forward, Reverse, Left, Right.  
- **MPU6050 sensor fusion** for stable tilt readings.  
- **Low-latency RF link** with NRF24L01.  
- **PWM motor driving** for smooth control.  
- Expandable to include **speed modes, obstacle sensors, or camera module**.  

---

## 📂 Repository Structure
```bash
📦 gesture-robot
 ┣ 📂 transmitter_code   # Arduino Nano (MPU6050 + TX)
 ┣ 📂 receiver_code      # Arduino Uno (Motors + RX)
 ┣ 📂 docs               # Schematics, images, diagrams
 ┣ 📜 LICENSE
 ┣ 📜 README.md
 ┗ 📜 requirements.txt   # Arduino / PlatformIO libraries

