# 🌊 AquaSmatters – Smart Water Management System

**AquaSmatters** is an IoT-based smart water management system designed to monitor water quality, control water flow (input/output), and track usage in real-time. This system combines embedded hardware, a Flutter mobile app, and Firebase cloud services to provide an efficient and user-friendly water monitoring solution.

---

## 🚀 Features

* 📡 **Real-time monitoring** of water quality (via sensors)
* ⚙️ **Automated control** of water input/output valves
* 📈 **Usage tracking** for better resource management
* 📲 **Flutter mobile app** for real-time visualization and manual control
* ☁️ **Firebase Realtime Database** for live data sync and control
* 🔌 **ESP32 microcontroller** for sensor data collection and communication

---

## 🛠️ Technologies Used

* **Flutter** – Mobile application development
* **Firebase** – Cloud database and real-time sync
* **ESP32** – Microcontroller for IoT and sensor integration
* **C++ (Arduino)** – Firmware development
* **Dart** – Flutter backend logic

---

## 📷 Screenshots
![2](https://github.com/user-attachments/assets/f0fcdfc5-ce42-4843-94dd-5bb99ee47a09)


---

## 📚 How to Run

### 🔧 ESP32 Firmware

* Upload the firmware in `/firmware/` to your ESP32 using Arduino IDE.
* Configure Wi-Fi and Firebase credentials.

### 📱 Flutter App

```bash
flutter pub get
flutter run
```

Make sure your Firebase project is set up correctly and `google-services.json` is included.

---

## 📌 Status

🚧 **Project is under active development.** More features and improvements are on the way!

---
