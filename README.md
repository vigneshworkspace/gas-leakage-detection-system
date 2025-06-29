# gas-leakage-detection-system
# 🔥 Gas Leakage Detection System (GLDS)

An IoT-based real-time gas leakage detection and alerting system designed to detect harmful gases like LPG, methane, and carbon monoxide. This project ensures safety by monitoring the environment and sending immediate alerts when gas concentrations exceed safe limits.it makes a call to your mobile immediatly if you save it as gas alert it will even more convinient.and this for 150 calls doesn't incurr any charges .

---

## 🚀 Features
- Real-time gas concentration monitoring
- Instant alerts via buzzer and LED
- IoT-based notifications (via Blynk/Twilio)
- Live data dashboard
- Compact and low-power design

---

## 🧰 Tech Stack
- **Hardware:** MQ-2 / MQ-7 Gas Sensor, Arduino Uno / ESP32, Buzzer, LEDs
- **Connectivity:** ESP8266 WiFi Module / ESP32 WiFi
- **Software:** Arduino IDE, Blynk / Thingspeak / Firebase
- **Optional:** Python (Raspberry Pi), Flask backend, Mobile App

---

## 🛠️ How It Works
1. Gas sensors continuously monitor the surrounding air.
2. When gas concentration exceeds a safe threshold:
   - Buzzer and LEDs are triggered.
   - A message/alert is sent via an IoT service.
3. All sensor data can be logged and visualized on a real-time dashboard.

# ⚠️ Anomaly Detection using TensorFlow Lite

This project demonstrates how to build and deploy a lightweight anomaly detection model using TensorFlow Lite (TFLite). It is ideal for use cases like gas leak detection, sensor failure monitoring, or any edge-based anomaly classification.

---

## 🚀 Project Overview

- 📊 **Model Type:** Autoencoder (Unsupervised)
- 🧠 **Purpose:** Detect anomalies in sensor data ( gas sensor values)
- 📱 **Deployment:** TFLite for edge devices (esp32)

---

## 🧠 How It Works

1. Train an **Autoencoder** on normal sensor readings.
2. Measure the **reconstruction error** between input and output.
3. If error > threshold → mark as anomaly.
4. Convert the trained model to `.tflite` for lightweight inference.

---

## 🧰 Tech Stack

- TensorFlow / Keras
- TensorFlow Lite Converter
- Python (for training & testing)
- Edge Deployment 


[video of the project](https://drive.google.com/file/d/1f0yUhSE9oCd6fHXcuvmqv9kWP_6IGKvl/view?usp=sharing)
