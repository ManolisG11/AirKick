# 🚀 Airkick – WiFi Deauther for Arduino Nano ESP32

> _"Kick devices off WiFi networks with style (and permission)."_  
> ⚠️ **For educational and authorized testing only!**

![AirKick Logo](https://img.shields.io/badge/built%20with-ESP32-blue?style=flat-square)
![MIT License](https://img.shields.io/github/license/manolisg11/AirKick?style=flat-square)

---

## 🌐 What is Airkick?

**Airkick** is a sleek, ESP32-based WiFi **deauthentication attack tool** built specifically for the **Arduino Nano ESP32**. It allows users to scan for nearby WiFi networks and selectively start or stop deauth attacks via a modern web interface. Designed for **educational use**, Airkick demonstrates wireless vulnerabilities in a controlled, authorized environment.

---

## ✨ Features

✅ **WiFi Access Point Interface**  
Starts an AP called `AirKick` with password `airkick123`.

✅ **Modern Web Dashboard**  
Navigate to `192.168.4.1` to:
- 🌐 Scan nearby WiFi networks
- 🎯 Select a target from a slick table view
- 💥 Start/Stop Deauthentication attacks
- ⚠️ View current status (ACTIVE/INACTIVE)

✅ **Real-Time Network Scanner**  
Instantly fetch nearby SSIDs, BSSIDs, and channels.

✅ **Precise Targeting**  
Select any network with one click and Airkick handles the BSSID/channel setup.

✅ **Low-level WiFi Frame Injection**  
Uses `esp_wifi_80211_tx` to send deauth frames directly.

✅ **Responsive Web UI**  
Beautiful HTML + CSS frontend served from ESP32’s internal web server.

✅ **Built for Nano ESP32**  
Lightweight, fast, and tailored for the Arduino Nano ESP32 footprint.

---

## 📷 Preview

> Interface loads automatically on device connection to `AirKick` AP

![screenshot](https://dummyimage.com/800x400/cccccc/000000&text=Airkick+Web+UI+Preview)

---

## 🛠️ Setup Instructions

### ✅ Requirements

- Arduino IDE 2.x ✅
- Board: **Arduino Nano ESP32**
- Libraries:
  - `WiFi.h`
  - `WebServer.h`
  - `esp_wifi.h`

### 📦 Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/manolisg11/AirKick.git
