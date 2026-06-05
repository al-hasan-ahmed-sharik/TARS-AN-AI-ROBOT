# TARS-AN-AI-ROBOT
TARS is a compact AI assistant robot built using ESP32-S3. It integrates voice interaction, OLED display feedback, Wi-Fi connectivity, and sensor-based processing.

<img width="2048" height="1260" alt="tars" src="https://github.com/user-attachments/assets/936ab9df-3ba9-425c-9490-412c1c768781" />

## System Overview

TARS uses ESP32-S3 as the main controller. It handles:
- Voice processing
- Sensor data
- WiFi communication
- OLED display control

The OLED works as a visual interface (“robot eye”) and a Li-ion battery powers the system with TP4056 charging protection.

## Components

- ESP32-S3
- OLED Display (I2C)
- Li-ion Battery (3.7V)
- TP4056 Charging Module
- Microphone Module (optional)

## How It Works

1. ESP32-S3 boots up using battery power  
2. Initializes I2C communication  
3. OLED display shows startup animation  
4. Microphone starts listening for input  
5. Voice commands are processed  
6. WiFi connects for API data (time/weather/etc.)  
7. Output is shown on OLED display  
8. System returns to idle mode

## Operational Guide

1. Power on the robot  
2. Robot creates a WiFi hotspot  
3. Connect using mobile phone  
4. Open IP address shown on display  
5. Enter WiFi credentials  
6. System connects to internet  
7. Pair using verification code  
8. Robot is ready to use

## Author

Al Hasan Ahmed Sharik
