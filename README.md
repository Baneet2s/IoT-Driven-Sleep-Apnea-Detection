# IoT-Driven Sleep Apnea Detection

**Project Status:** 🚧 In Progress (Mid-Semester) 🚧

This is the official repository for the Capstone Project `CPG-167` from the Thapar Institute of Engineering and Technology. Our project focuses on developing a non-invasive, affordable, and real-time sleep apnea detection system using a wearable IoT wristband and AI.

The system aims to address the limitations of traditional Polysomnography (PSG), which is often costly, inconvenient, and inaccessible for continuous monitoring.

### ## Key Features

* **Multi-Sensor Data Fusion:** The wearable wristband integrates multiple biosensors to capture physiological signals, including **SpO₂**, **Heart Rate Variability (HRV)**, and **ECG**.
* **AI-Powered Detection:** An AI/ML model analyzes the collected data in real-time to identify apnea events and assess their severity.
* **Real-Time Alerts:** The system features a dual-alert mechanism, including a local buzzer on the device and notifications to a mobile app for users or caregivers.
* **Cloud Integration:** Data is wirelessly transmitted via an ESP32 microcontroller to a cloud platform (Firebase) for storage, advanced analysis, and remote monitoring by healthcare providers.

### ## Technology Stack

| Component | Technologies & Tools |
|---|---|
| **Hardware** | ESP32 Microcontroller, MAX30102 (SpO₂/HR Sensor), MAX30003 (ECG Sensor). |
| **Firmware** | Arduino IDE / PlatformIO, C++. |
| **AI / Machine Learning** | Python, PyTorch, TensorFlow/Keras, Scikit-learn, NumPy, Pandas. |
| **Cloud & Backend** | Google Firebase (Realtime Database). |
| **Frontend** | Mobile App (React Native/Flutter planned), Web Dashboard (Streamlit/React planned). |

### ## Project Status & Next Steps

We have successfully completed the hardware assembly and data acquisition pipeline. The wearable prototype can currently capture physiological signals (ECG, SpO₂) and transmit them successfully to our Firebase database in real-time.

**Our immediate next step is to integrate the AI model with the Firebase data to perform apnea detection**.

### ## Repository Structure

```
├── ai_model/              # Python scripts, notebooks, and data for the ML model
├── app/                   # Code for the frontend mobile/web application
├── docs/                  # All project documentation (proposal, reports, presentation)
├── firmware/              # C++ code for the ESP32 microcontroller
├── hardware/              # Schematics, Bill of Materials (BOM), and hardware info
├── .gitignore             # Specifies files/directories to ignore in git
├── LICENSE                # Project license file
└── README.md              # This file
```

### ## Team Members & Mentors

**Team (CPG-167):**
* Baneet Singh Sachdeva (102203180)
* Armaan Saini (102217058)
* Ramitdeep Kaur (102217071)
* Babandeep Kaur (102203208)
* Mehakdeep Kaur (102203242)

**Under the Mentorship of:**
* Dr. Rohit Ahuja (Assistant Professor-II, CSED)
* Dr. Amit Mishra (Assistant Professor-III, ECED)

---
*This project is submitted in partial fulfillment of the requirements for the Bachelor of Engineering degree at the Computer Science and Engineering Department, TIET, Patiala.*
