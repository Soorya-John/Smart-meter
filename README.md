⚡ Smart Electricity Meter
A feature-rich smart electricity meter designed for real-time power monitoring, load control, and remote data logging. Built using affordable microcontrollers and sensors, this project is ideal for energy-saving, educational, and IoT applications.

🛠️ Features
Real-time Voltage & Current Monitoring

Power & Energy Consumption Tracking

Load Control (Relay Switch)

Overload Protection

OLED Display for On-Device Stats

Wi-Fi Connectivity for Remote Monitoring

Data Logging to Cloud (e.g., Blynk/ThingSpeak/Firebase)

OTA Firmware Updates

Compact Custom PCB Design

Battery Backup (optional)

🧰 Hardware Components
Component	Description
⚙️ Microcontroller	ESP8266 / ESP32 / Arduino
🔌 Voltage Sensor	ZMPT101B
🔄 Current Sensor	SCT-013 (Non-invasive CT sensor)
💡 Display	SSD1306 OLED 128x64 (I2C)
🔋 Power Supply Module	AMS1117 / HLK-PM01
⚠️ Relay Module	For load control (AC appliances)
🔔 Buzzer (optional)	Audible alerts
🔘 Push Buttons	Manual control / configuration
📶 Wi-Fi Antenna	Onboard or external
🔌 Terminal Blocks	For AC connections

📐 PCB Design Notes
Compact layout to fit into standard wall-mount enclosures.

Isolation between AC and DC circuits using optocouplers and proper creepage distances.

Mounting holes for enclosure integration.

Screw terminals for AC input, current transformer, and relay output.

🔧 Setup Instructions
Connect Sensors:

ZMPT101B → ADC for voltage

SCT-013 → ADC with burden resistor for current

Calibrate Sensors:

Use known loads to calibrate voltage and current readings.

Flash Firmware:

Use Arduino IDE/PlatformIO.

Configure Wi-Fi and cloud credentials in config.h.

Power Up & Monitor:

Observe readings on OLED.

Use mobile/web dashboard for remote monitoring.

📡 Cloud Integration
Blynk / ThingSpeak / Firebase / MQTT supported

Real-time dashboard with graphs, alerts, and consumption history

🔐 Safety Tips
Ensure proper isolation between high-voltage and low-voltage circuits.

Use fuses and varistors for surge protection.

Never handle live wires while working on the circuit.

🚀 Future Improvements
Mobile app with usage analytics

Bill estimation based on local tariff

Multi-channel monitoring (per-room or per-device)

Integration with home automation (e.g., Home Assistant)

📸 Project Images
<img width="1075" height="749" alt="Screenshot 2025-07-29 211955" src="https://github.com/user-attachments/assets/a9fef4b9-25e7-4874-b241-2a0243bd6416" />
<img width="893" height="690" alt="Screenshot 2025-07-29 212012" src="https://github.com/user-attachments/assets/9d1999d9-f484-46a6-97f6-524233cd30a8" />


👨‍💻 Author
Soorya John
Electronics enthusiast, IoT maker, and embedded systems developer.


📜 License
This project is open-source and available under the MIT License.
