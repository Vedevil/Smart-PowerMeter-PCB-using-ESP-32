# Smart-PowerMeter-PCB-using-ESP-32
ESP32-based Smart Power Monitoring PCB with PZEM-004T, ACS712, and SCT013 sensors

⚡ Smart Power Monitor – PCB Design

The Smart Power Monitor PCB is an open-source hardware project built around the ESP32-WROOM-32 microcontroller, designed to measure and monitor voltage, current, power, and energy consumption in real time.

This PCB integrates support for three widely used energy measurement modules:

PZEM-004T – For accurate voltage, power, and energy measurement.

ACS712 – A Hall-effect current sensor for low-current measurements.

SCT013 – A non-invasive current clamp for higher AC load monitoring.

The design is tailored for IoT applications, where energy usage data can be logged, analyzed, and transmitted wirelessly. With the ESP32 at its core, this PCB is capable of connecting to MQTT brokers, cloud dashboards, or local monitoring systems, enabling use in smart homes, research labs, and industrial automation setups.

✨ Key Features

ESP32-WROOM-32 Controller – WiFi + Bluetooth connectivity out of the box.

Multi-Sensor Support – Compatible with PZEM-004T, ACS712, and SCT013.

Compact PCB Form Factor – Optimized 2-layer PCB for low-cost fabrication.

Open Source – All schematics, PCB files, and Gerbers are free to use.

IoT Ready – Designed for integration with MQTT dashboards, Home Assistant, or custom mobile apps.

Educational Value – Perfect for learning PCB design, IoT systems, and power electronics.

📐 Hardware Overview

Power Supply: 5V input via barrel jack or header.

Connectivity: UART/I²C headers for sensor interfacing.

Measurement Range:

Voltage: 80–260V AC (via PZEM-004T)

Current: 0–20A (via ACS712)

Current: up to 100A (via SCT013 clamp)

PCB Layers: 2 (optimized for easy manufacturing).

Software Support: Arduino IDE / PlatformIO with ESP32 libraries.

🛠️ Applications

Smart Home Energy Monitoring (track appliances, reduce consumption).

Industrial Load Monitoring (real-time analysis of machines and equipment).

IoT Dashboards (publish data to the cloud using MQTT/HTTP).

Academic & Research Projects (power electronics, embedded systems).

Low-cost alternative to commercial energy meters.

📦 Repository Contents

/hardware/ – KiCad schematic, PCB layout, Gerber files, BOM.

/docs/ – PCB renders, diagrams, and usage notes.

LICENSE – MIT License for free usage and modifications.

README.md – Documentation and project overview.

🔧 How to Get Started

Clone the repository:

git clone https://github.com/<your-username>/SmartPowerMonitor-PCB.git


Open the .sch and .kicad_pcb files in KiCad (v6+ recommended).

Export Gerbers using KiCad’s plot function.

Upload Gerbers (SmartPowerMonitor-Gerbers.zip) to PCB manufacturers (JLCPCB, PCBWay, etc.).

Order components from the BOM and assemble.

Flash ESP32 with your firmware to start monitoring energy.

📊 Example Workflow

Connect AC load to sensors (e.g., lamp, motor).

ESP32 reads measurements from PZEM-004T, ACS712, or SCT013.

Data is displayed via Serial Monitor or sent over WiFi.

MQTT broker or IoT dashboard logs the data.

User tracks real-time and historical energy consumption.

📜 License

This project is licensed under the MIT License – you are free to use, modify, and distribute, provided proper credit is given.
Schematic 
<img width="1186" height="830" alt="image" src="https://github.com/user-attachments/assets/70010fce-c240-49b1-ad7e-5050a57b61aa" />


Layout
<img width="1572" height="865" alt="image" src="https://github.com/user-attachments/assets/4bcdd30a-468d-44be-a487-168fc3bb37f6" />


3D View
<img width="1007" height="652" alt="image" src="https://github.com/user-attachments/assets/7c255b91-24f7-4eef-b09e-f9ba80b514d7" />

