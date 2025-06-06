# Line-Follower-Robot-cum-Wifi-Controlled
# 🤖 Line Follower cum Wi-Fi Controlled Robot

A hybrid robot that combines autonomous line-following functionality with manual Wi-Fi-based control using the ESP8266 microcontroller. Built for educational, research, and hobbyist purposes, this robot showcases embedded systems, sensor integration, and IoT control.

---

## 📘 Overview

This project features a 2WD robot capable of two operational modes:

1. **Autonomous Mode**: Follows a black line using IR sensors.
2. **Wi-Fi Manual Mode**: Controlled through a browser-based interface over Wi-Fi.

This allows real-time switching between automation and manual remote operation.

---

## ⭐ Features

* Dual operation: autonomous and manual control
* Web-based control panel (no app required)
* IR sensor-based path detection
* ESP8266-hosted control interface
* Seamless mode switching
* Expandable architecture for further enhancement

---

## 🛠️ Technologies Used

* **ESP8266** (NodeMCU or ESP-01)
* **Arduino IDE** for programming
* **IR Sensors** for line detection
* **L298N** Motor Driver
* **DC Motors** with 2WD chassis
* **HTML + JavaScript** for web control interface
* **Li-ion Battery** with voltage regulation

---

## ⚙️ Installation & Setup

### Hardware Setup

1. Mount ESP8266, IR sensors, L298N, and motors on the chassis.
2. Connect:

   * IR sensors to digital pins
   * L298N to motor and ESP8266 GPIOs
   * Power modules using 7.4V or 9V battery

### Software Setup

1. Install **Arduino IDE**
2. Add **ESP8266 Board Package** in Boards Manager
3. Upload provided code to ESP8266
4. Modify Wi-Fi credentials in code (if using Station mode)

### Wi-Fi Setup

* Use **Access Point Mode** (robot creates its own network) or connect to an existing router
* Access the control interface using the robot's IP address in a browser

---

## 🕹️ Usage

### Mode 1: Autonomous Line Following

* Place robot on a black track
* IR sensors guide it to follow the line

### Mode 2: Manual Wi-Fi Control

* Connect to the robot's Wi-Fi or same local network
* Open browser and enter IP address
* Use directional buttons to control movement

---

## 🔧 Future Enhancements

* Battery level monitoring on UI
* Live camera streaming (ESP32-CAM)
* Ultrasonic sensor-based obstacle avoidance
* AI for smart path prediction
* Firebase/Blynk cloud data sync
* Voice control (Google Assistant/Alexa)
* Native Android app with Bluetooth support

---

## 📄 License

This project is open-source and available under the MIT License.
