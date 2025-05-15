# Micromouse Power Subsystem – EEE3088F 2025

This repository contains the design files, documentation, and analysis for the Power Subsystem of the **Micromouse Robot** developed as part of the EEE3088F Design Project at the University of Cape Town (2025).

## 🚀 Overview

The power subsystem is responsible for safely powering the micromouse robot. It includes:
- A LiPo battery charging system
- Dual-mode charging current selection
- Two regulated power outputs (3.3 V and 5 V)
- A logic-controlled ON/OFF switch
- H-bridge drivers for up to four bidirectional DC motors
- Two external high-side load switches
- Battery voltage and current monitoring
- USB-C PD integration

## 📐 Key Specifications

- **Input Voltage:** 9 V from USB-C source  
- **Battery:** 3.7 V, 800 mAh LiPo  
- **Charging Modes:** 200 mA (slow), 600 mA (fast), logic-selectable  
- **Outputs:**  
  - 3.3 V @ 300 mA (±5%)  
  - 5 V @ 1.5 A (±5%)  
- **Switching:** Mechanical STSP switch to cut outputs and reduce quiescent current < 30 μA  
- **Battery Monitoring:** INA219 over I²C  
- **External Loads:** Two 5 V high-side switches (1 A each)  
- **Motor Control:** 4 bidirectional brushed DC motors via H-bridge drivers

## 🧠 Design Tools

- **KiCad 7.0** – PCB & schematic design  
- **JLCPCB** – Fabrication and part sourcing  
- **LaTeX** – Technical documentation  
- **Git** – Version control and collaboration

## 🧑‍🎓 Author
Pontsho Mbizo 
University of Cape Town – Department of Electrical & Computer Engineering  
EEE3088F Class of 2025  




