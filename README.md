# Micro-Uno

A powerful, custom dual-microcontroller development board that combines the USB connectivity and compact form factor of the Pro Micro (`ATmega32U4`) with the classic pinout and versatility of the Arduino Uno (`ATmega328P`).

---

## 🚀 Key Features

* **Dual Microcontroller Architecture:**
  * **Core 1:** ATmega32U4 (`U1`) with native USB Type-C support, hardware serial, and HID capabilities.
  * **Core 2:** ATmega32P (`U2`) running with an external 16MHz crystal oscillator, providing classic Uno-compatible GPIO and analog channels.
* **Power & USB Interface:**
  * USB Type-C receptacle (`J1`) with CC1/CC2 pull-down resistors and a resettable PTC polyfuse (`F1`).
  * Comprehensive decoupling capacitance (`C1`-`C12`) ensuring stable power rails and clean clock signals.
* **Expansion & Connectivity:**
  * Dedicated ICSP headers (`J2`, `J3`) for direct programming of both microcontrollers.
  * Multi-pin breakout headers (`J4`, `J5`, `J6`) exposing full Port expansions (`PORTC`, `PORTD`, `PORTF`) for rapid prototyping.

---

## 📊 Schematic Overview

The schematic integrates both processor cores alongside robust power filtering and extensive pin breakout headers on a single A4 sheet.

<p align="center">
  <img src="https://github.com/user-attachments/assets/984720e9-923e-4a0a-a719-bb8979c5a001" alt="Schematic Page" width="800"/>
</p>

---

## 🛠️ PCB Design & Routing

The PCB layout cleanly routes the dense dual-processor traces, keeping crystal oscillators close to their respective chips and managing power planes efficiently.

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
