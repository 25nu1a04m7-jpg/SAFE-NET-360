# SAFE-NET 360 🚨

### Multi-Layer IoT Safety System for Elderly People

## 📌 Problem Statement

Elderly people living alone may face falls, injuries, or emergencies without immediate help. Existing wearable safety systems may fail when the device is removed, forgotten, or unavailable. There is a need for a low-cost multi-layer system that can maintain safety monitoring even during such gaps.

## 💡 Project Overview

SAFE-NET 360 is a low-cost IoT-based elderly safety system that combines:

* 👕 Smart wearable
* 🏠 Home monitoring sensors
* 📍 GPS location tracking
* 🚨 Emergency alerts
* 🏷️ Backup BLE safety tag

The system reduces dependence on a single wearable device and provides multiple layers of safety monitoring.

## ⚙️ Main Features

* Fall detection
* GPS location tracking
* SOS emergency button
* Wearable removal detection
* Home movement monitoring
* Door activity detection
* Bed/chair occupancy monitoring
* Backup BLE tag
* Caregiver emergency alerts

## 🔧 Technologies Used

* ESP32
* MPU6050
* NEO-6M GPS
* SIM800L GSM
* PIR Sensor
* Magnetic Door Sensor
* Pressure/FSR Sensor
* Reed Switch
* BLE
* Arduino IDE
* Embedded C/C++

## 🔄 Working

Sensors collect information → ESP32 processes the data → unusual conditions are detected → location/status is checked → caregiver receives an alert.

## 🎯 Objective

To develop an affordable multi-layer IoT safety system that can reduce monitoring gaps and improve emergency awareness for elderly people living alone.

## 👩‍💻 Project Team

SAFE-NET 360 — Open Innovation in Hardware Project

## 📂 Repository Contents

* `code/` – Arduino programs
* `circuit/` – Circuit diagrams
* `documentation/` – Project documents
* `images/` – Prototype and project images
