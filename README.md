# 🔐 Smart Pendant for Women’s Safety using Machine Learning

A wearable IoT-based safety device designed to protect women in real-time through AI-driven threat detection, automatic alerts, live tracking, and evidence collection.

> 📍 Developed as part of ASEP1 (Applied Science & Engineering Project - Semester 1)  
> 🏫 Vishwakarma Institute of Technology, Pune  
> 👥 Team Members: Vedant Patil, Samarth Patil, Tejas Patil, Reyan Patil, Tirtha Patil, Utkarsh Patil  
> 👩‍🏫 Guided by: Prof. Supriya Telsang

---

## 🧠 Project Overview

The **Smart Pendant** integrates **IoT** and **Machine Learning** to create a reliable, wearable safety device. It can automatically detect threats like weapons using a camera and ML model, trigger alerts via GSM, send GPS location, and store visual evidence. A mobile app allows live monitoring and also alerts users when they enter danger-prone zones using predictive models based on crime data.

---

## 💡 Features

- 🚨 **Real-time Threat Detection** using deep learning and ESP32-CAM
- 🗺️ **Live GPS Tracking** and automatic alerting via GSM
- 🎥 **Visual Evidence Collection** stored on a micro SD card
- 📱 **Android App Integration** for monitoring, alert management, and notifications
- 🔥 **Danger Zone Prediction** using regression models on crime data (heatmap display)
- ❌ **False Alarm Reduction** via a weapon classification model
- 🔐 **Offline Capability** (SMS-based alert system for low-internet areas)

---

## ⚙️ Technologies Used

| Component | Purpose |
|----------|---------|
| ESP32-CAM | Captures live video for threat detection |
| GPS Module | Sends real-time location |
| GSM Module | Sends emergency alerts via SMS |
| Micro SD Card | Stores video/image evidence |
| Python | ML model training and evaluation |
| Android (Java/Kotlin) | Mobile app development |
| Deep Learning (CNN) | Object detection (weapon/non-weapon classification) |
| Regression (crime data) | Danger zone prediction & heatmap generation |


