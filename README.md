# Arduino-ShieldLightProject
This Arduino project serves as a street light and accident detection system. When an accident is detected in dim lighting conditions, an SMS alert is sent automatically, providing information about the location for immediate assistance.
# Street Light Accident Detection System

## Project Description

This Arduino project serves as a street light and accident detection system that utilizes a light-dependent resistor (LDR) to measure ambient light and a vibration sensor (SW-420) to detect vibrations indicative of an accident. When an accident is detected in dim lighting conditions, an SMS alert is sent automatically, providing information about the location for immediate assistance.

## Features

- **Ambient Light Detection**: Monitors the surrounding light levels with an LDR to turn the system on or off.
- **Accident Detection**: Uses a vibration sensor to detect disturbances that may indicate an accident.
- **SMS Alerts**: Automatically sends SMS notifications to specified phone numbers when an accident is detected.
- **LED and Buzzer Indication**: Visual and audible alerts using an LED and a buzzer to signal the system's status.

## Installation

### Requirements
- Arduino board (e.g., Arduino Uno, Nano, etc.)
- SIM800L GSM module
- SW-420 vibration sensor
- Photoresistor (LDR)
- LED
- Buzzer
- Resistors (appropriate values for LDR)
- Jumper wires
- Breadboard (optional)
