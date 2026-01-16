# JetController
An open‑source smart controller platform for RC planes (ESP32‑C3)
License: GPL‑3.0
JetController is an open‑source hardware and software project designed for RC planes, offering flexible PWM control, high‑power lighting, servo sequencing, and smart LED effects — all built on the ESP32‑C3 platform.
The project includes hardware schematics, PCB layout, Arduino‑based firmware, and 3D‑printable parts (housing, EDF afterburner adapters).

✨ Features
🔧 Input Capabilities

2× Fully‑configurable PWM inputs
For throttle, gear switch, flaps, or general‑purpose channel mapping.

⚡ Power System

Wide input voltage range (5–30 V DC)
Integrated 5 V BEC up to 3 A using an efficient mini step‑down converter.
Designed for reliability in EDF jets and high‑current scenarios.

🎮 Output Control

2× Fully‑configurable PWM outputs
Ideal for servo sequencing (e.g. landing gear + doors).

💡 Lighting Control

3× Configurable LED drivers
Supports:

Navigation lights
Blinking/beacon effects
Landing lights
Custom user‑defined light modes



🔥 High‑Power LED Switching

2× High‑power VBAT‑fed MOSFET switches
Suitable for:

7 W afterburner LEDs
High‑intensity strobes
Other high‑load accessories



📡 Connectivity

Wi‑Fi support (ESP32‑C3)
Planned feature: Web‑based configuration (not yet implemented).


🧩 Included in the Repository
/hardware
  ├── schematics
  ├── pcb_layout
  ├── fabrication files (Gerbers)
/firmware
  ├── Arduino IDE source code
  ├── configuration examples
/3d_models
  ├── enclosure (housing)
  ├── EDF afterburner adapters
/docs
  ├── user_guide.md
  ├── wiring_schemes.md  
README.md
LICENSE (GPL-3.0)


🛠️ Development & Firmware
Software
JetController firmware is written in Arduino-style C++ for the ESP32‑C3 and can be compiled and flashed using:

Arduino IDE
Board definition: ESP32C3 / ESP32C3 Dev Module
Flashing via USB‑C or serial adapter (depending on your ESP32C3 SuperMini variant)

Hardware Prototyping
The project is designed around accessible, low‑cost components to simplify community contributions.

🧾 Bill of Materials (Main Components)

























ComponentDescriptionESP32‑C3 SuperMiniMain MCU, Wi‑Fi capableMini 5 V Step‑Down DC/DCWide input voltage BEC (5–30V → 5V @ 3A)AO3401 (×5)P‑channel MOSFETs for high‑power switching and protectionAssorted discretesResistors, small‑signal MOSFETs, diodes, capacitors, connectors

🚀 Applications
JetController is suitable for:

EDF jets with functional afterburner lighting
Scale aircraft with navigation, beacon and landing lights
Electric retracts and gear‑door sequencing
Custom lighting effects
Multi‑channel RC input processing


🔮 Roadmap

 Web‑based configuration UI (ESP32‑C3 Wi‑Fi)
 Real‑time monitoring dashboard
 Extended LED effect engine
 Preconfigured aircraft profiles
 Step‑by‑step build and wiring tutorials
 Demo videos


🤝 Contributing
This project is licensed under GPL‑3.0, meaning all derived work must remain open and released under the same license.
Contributions are welcome across:

Hardware design
Firmware features
3D printable accessories
Documentation

Please open an issue or pull request if you'd like to get involved.

📜 License
This project is distributed under the GNU General Public License v3.0 (GPL‑3.0).
See the LICENSE file for full details.
