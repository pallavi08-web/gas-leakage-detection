# Automatic Gas Regulator with Gas Leakage Detection & Auto-Shut-Off System

## Overview
This project presents an Automatic Gas Regulator system designed to improve household and commercial kitchen safety by detecting LPG gas leakage and automatically shutting off the gas supply.

The system integrates:
- Real-time gas leakage detection
- Automated gas shut-off mechanism
- Alert indication system
- Manual override control

The project combines embedded systems, gas sensing technology, and mechanical actuation mechanisms to create a smart safety solution for LPG-based environments. :contentReference[oaicite:0]{index=0}

---

## Problem Statement
LPG cylinders are widely used in homes and commercial kitchens. Gas leakage caused by:
- Faulty regulators
- Damaged pipes
- Improper handling

can lead to dangerous accidents such as:
- Fires
- Explosions
- Toxic exposure

Leakage is often detected only after gas concentration becomes dangerously high, increasing safety risks significantly. :contentReference[oaicite:1]{index=1}

---

## Objectives
- Detect LPG gas leakage in real time
- Automatically shut off gas supply during leakage
- Provide audio/visual safety alerts
- Implement a servo-driven mechanical shut-off mechanism
- Include manual override functionality for user control

:contentReference[oaicite:2]{index=2}

---

## Working Principle

The system continuously monitors LPG concentration using an MQ-series gas sensor.

### Process Flow
1. Gas sensor detects LPG concentration.
2. Arduino UNO processes sensor readings.
3. If gas concentration exceeds threshold:
   - Buzzer alert activates
   - Servo motor rotates
4. Crank-slider mechanism converts rotary motion into linear motion.
5. Gas valve automatically closes.
6. Manual override buttons allow user intervention.

The system ensures immediate response during hazardous gas leakage situations. :contentReference[oaicite:3]{index=3}

---

## Gas Detection Threshold

The project assumes LPG concentration above:

:contentReference[oaicite:4]{index=4}

is considered hazardous and requires automatic response. :contentReference[oaicite:5]{index=5}

---

## Crank-Slider Mechanism

The auto shut-off mechanism uses a crank-slider arrangement.

### Motion Conversion
The mechanism converts:

:contentReference[oaicite:6]{index=6}

This allows the servo motor rotation to actuate the gas valve and stop LPG flow automatically.

The mechanism can operate in:
- In-line configuration
- Offset configuration

depending on design requirements. :contentReference[oaicite:7]{index=7}

---

## Components Used

| Component | Purpose |
|---|---|
| Arduino UNO | Main controller |
| MQ Gas Sensor | LPG leakage detection |
| SG90 Servo Motor | Valve actuation |
| Electromagnetic Buzzer | Alert indication |
| Push Buttons | Manual override |
| Breadboard & Jumper Wires | Circuit connections |
| 3D Printed Valve Attachments | Mechanical shut-off assembly |

:contentReference[oaicite:8]{index=8}

---

## Features
- Real-time LPG monitoring
- Automatic gas shut-off
- Embedded safety alerts
- Servo-driven mechanical control
- Manual override support
- Compact and low-cost implementation
- Smart safety automation

---

## Technologies Used
- Embedded Systems
- Arduino Programming
- Gas Sensing Technology
- Servo Motor Control
- Mechanical Linkage Systems
- Safety Automation Systems

---

## Applications
- Household kitchens
- Commercial cooking systems
- LPG storage environments
- Industrial gas safety systems
- Smart home safety automation

---

## Learning Outcomes
This project helped in understanding:
- Gas sensing systems
- Embedded controller interfacing
- Servo motor actuation
- Safety-critical automation
- Mechanical motion conversion systems
- Real-time monitoring and control

---

## Future Enhancements
Future improvements may include:
- GSM-based emergency alerts
- IoT monitoring dashboard
- Mobile application integration
- Automatic ventilation control
- Cloud-based gas monitoring
- AI-based leakage prediction

---

## Conclusion
The Automatic Gas Regulator system successfully demonstrates an intelligent safety solution for LPG leakage prevention. By integrating gas sensing, embedded control, mechanical actuation, and automated shut-off functionality, the project provides a practical and effective approach to reducing gas-related hazards in domestic and commercial environments.
