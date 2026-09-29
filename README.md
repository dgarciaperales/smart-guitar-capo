# Smart Guitar Capo 

![Build Status](https://img.shields.io/badge/build-passing-brightgreen)
![Firmware Version](https://img.shields.io/badge/firmware-v1.0.0-blue)
![License](https://img.shields.io/badge/license-MIT-green)
![Platform](https://img.shields.io/badge/platform-ESP32%20%7C%20iOS%20%7C%20Android-orange)

A hybrid hardware-software project that combines a 3D-printed guitar capo with embedded IoT hardware and web-based audio analysis to help guitar users see which note they are currently playing via electronic status display. In other words, its an intelligent guitar capo equipped with embedded sensors and Bluetooth connectivity. Smart Capo detects real-time fret position, monitors string tension and tuning accuracy, and syncs seamlessly with a mobile companion app for auto-transposition, tabs, and performance analytics.

---

## Table of Contents

- [Key Features](#-key-features)
- [System Architecture](#-system-architecture)
- [Hardware & Component List](#-hardware--component-list)
- [Getting Started](#-getting-started)
  - [Prerequisites](#prerequisites)
  - [Firmware Setup](#firmware-setup)
  - [Mobile App Setup](#mobile-app-setup)
- [Usage & Calibration](#-usage--calibration)
- [Repository Structure](#-repository-structure)
- [Contributing](#-contributing)
- [License](#-license)

---

## Key Features

- **Real-Time Fret Detection:** Automatically detects which fret the capo is clamped onto.
- **Auto-Transposition:** Instantly transposes chord charts and tabs in the app based on capo placement.
- **Tension & Pressure Monitoring:** Prevents sharp notes and neck damage by alerting you if the clamp is too tight or loose.
- **Integrated Micro-Tuner:** Provides quick tuning verification directly from the capo's LED display.
- **Low Energy Bluetooth (BLE):** Long battery life with fast, seamless pairing to iOS and Android devices.

---

## System Architecture
