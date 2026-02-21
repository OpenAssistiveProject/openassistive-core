OpenAssistive System Architecture
Version 1.1
Author: Milton Rodolfo Amador Zúniga
License: GPLv3

1. System Overview

OpenAssistive is a modular assistive mobility platform composed of distributed sensing, real-time embedded processing, and high-level compute logic.

The system is divided into two primary processing domains:

Real-time embedded domain (microcontroller)

High-level compute domain (Raspberry Pi class device)

This separation guarantees deterministic behavior for safety-critical sensor feedback while enabling advanced features such as computer vision and audio interaction.

2. Core Components
2.1 Smart Cane Sensor Sleeve

Time-of-Flight (ToF) distance sensors

Environmental obstacle detection

Modular attachment system

2.2 Microcontroller Unit

Real-time sensor acquisition

Distance filtering and threshold logic

Haptic trigger control

Communication interface (UART / USB / I2C)

2.3 Compute Unit

Computer vision processing

QR reading

Object recognition (future extension)

Audio synthesis and feedback

System orchestration

2.4 Haptic Feedback System

Coin vibration motors

Directional intensity mapping

Low-latency response (<50 ms target)

2.5 Audio Interaction Module

Headset output

Voice feedback

Offline-first speech processing

3. Data Flow

Sensors → Microcontroller → Compute Unit → Haptic / Audio Output

The microcontroller guarantees timing stability.
The compute unit handles complex logic and perception tasks.

4. Power Model

Estimated average consumption: 8–12W
Battery target: 20,000 mAh power bank
Expected autonomy: 6–10 hours

Power domains are isolated between embedded and compute subsystems.

5. Design Principles

Modular architecture

Offline-first computing

Repairability

Low-cost components

Textile-integrated cabling

GPL-licensed ecosystem

Social impact priority

6. Future Extensions

GPS assist module

Offline mapping

Wireless cane module

Indoor beacon navigation

Distributed sensor expansion

OpenAssistive Project
Open Social Assistive Technology Initiative
