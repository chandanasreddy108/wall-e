# 🌱 E-FARM – Edge AI Based Smart Agriculture Crop Recommendation System

<p align="center">
  <img src="https://img.shields.io/badge/Platform-ESP32-blue?style=for-the-badge">
  <img src="https://img.shields.io/badge/AI-Edge%20AI-green?style=for-the-badge">
  <img src="https://img.shields.io/badge/IoT-Smart%20Agriculture-orange?style=for-the-badge">
  <img src="https://img.shields.io/badge/License-MIT-red?style=for-the-badge">
</p>

<p align="center">
  <strong>An intelligent Edge AI-powered smart agriculture system that analyzes real-time environmental conditions and recommends the most suitable crops for cultivation while enabling remote monitoring and sustainable farming practices.</strong>
</p>

---

# 📖 Overview

**E-FARM** is an **Edge AI-based Smart Agriculture Crop Recommendation System** designed to assist farmers in making data-driven agricultural decisions. The system continuously monitors important environmental parameters such as soil moisture, temperature, humidity, rainfall, and light intensity using IoT sensors.

Unlike cloud-dependent systems, **E-FARM performs crop recommendation directly on the edge device**, reducing internet dependency, minimizing latency, and ensuring reliable operation even in remote agricultural areas.

The collected sensor data is processed using machine learning algorithms deployed on an embedded controller, allowing instant crop recommendations and intelligent farming decisions.

---

# 🎯 Objectives

* Develop an intelligent crop recommendation system.
* Utilize Edge AI for real-time decision making.
* Reduce dependency on cloud computing.
* Improve crop productivity through data-driven agriculture.
* Optimize water usage and irrigation.
* Assist farmers in selecting suitable crops based on current environmental conditions.
* Promote sustainable and precision farming.

---

# ✨ Features

* 🌱 Edge AI Crop Recommendation
* 🌡 Real-time Temperature Monitoring
* 💧 Soil Moisture Detection
* 🌦 Humidity Monitoring
* ☀ Light Intensity Measurement
* 🌧 Rain Detection
* 📊 Live Sensor Dashboard
* 📶 IoT Connectivity
* ⚡ Low Power Operation
* 📱 Mobile/Web Monitoring
* 🔔 Smart Alerts & Notifications
* 📈 Historical Data Logging
* 🌾 Precision Farming Support
* 🌍 Works in Remote Areas
* 🔒 Secure Local Processing

---

# 🧠 Edge AI Workflow

```text
Environmental Sensors
        │
        ▼
Data Acquisition
        │
        ▼
Feature Extraction
        │
        ▼
Edge AI Model
        │
        ▼
Crop Recommendation
        │
        ▼
Farmer Dashboard
```

---

# 🏗 System Architecture

```text
                Environmental Sensors
      ┌───────────────────────────────────┐
      │                                   │
      │ Temperature                       │
      │ Humidity                          │
      │ Soil Moisture                     │
      │ Rain Sensor                       │
      │ Light Sensor                      │
      └───────────────────────────────────┘
                    │
                    ▼
              ESP32 / Edge Controller
                    │
        ┌───────────┴────────────┐
        │                        │
        ▼                        ▼
   Edge AI Model           IoT Communication
        │                        │
        └───────────┬────────────┘
                    ▼
           Crop Recommendation
                    │
                    ▼
         Mobile App / Web Dashboard
```

---

# 🛠 Hardware Components

| Component                     | Purpose                   |
| ----------------------------- | ------------------------- |
| ESP32                         | Main Edge AI Controller   |
| Soil Moisture Sensor          | Soil water measurement    |
| DHT22                         | Temperature & Humidity    |
| Rain Sensor                   | Rain detection            |
| LDR / BH1750                  | Light intensity           |
| OLED Display                  | Local information display |
| Relay Module                  | Irrigation control        |
| Water Pump                    | Automated irrigation      |
| Wi-Fi Module (ESP32 Built-in) | IoT communication         |
| Power Supply                  | System power              |

---

# 💻 Software Used

* Arduino IDE
* Edge Impulse
* TensorFlow Lite for Microcontrollers
* Python (Dataset Training)
* Firebase / MQTT (Optional)
* ESP32 Libraries
* Git & GitHub

---

# 🤖 Machine Learning Model

The Edge AI model is trained using agricultural datasets containing:

* Temperature
* Humidity
* Soil Moisture
* Rainfall
* Soil Conditions
* Light Intensity

The trained model is converted into an embedded format and deployed directly onto the ESP32, enabling offline crop recommendation with low latency.

---

# 🌾 Example Crop Recommendations

| Environmental Condition              | Recommended Crop |
| ------------------------------------ | ---------------- |
| High Moisture + Moderate Temperature | Rice             |
| Low Moisture + High Temperature      | Millet           |
| Moderate Moisture                    | Maize            |
| Cool Climate                         | Wheat            |
| Warm & Humid                         | Sugarcane        |
| Dry Climate                          | Groundnut        |

---

# 📊 Data Flow

```text
Sensors
   │
   ▼
ESP32
   │
   ▼
Edge AI Prediction
   │
   ▼
Crop Recommendation
   │
   ▼
Display / Mobile Dashboard
```

---

# 📁 Project Structure

```text
E-FARM/
│
├── Arduino_Code/
├── Edge_AI_Model/
├── Dataset/
├── Mobile_App/
├── Images/
├── Documentation/
├── Circuit_Diagram/
├── Libraries/
├── README.md
└── LICENSE
```

---

# 🚀 Future Enhancements

* AI-based disease detection
* Computer vision for crop health monitoring
* Drone integration
* Satellite weather prediction
* Fertilizer recommendation
* Automatic irrigation scheduling
* Multi-language farmer assistant
* Voice-enabled AI assistant
* Solar-powered deployment
* LoRa-based long-range communication

---

# 📈 Applications

* Smart Farming
* Precision Agriculture
* Crop Planning
* Greenhouses
* Agricultural Research
* Educational Projects
* Sustainable Farming
* Rural Farming Automation

---

# 🎓 Learning Outcomes

This project demonstrates practical implementation of:

* Edge AI
* TinyML
* Embedded Systems
* IoT
* Smart Agriculture
* Machine Learning Deployment
* Sensor Fusion
* Real-Time Decision Making
* ESP32 Programming
* Precision Farming Technologies

---

# 📷 Project Images

```
Add project images here

/images/System.jpg

/images/Prototype.jpg

/images/Circuit.png

/images/Working.jpg
```

---

# 📹 Demonstration

```
Coming Soon
```

---

# 📜 License

This project is licensed under the **MIT License**.

---

# 👨‍💻 Author

**Koushik M**

**Chandana S**

Mechatronics Engineering Student

Robotics | Embedded Systems | Edge AI | IoT | Automation

---

# 🤝 Contributing

Contributions are welcome!

1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Push to your branch
5. Open a Pull Request

---

# ⭐ Support

If you found this project helpful, consider giving it a **⭐ Star** on GitHub.

It motivates further development and helps others discover the project.

---

<p align="center">
  <strong>🌱 Smart Farming Begins with Intelligent Decisions 🌱</strong>
</p>
