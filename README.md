# 🚗 OBD-TRACKIFY (Coming Soon)

An open-source, plug-and-play vehicle telematics and physical cybersecurity reconnaissance tool. 

## 🔭 Project Overview
This repository will house the firmware, cloud infrastructure, and mapping dashboard for a custom hardware appliance designed to interface with a vehicle's **OBD-II network** while performing automated **Wi-Fi wardriving**. 

The goal is to map localized wireless architecture and audit signal spillover to identify vulnerable legacy networks (WEP/Open) from a moving perimeter.

## 🛠️ System Architecture (In Development)
* **Firmware:** C++ / ESP32 framework handling asynchronous Wi-Fi scanning and NMEA GPS sentence parsing.
* **Storage:** Localized cryptographic logging to an onboard SPI MicroSD module.
* **Analytics Dashboard:** A custom web UI using Leaflet.js to filter and visualize network risk profiles on an interactive map.

---
*Developed in collaboration with a Red Team security researcher. Firmware initialization scripts dropping soon.*
