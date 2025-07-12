
# 🤖 Smart Robot for Detection and Diffusion of Explosives and Hazardous Gas

A smart, semi-autonomous robotic system developed for bomb detection, landmine identification, hazardous gas sensing, and remote diffusion using advanced hardware integration and machine learning.

## 🔍 Project Overview

This project presents a multi-layered robotic solution designed to operate in hazardous environments such as military zones, industrial areas, or disaster sites. It integrates:

- **Bomb and landmine detection**
- **Toxic gas sensing**
- **Object recognition using deep learning**
- **GPS-based location tracking**
- **Live video surveillance (ESP32-CAM)**
- **Remote-controlled gripper for bomb diffusion**

> 🔒 **Goal:** Enhance safety by minimizing human involvement in bomb disposal and chemical hazard zones.

---

## ⚙️ Features

- 🧠 **CNN-based object detection** (guns, bombs, drones, etc.)
- 🌫️ **Toxic gas classification**: Safe / Warning / Dangerous using Python & Firebase
- 🧲 **Metal detection** for landmines
- 📍 **GPS module** for real-time threat location tracking
- 🎥 **Live surveillance feed** with ESP32-CAM
- 🦾 **Robotic gripper** for safe handling and disposal of explosives
- 📧 **Automated email alerts** with GPS & threat details
- 📊 **Real-time data visualization** (bar charts, pie charts, line graphs, heatmaps)

---

## 🛠 Hardware Components

- NodeMCU ESP8266
- ESP32-CAM module
- Arduino 433 MHz Transmitter & Receiver
- Gas Sensor (Simulated data)
- Metal Detector
- Servo motor + Gripper
- 1000–3000 RPM Motors
- GPS Module
- LM7805 Voltage Regulator
- 12V Battery Pack

---

## 🧠 Software Stack

- `Python` with `TensorFlow` / `Keras`
- `Google Colab` for ML training & deployment
- `Firebase Realtime Database` for gas data storage and alerts
- `Arduino IDE` for hardware programming
- `RF Communication` for remote operation

---

## 📊 Machine Learning Details

### Defense Object Detection (CNN)
- **Dataset**: 50,000+ custom-labeled images (drones, missiles, bombs, etc.)
- **Model**: CNN (ReLU, Dropout, MaxPooling, Sigmoid output)
- **Accuracy**: [Insert accuracy if available]
- **Deployment**: Google Colab + Email alert trigger on detection

### Gas Detection Classification
- **Gases Simulated**: CO, CO₂, CH₄, NH₃
- **Data Visualization**: Bar, Pie, Line, and Heatmaps using Matplotlib/Seaborn
- **Threshold Categories**: Safe, Warning, Dangerous

---

## 📸 Screenshots

> _Add your screenshots here if needed_

- Robot Top View
- Robot Side View
- Live ESP32-CAM Feed
- Gas Classification Graphs
- Detected Weapon via ML
- Email Alert Sample

---

## 🚀 Future Improvements

- Fully autonomous navigation with obstacle avoidance
- Integration with real gas sensors
- Upgrade to edge AI (e.g., Jetson Nano)
- Voice alert or mobile app integration
- Integration of Ground Penetrating Radar (GPR)

---

## 🧑‍💻 Authors

- Vaishnavi Devi J 
- Yogitha K  


> Built as part of our final year engineering project at Sathyabama Institute of Science and Technology.

---

## 📜 License

This project is for educational and research purposes only. You can fork or reuse with attribution.

---

## 🙏 Acknowledgements

Thanks to our mentors, faculty, and peer support that made this project possible. Special thanks to open-source communities and Firebase/Google Colab platforms.

