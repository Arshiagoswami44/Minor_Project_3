# Smart Energy Monitering and Management System

📌 Project Overview
This project is an IoT-based Energy Monitoring System designed to monitor real-time electrical parameters such as voltage, current, power, and energy consumption of household appliances. The system sends live data to a mobile dashboard using the Blynk IoT platform.
The objective of this project is to enable smart energy monitoring and promote efficient electricity usage.

🛠️ Components Used
NodeMCU ESP8266
PZEM-004T Energy Monitoring Module
CT Clamp (Current Transformer)
Bulb / Fan (Load for testing)
Connecting Wires
Breadboard
Wi-Fi Network

⚙️ Technologies Used
Arduino IDE (Programming Environment)
C++ (Arduino Programming Language)
Blynk IoT Cloud Platform
Embedded Systems
IoT Communication

🔄 System Architecture
Bulb / Fan
↓
PZEM-004T Sensor
↓
NodeMCU ESP8266
↓
Wi-Fi
↓
Blynk IoT Dashboard

📊 Features
Real-time voltage monitoring
Real-time current measurement
Power calculation (Watt)
Energy consumption tracking (kWh)
Remote monitoring via mobile dashboard
Scalable for multiple appliances

🧠 Working Principle
The PZEM-004T sensor measures voltage, current, power, and energy from the connected load.
NodeMCU reads the sensor data using serial communication.
The microcontroller connects to Wi-Fi.
Data is transmitted to the Blynk IoT cloud.
The dashboard displays live energy readings.

🚀 Setup Instructions
Install Arduino IDE.
Install ESP8266 board package.
Install required libraries:
Blynk
PZEM004Tv30
Update the following in the code:
BLYNK_TEMPLATE_ID
BLYNK_TEMPLATE_NAME
BLYNK_AUTH_TOKEN
Wi-Fi SSID and Password
Upload code to NodeMCU.
Connect PZEM sensor and load.
Monitor readings in Blynk IoT dashboard.

📈 Current Project Status
Code development completed
Dashboard configuration initiated
Sensor integration in progress
Final testing pending

🔮 Future Enhancements
Threshold-based alert system
Automatic power cut-off using relay
Data logging and analysis
Multi-device monitoring

👩‍💻 Author
Arshia Goswami
B.Tech – Minor Project
K.R. Mangalam University
