# Micro-Uno

A robust, portable, and feature-rich development board that combines the flexibility and compact form factor of the Pro Micro (ATmega32U4) with advanced power management, wireless connectivity, and extensive data storage capabilities.

---

## 🚀 Key Features

* **Core Processing:** ATmega32U4 microcontroller (Pro Micro architecture) with native USB support and hardware serial communication.
* **Wireless Connectivity:** Integrated ESP32-S2-WROVER module providing robust Wi-Fi and advanced networking capabilities.
* **Advanced Power Management:**
  * USB Type-C interface for power and programming.
  * TP4056-based Li-Po battery charging circuit with status indicators.
  * MT3608 step-up (boost) DC-DC converter delivering a stable 5V output from a 3.7V battery cell.
  * AMS1117-3.3 LDO voltage regulator for dedicated, low-noise 3.3V peripheral rails.
* **Mass Storage:**
  * W25Q128 (128Mbit / 16MiB) SPI Flash memory for logging and data storage.
  * MicroSD card slot operating via the shared SPI bus with dedicated Chip Select (CS) management.

---

## 📊 Schematic Overview

The schematic is modularly designed, separating power generation, main processing units, memory interfaces, and wireless communication blocks to ensure signal integrity and ease of manufacturing.

<p align="center">
  <img src="https://github.com/user-attachments/assets/984720e9-923e-4a0a-a719-bb8979c5a001" alt="Schematic Page" width="800"/>
</p>

---

## 🛠️ PCB Design & Routing

The layout has been meticulously routed to minimize trace lengths on critical high-speed and power lines, utilizing proper decoupling capacitors (0.1µF and 10µF) near all IC power pins.

<p align="center">
  <img src="https://github.com/user-attachments/assets/9bfee50c-97f0-4596-9ddc-b2063e9f2433" alt="PCB Layout" width="800"/>
</p>

---

## 💡 3D Renders

### Top View
<p align="center">
  <img src="https://github.com/user-attachments/assets/c9dbace6-2a4e-40e4-aeac-3ce792a769a2" alt="3D Top View" width="600"/>
</p>

### Bottom View
<p align="center">
  <img src="https://github.com/user-attachments/assets/c9a71bed-4eff-4dbc-8ca3-34e86ab3a54f" alt="3D Bottom View" width="600"/>
</p>
