# STM32-Based Smart Acquisition and Diagnostic Instrument

## 📌 Project Overview

The **STM32-Based Smart Acquisition and Diagnostic Instrument** is a portable, multi-functional monitoring prototype designed to measure physical parameters and identify abnormal operating conditions in equipment such as motors and industrial appliances.

The system integrates temperature, humidity, and vibration sensing into a single instrument. It displays real-time measurements, provides visual and audible alerts, and stores time-stamped diagnostic data on an SD card for further analysis.

## 🎯 Objectives

- Monitor equipment operating conditions using multiple sensors.
- Identify potential abnormal conditions through configurable diagnostic thresholds.
- Display real-time sensor readings on a TFT display.
- Provide visual health indications using PWM-controlled LEDs.
- Record sensor readings with timestamps for future reference.
- Develop a compact and user-friendly instrument for equipment monitoring.

## ⚙️ Key Features

- **Multi-Sensor Monitoring:** Measures temperature, humidity, and vibration.
- **Real-Time Display:** Presents sensor readings and operating status on a TFT display.
- **Equipment Health Indication:** Uses LEDs to indicate normal, suspected-anomaly, and critical conditions.
- **Diagnostic Data Logging:** Stores sensor measurements and timestamps on an SD card.
- **Real-Time Clock (RTC):** Maintains timestamps for recorded measurements.
- **Mode Selection:** Push buttons allow users to select applications and switch between measurement and diagnostic modes.
- **Audible Feedback:** A buzzer provides feedback for button actions, mode selection, and relevant warnings.
- **Safe SD Card Handling:** Indicates when data is being written and when the card is safe to remove.

## 🛠️ Hardware Components

| Component | Purpose |
|---|---|
| STM32 Microcontroller | Main processing and control unit |
| Temperature Sensor | Monitors equipment temperature |
| Humidity Sensor | Measures surrounding humidity |
| Vibration Sensor | Detects equipment vibration |
| TFT Display | Displays measurements and diagnostic status |
| SD Card Module | Stores diagnostic data |
| RTC Module | Provides date and time information |
| Push Buttons | Select modes and navigate the interface |
| PWM-Controlled LEDs | Indicate equipment health status |
| Buzzer | Provides audible alerts |

## 💻 Technologies Used

- Embedded C / C++ for firmware development
- STM32 microcontroller platform
- HTML, CSS, and JavaScript for the web-based prototype
- GitHub for source code management
- GitHub Pages for hosting the web prototype

## 🔄 System Workflow

1. **System Initialization:** The instrument starts with a loading animation and performs peripheral checks.
2. **Application Selection:** The user selects the equipment or application to monitor.
3. **Mode Selection:** The user chooses measurement mode or diagnostic mode.
4. **Data Acquisition:** The STM32 reads the connected sensors and processes their measurements.
5. **Status Indication:** The TFT display and LEDs present the readings and corresponding equipment health status.
6. **Data Logging:** In diagnostic mode, sensor readings are recorded with timestamps on the SD card.
7. **Safe Removal Indication:** The instrument indicates when writing is complete and the SD card can be safely removed.

## 🌐 Interactive Web Prototype

The web prototype demonstrates the proposed instrument's interface, monitoring concept, and diagnostic workflow.

**Live Prototype:** [Click here to access the website](https://your-username.github.io/your-repository/)

*Replace the example URL with the actual GitHub Pages link after deployment.*

## 📂 Repository Structure

```text
STM32-Smart-Diagnostic-Instrument/
├── index.html
├── style.css
├── script.js
└── README.md
```

The repository contains the web prototype files. Embedded firmware and hardware
