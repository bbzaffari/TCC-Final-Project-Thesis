---
---
# **Cooling–Link** – *A Dependable Wireless Monitoring and Control Ecosystem for Cold Storage Environments*

---
> **Disclosure Note**  
>  This document contains descriptions of the Cooling Link Ecosystem and MC.C., which are currently under patent review.  In compliance with institutional and legal requirements, certain implementation details and architectural diagrams have been intentionally omitted or generalized. The full technical disclosure will be made available upon completion of the patent filing.
---


---

# Overview


Maintaining optimal humidity and temperature levels in cold storage rooms is essential for preserving the shelf life and quality of perishable goods. However, in countries like Brazil—where fruit warehouses often operate dynamically with frequent door openings and high ambient moisture—conventional monitoring solutions fall short. These environments demand robust, cost-effective, and modular systems that adapt to real-world usage patterns without compromising reliability.

This work presents the development of a scalable monitoring system called Cooling Link, designed to address this issue through a practical and cost-effective approach.

---
## 📜 Intellectual Property Notice

© 2025 Bruno Bavaresco Zaffari. All Rights Reserved.



---
---
---


##### Related Modules

The following external modules were developed and integrated as part of this project to provide hardware abstraction, sensor interfacing, and communication protocols: 

* [`OneWire`](https://github.com/bbzaffari/OneWire) – OneWire bus implementation for ESP-IDF.
* [`DS18B20-ESP-IDF`](https://github.com/bbzaffari/DS18B20-ESP-IDF) – Driver for the DS18B20 temperature sensor.
* [`SHT-30-31-ESP-IDF`](https://github.com/bbzaffari/SHT-30-31-ESP-IDF) – ESP-IDF driver for Sensirion SHT30/SHT31 sensors.
* [`HTU-31D-ESP-IDF-C`](https://github.com/bbzaffari/HTU-31D-ESP-IDF-C) – Low-level driver for the HTU31D humidity and temperature sensor.
* [`LoRa-Protocol-ESP-IDF`](https://github.com/bbzaffari/LoRa-Protocol-ESP-IDF) – Custom lightweight protocol built over LoRa (PHY) for structured device communication.


##### Adapted modules (credited)

The following modules were adapted or refactored based on work from other developers. Full credits are given in their respective repositories:

* [`lora-phy`](https://github.com/bbzaffari/lora-phy) – LoRa (PHY layer) – from nopnop.
* [`esp-idf-ssd1306-Minimal-Version`](https://github.com/bbzaffari/esp-idf-ssd1306-Minimal-Version) – Minimal OLED SSD1306 driver adapted for performance and memory safety  – from nopnop.

