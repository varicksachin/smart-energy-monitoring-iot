# Smart Energy Monitoring using IoT

Real-Time Electricity Theft Detection & Anomaly Analysis using ESP32 + Firebase

## Overview

This project is a smart energy monitoring system that performs real-time electricity monitoring, anomaly detection, and theft analysis using IoT edge processing and cloud computing technologies.

The system uses ESP32 for data processing and Firebase for cloud-based storage and visualization.

---

## Objectives

- Design and develop a real-time electricity monitoring system
- Detect abnormal usage patterns such as theft and sudden spikes
- Transmit electrical data to cloud for remote monitoring
- Provide alert mechanisms for abnormal conditions
- Build a scalable and cost-effective smart energy solution

---

## Working Principle

The system calculates electrical power using:

P = V × I

Where:
- P = Power (Watts)
- V = Voltage
- I = Current

The ESP32:
- Reads or simulates voltage and current values
- Computes real-time power consumption
- Applies threshold-based anomaly detection

### Detection Categories
- NORMAL — Safe Usage
- SPIKE — Sudden Rise
- THEFT — Abnormal High Usage

---

## System Workflow

Voltage & Current Data
↓
ESP32 Processing
↓
Anomaly Detection
↓
WiFi Transmission
↓
Firebase Realtime Database
↓
Dashboard Visualization & Alerts

---

## Architecture Overview

ESP32 → Data Processing → WiFi → Firebase → Dashboard → Alerts

---

## Hardware Components

- ESP32 MCU
- Buzzer
- Power Supply Module
- Voltage & Current Sensors (future integration)

---

## Software Stack

- Arduino IDE
- Embedded C/C++
- Firebase Realtime Database
- Web Dashboard / ThingsBoard
- Real-Time Analytics

---

## Key Features

- Real-time monitoring with edge-level anomaly detection
- Cloud-based storage and live data visualization
- Threshold-based alerts
- Modular low-cost architecture
- Scalable smart grid integration

---

## Future Scope

- Machine Learning anomaly detection
- Mobile app alerts
- Smart grid integration
- Automatic power cutoff
- Live sensor-based monitoring

---

## Technologies

- IoT
- ESP32
- Firebase
- Edge Computing
- Smart Grid
- Real-Time Analytics

---

## Status

Project under development.
