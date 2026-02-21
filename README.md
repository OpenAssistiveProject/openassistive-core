# OpenAssistive Core

OpenAssistive is an open social assistive technology initiative focused on building low-cost, modular mobility systems for blind and visually impaired persons.

This repository defines the core architecture, system design principles, and technical foundations of the OpenAssistive project.

---

## Mission

To design and document open, repairable, modular assistive mobility systems that complement traditional white cane usage through sensor integration, haptic feedback, and offline computing.

OpenAssistive prioritizes:

- Accessibility  
- Affordability  
- Repairability  
- Offline capability  
- Open documentation  
- GPL-licensed software  
- Social purpose first  

---

## System Architecture Overview

The OpenAssistive system is modular and composed of:

- Smart cane sensor sleeve (ToF sensors)  
- Microcontroller (real-time sensor processing)  
- Raspberry Pi compute unit (vision, audio, logic)  
- Haptic feedback module  
- Audio interaction module  
- Textile-integrated cabling system  

### Data Flow

Sensors → Microcontroller → Compute Unit → Haptic / Audio Output  

This separation ensures real-time reliability and modular scalability.

---

## Design Principles

- Modular hardware architecture  
- Separation of real-time and high-level processing  
- Energy efficiency and power budgeting  
- Textile-integrated cabling  
- Offline-first computing  
- Open hardware & software under GPLv3  

---

## Repository Structure (Planned)

```
/docs
/hardware
/firmware
/software
/electronics
/mechanical
```

---

## Development Status

Phase 1 – Architectural definition and documentation  
Phase 2 – Sensor sleeve prototype  
Phase 3 – Microcontroller integration  
Phase 4 – Compute unit integration  
Phase 5 – Field testing  

---

## License

This project is licensed under the GNU General Public License v3 (GPLv3).

Copyright (C) 2026 Milton Rodolfo Amador Zúniga

---

OpenAssistive Project  
Open Social Assistive Technology Initiative
