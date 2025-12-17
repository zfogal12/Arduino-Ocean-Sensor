# Arduino-Based Temperature Logger for Marine Environments

## Overview
This project uses an Arduino microcontroller and a waterproof temperature sensor to log environmental temperature data. 
The goal is to simulate basic oceanographic instrumentation used on buoys and field deployments.

## Motivation
Ocean research relies on low-power, reliable sensors to collect data in harsh environments. 
This project explores how simple embedded systems can be used for environmental monitoring.

## Hardware
- Arduino Uno
- Waterproof DS18B20 temperature sensor
- Breadboard and jumper wires
- USB cable

## Software
- Arduino IDE
- C/C++ (Arduino)
- (Optional) Python for data analysis

## How It Works
1. The Arduino reads temperature data from the DS18B20 sensor.
2. Data is transmitted via serial communication.
3. Measurements are logged at fixed time intervals.

## Results
(Include photos, screenshots, or plots here once you have them.)

## Challenges & Lessons Learned
- Sensor calibration
- Noise in measurements
- Timing and data logging

## Future Improvements
- SD card data logging
- Waterproof housing
- Long-term deployment testing
