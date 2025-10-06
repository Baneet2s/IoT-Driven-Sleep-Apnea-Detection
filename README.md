# IoT-Driven Sleep Apnea Detection

**Project Status:** 🚧 In Progress (Mid-Semester) 🚧

[cite_start]This is the official repository for the Capstone Project `CPG-167` from the Thapar Institute of Engineering and Technology[cite: 10, 17]. [cite_start]Our project focuses on developing a non-invasive, affordable, and real-time sleep apnea detection system using a wearable IoT wristband and AI[cite: 35, 39].

[cite_start]The system aims to address the limitations of traditional Polysomnography (PSG), which is often costly, inconvenient, and inaccessible for continuous monitoring[cite: 33, 45, 566].

### ## Key Features

* [cite_start]**Multi-Sensor Data Fusion:** The wearable wristband integrates multiple biosensors to capture physiological signals, including **SpO₂**, **Heart Rate Variability (HRV)**, and **ECG**[cite: 461, 610].
* [cite_start]**AI-Powered Detection:** An AI/ML model analyzes the collected data in real-time to identify apnea events and assess their severity[cite: 37, 653].
* [cite_start]**Real-Time Alerts:** The system features a dual-alert mechanism, including a local buzzer on the device and notifications to a mobile app for users or caregivers[cite: 465, 616].
* [cite_start]**Cloud Integration:** Data is wirelessly transmitted via an ESP32 microcontroller to a cloud platform (Firebase) for storage, advanced analysis, and remote monitoring by healthcare providers[cite: 38, 1139].

### ## Technology Stack

| Component             | Technologies & Tools                                                                                                  |
| --------------------- | --------------------------------------------------------------------------------------------------------------------- |
| **Hardware** | [cite_start]ESP32 Microcontroller, MAX30102 (SpO₂/HR Sensor), MAX30003 (ECG Sensor)[cite: 462, 463, 1076].                               |
| **Firmware** | [cite_start]Arduino IDE / PlatformIO, C++[cite: 1096].                                                                                   |
| **AI / Machine Learning** | [cite_start]Python, PyTorch, TensorFlow/Keras, Scikit-learn, NumPy, Pandas[cite: 764, 765, 766, 875].                              |
| **Cloud & Backend** | [cite_start]Google Firebase (Realtime Database)[cite: 768, 1294].                                                                         |
| **Frontend** | [cite_start]Mobile App (React Native/Flutter planned), Web Dashboard (Streamlit/React planned)[cite: 140, 768, 1107]. |

### ## Project Status & Next Steps

[cite_start]We have successfully completed the hardware assembly and data acquisition pipeline[cite: 1301]. [cite_start]The wearable prototype can currently capture physiological signals (ECG, SpO₂) and transmit them successfully to our Firebase database in real-time[cite: 1302].

[cite_start]**Our immediate next step is to integrate the AI model with the Firebase data to perform apnea detection**[cite: 1303, 1305].

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
* [cite_start]Baneet Singh Sachdeva (102203180) [cite: 4]
* [cite_start]Armaan Saini (102217058) [cite: 5]
* [cite_start]Ramitdeep Kaur (102217071) [cite: 6]
* [cite_start]Babandeep Kaur (102203208) [cite: 7]
* [cite_start]Mehakdeep Kaur (102203242) [cite: 8]

**Under the Mentorship of:**
* [cite_start]Dr. Rohit Ahuja (Assistant Professor-II, CSED) [cite: 12, 26]
* [cite_start]Dr. Amit Mishra (Assistant Professor-III, ECED) [cite: 13, 28]

---
[cite_start]*This project is submitted in partial fulfillment of the requirements for the Bachelor of Engineering degree at the Computer Science and Engineering Department, TIET, Patiala.* [cite: 468]
