
#  Smart Dustbin for Home

An **ESP32-based smart waste management system** that automates trash disposal using sensors, enabling **touchless operation, wet/dry segregation, overflow detection, and remote-controlled mobility**.

---

##  Overview

The Smart Dustbin is designed to improve **household hygiene, convenience, and environmental responsibility** by integrating embedded systems and IoT concepts.

It eliminates manual interaction with waste and ensures proper segregation at the source—critical for effective recycling.

---

##  Features

*  **Touchless Lid Operation**
  Ultrasonic sensor detects hand/object → automatically opens lid

*  **Automatic Wet/Dry Waste Segregation**
  Moisture sensor classifies waste → servo directs to correct bin

*  **Overflow Detection & Alerts**
  Ultrasonic sensors monitor fill level → buzzer alerts when full

*  **Remote-Controlled Movement**
  Bluetooth-controlled mobility (F/B/L/R commands)

*  **Hygienic & User-Friendly Design**
  Minimizes direct contact with garbage

---

## 🧠 System Architecture

The system follows a **Sensor → Controller → Actuator** model using ESP32.

###  Modules

1. **Lid Automation + Waste Sorting**

   * Ultrasonic sensor detects object
   * Moisture sensor classifies waste
   * Servo directs waste to appropriate bin

2. **Overflow Detection**

   * Ultrasonic sensors monitor bin levels
   * Buzzer alerts when threshold reached

3. **Remote Mobility**

   * Bluetooth commands control DC motors via motor driver

---

## 🛠️ Hardware Components

| Component                    | Quantity |
| ---------------------------- | -------- |
| ESP32                        | 1        |
| Ultrasonic Sensors (HC-SR04) | 3        |
| Moisture Sensor              | 1        |
| Servo Motor                  | 1        |
| DC Motors                    | 2        |
| L293D Motor Driver           | 1        |
| Buzzer + LEDs                | 1        |
| Battery (18650)              | 2        |
| Perfboard                    | 1        |
| Chassis + Wheels             | 1        |

---



If you want, I can also:

* Add **circuit diagrams section**
* Convert this into a **portfolio-grade README (with badges + GIFs)**
* Or tailor it specifically for **placements / resume projects**
