# -AI-SMART-SURVEILLANCE-SYSTEM-
AI Smart Surveillance System Using ESP32-CAM

📌 Overview

The AI Smart Surveillance System is an IoT-based security project built using an ESP32-CAM and a PIR Motion Sensor. The system continuously monitors an area for human motion. When motion is detected, the ESP32-CAM captures an image, activates a buzzer and LED, and can send the captured image to a mobile device over Wi-Fi. This project provides a simple, affordable, and smart surveillance solution for homes, offices, and small businesses.

---

✨ Features

- Motion detection using PIR sensor
- Automatic image capture with ESP32-CAM
- LED and buzzer alert
- Wi-Fi connectivity
- Remote image notification
- Low-cost IoT security solution
- Easy to build and expand

---

🛠 Components Used

- ESP32-CAM Module
- HC-SR501 PIR Motion Sensor
- Active Buzzer
- 5mm LED
- 220Ω Resistor
- FTDI USB-to-Serial Programmer
- Breadboard
- Jumper Wires
- USB Cable
- 5V Power Supply

---

🔌 Pin Connections

ESP32-CAM| Component
5V| PIR VCC
GND| PIR GND, LED (-), Buzzer (-)
GPIO13| PIR OUT
GPIO2| LED (+) through 220Ω resistor
GPIO12| Active Buzzer (+)

---

⚙️ Working Principle

1. The ESP32-CAM starts and connects to Wi-Fi.
2. The PIR sensor continuously monitors for motion.
3. When motion is detected, the ESP32-CAM captures an image.
4. The LED and buzzer turn on to indicate an alert.
5. The captured image can be sent to a mobile phone through Wi-Fi.
6. The system returns to monitoring mode after the alert.

---

▶️ How to Run

1. Install Arduino IDE.
2. Install the ESP32 board package.
3. Connect the ESP32-CAM using an FTDI programmer.
4. Open "AI_Surveillance.ino".
5. Enter your Wi-Fi credentials.
6. Upload the code.
7. Reset the ESP32-CAM.
8. Power the circuit and test motion detection.

---

📸 Applications

- Home Security
- Office Surveillance
- Warehouse Monitoring
- Smart Room Monitoring
- Laboratory Security

---

🚀 Future Improvements

- Face Recognition
- Live Video Streaming
- Cloud Storage
- Mobile Application
- Two-Way Audio
- Multiple Camera Support

---

📊 Project Duration

41 Hours 32 Minutes 55 Seconds

---

👨‍💻 Author

Prince Kumar

Built as a hardware project using ESP32-CAM, IoT, and Embedded Systems for a smart surveillance solution.