# Smart In-Car Health Guardian (SIH Prototype)

![Platform](https://img.shields.io/badge/Platform-Raspberry%20Pi%204-red?style=for-the-badge&logo=raspberry-pi)
![ML](https://img.shields.io/badge/Machine%20Learning-LSTM%20%7C%20Decision%20Trees-blue?style=for-the-badge)
![Hardware](https://img.shields.io/badge/Sensor-TCRT1000%20IR-orange?style=for-the-badge)
![Domain](https://img.shields.io/badge/Domain-Automotive%20HealthTech-green?style=for-the-badge)

## 📋 Project Overview
The **Smart In-Car Health Guardian** is an automated emergency response system and IoT edge device designed to monitor driver vitals and predict medical emergencies in real-time. By continuously tracking heart rate via steering wheel sensors, the system acts as a silent guardian: if incapacitation occurs, it bypasses human error and initiates a GPS-integrated emergency dispatch to the nearest hospital.

## ⚙️ Core Architecture & Hardware
* **Edge Computing:** Powered by a Raspberry Pi 4 to process real-time biometric data locally with low implementation challenges.
* **Sensor Integration:** Utilizes TCRT1000 IR optical sensors embedded directly into the steering wheel for continuous pulse monitoring.
* **Material Engineering:** The sensors are mounted using **Medical Grade Silicone**, an optimal solution that provides outstanding IR transparency, biocompatibility, and necessary grip comfort while withstanding dynamic cabin temperatures.

## 🧠 Machine Learning & Dispatch Algorithms
To balance accuracy and avoid false alarms, the system utilizes a robust predictive pipeline:
* **Anomaly Detection:** Employs an Isolation Forest model trained on normal driving data. This is coupled with an LSTM Autoencoder and Decision Tree models to confidently confirm genuine cardiac crises.
* **Intelligent Routing:** Integrates **k-d tree algorithms** to instantly locate the nearest suitable medical facility and dispatch an ambulance.
* **Multi-Channel Alerts:** Automatically transmits encrypted data packets and GPS coordinates to hospitals, patrolling vehicles, and family members.

## 🚀 Future Scope & Enhancements
The next iteration of the vehicle architecture will include expanded health monitoring:
* **Personalized Health Dashboard:** Integrating personal health profiles to provide targeted, full-screen medication reminders (e.g., "Time to take your Blood Pressure Medicine") via the infotainment system.
* **Thermal Monitoring:** Strategic placement of temperature sensors in the seat/visor to periodically check for fever or sudden temperature drops without causing driver distraction.
* **Fatigue & Stress Detection:** Advanced steering wheel pressure sensors to monitor grip strength. A weakening grip indicates drowsiness, while a sudden complete loss of grip instantly triggers the emergency module.
