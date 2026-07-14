# Industrial-Safety-Monitoring-System
🚨 Industrial Safety Monitoring System

📌 Overview

The "IoT-Based Industrial Safety Monitoring System" is designed to enhance workplace safety by continuously monitoring industrial environments for hazardous gases and fire incidents. Using an ESP32 microcontroller and IoT technology, the system collects sensor data and uploads it to the "ThingSpeak Cloud Platform" for real-time monitoring.
Whenever a hazardous gas leak or fire is detected, the system immediately activates a "buzzer alarm" to alert personnel, helping prevent accidents and improve industrial safety.

🎯 Objectives

* Detect hazardous gas leakage in industrial environments.
* Detect fire incidents in real time.
* Monitor temperature and humidity conditions.
* Provide remote monitoring through the ThingSpeak cloud dashboard.
* Generate instant alerts using a buzzer during emergency situations.
* Improve workplace safety and reduce risks.

⚙️ Components Used

* ESP32 Development Board
* MQ-2 Gas Sensor
* Flame Sensor
* DHT11 Temperature & Humidity Sensor
* Buzzer
* Jumper Wires
* Breadboard

🛠️ Technologies Used

* Embedded C
* Arduino IDE
* ESP32
* Internet of Things (IoT)
* ThingSpeak Cloud Platform
* Wi-Fi Communication

🔄 Working Principle

The system continuously monitors environmental conditions using multiple sensors. The MQ-2 sensor detects hazardous gases such as LPG, methane, and smoke, while the flame sensor identifies the presence of fire. The DHT11 sensor measures temperature and humidity.
The ESP32 processes all sensor readings and sends the data to the ThingSpeak cloud dashboard through Wi-Fi. If a hazardous gas leak or fire is detected, the buzzer is activated immediately to provide an audible warning. The sensor data and alert status are also updated on the cloud dashboard for remote monitoring.

 📊 Features

* Real-time industrial safety monitoring
* Hazardous gas leakage detection
* Fire detection and alert system
* Temperature and humidity monitoring
* Cloud-based monitoring using ThingSpeak
* Instant buzzer alerts during emergencies
* Wireless data transmission through Wi-Fi
* Low-cost and efficient safety solution

📱 ThingSpeak Dashboard

The ThingSpeak dashboard provides real-time visualization of:
* Temperature
* Humidity
* Gas Sensor Readings
* Fire Detection Status
* Alert Conditions

This enables users to monitor industrial conditions remotely from anywhere with internet access.

 > Setup

1. Install Arduino IDE and ESP32 board support.
2. Install the required libraries.
3. Configure Wi-Fi credentials and ThingSpeak API details in the code.
4. Upload the code to the ESP32.
5. Connect the hardware components and power the system.
6. Monitor sensor data on the ThingSpeak dashboard.

 📈 Future Enhancements

* SMS and Email Notifications
* Mobile Application Integration
* AI-Based Predictive Safety Analysis
* Automatic Fire Suppression System
* Additional Industrial Safety Sensors
* Advanced Data Analytics

🏭 Applications
* Industrial Plants
* Chemical Industries
* Oil & Gas Facilities
* Warehouses
* Manufacturing Units
* Smart Buildings
* Laboratories

 🎥 Project Demonstration

Project Video:https://drive.google.com/file/d/1cLzyY_P19VaOauybJQA6E0IrN_5VpQLS/view?usp=sharing

👩‍💻 Author
Lavanya Choudhary
B.Tech Industrial IoT
St. Vincent Pallotti College of Engineering & Technology (SVPCET), Nagpur

 📜 License
This project is developed for educational and learning purposes. 
