# 🩺 HEALTH-BAND — Smart Health Monitoring System

<p align="center">
  <img src="https://img.shields.io/badge/Platform-Web%20%7C%20Android-blue?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Status-Active-brightgreen?style=for-the-badge" />
  <img src="https://img.shields.io/badge/License-MIT-orange?style=for-the-badge" />
</p>

> A comprehensive smart health monitoring platform that bridges patients and doctors through real-time vitals tracking, AI-powered health insights, fetal monitoring, blockchain-secured records, and an intelligent health assistant.

---

## 📋 Table of Contents

- [Overview](#-overview)
- [Features](#-features)
- [Tech Stack](#-tech-stack)
- [Project Structure](#-project-structure)
- [Getting Started](#-getting-started)
- [Login Credentials](#-login-credentials)
- [Screenshots](#-screenshots)
- [Android App](#-android-app)
- [Team](#-team)

---

## 🌟 Overview

**HEALTH-BAND** is a full-stack health monitoring web application and Android app designed for both **patients** and **doctors**. It provides real-time health tracking, AI-generated personalized health plans, fetal monitoring dashboards, blockchain-secured medical records, appointment scheduling, and an interactive AI health chatbot.

---

## ✨ Features

### 👤 Patient Dashboard
- 📊 **Real-Time Vitals** — Live tracking of Heart Rate, SpO₂, Blood Pressure, Temperature, and Steps
- 🤖 **AI Health Plan** — Personalized diet, exercise, and wellness recommendations powered by AI
- 🗓️ **Appointment Booking** — Schedule and manage doctor appointments
- 🏆 **Leaderboard** — Gamified health goals with rankings
- 💬 **Health Bot** — Conversational AI assistant for health queries
- ⛓️ **Blockchain Records** — Immutable, secure medical record storage
- 🔔 **Reminders** — Medication and health activity reminders
- 📶 **Connectivity Status** — Wearable device connection monitoring

### 🩻 Doctor Dashboard
- 👥 **Patient Management** — View and manage all assigned patients
- 📋 **Patient Health Reports** — Detailed vitals history per patient
- 🔁 **Real-Time Monitoring** — Live vitals feed from connected health bands

### 🤰 Fetal Monitoring
- 📈 **Real-Time Charts** — Fetal Heart Rate, SpO₂, and Movement Intensity
- 🧑‍⚕️ **Maternal Vitals** — Simultaneous mother vitals tracking
- 🔄 **Head Position Detection** — Automated fetal position tracking

### 🔐 Security & Data
- **Blockchain-secured** medical records
- Firebase-backed user authentication
- Role-based access control (Doctor / Patient)

---

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| Frontend | HTML5, CSS3, JavaScript (Vanilla) |
| Charts | Chart.js |
| Icons | Boxicons |
| Backend | Python (Flask) |
| Database | SQLite (`data.db`) |
| Auth / Cloud | Firebase |
| Android | WebView-based Android App (Java) |
| Deployment | Vercel |

---

## 📁 Project Structure

```
HEALTH-BAND/
├── index.html               # Login page (Patient / Doctor)
├── TI_patient.html          # Patient dashboard
├── TI_doctor.html           # Doctor dashboard
├── app.html                 # Main health app interface
├── fetal_monitoring.html    # Real-time fetal monitoring dashboard
├── ai_plan.html             # AI-generated personalized health plan
├── appointment.html         # Appointment booking system
├── leaderboard.html         # Health leaderboard
├── bot.html                 # AI health chatbot
├── blockchain.html          # Blockchain medical records
├── reminders.html           # Health reminders
├── health_status.html       # Health status page
├── connectivity.html        # Wearable connectivity status
├── wiring_diagram.html      # Hardware wiring diagram
├── patient_list.html        # Doctor's patient list
├── login.html               # Alternate login page
├── app.py                   # Python Flask backend
├── data.db                  # SQLite database
├── vercel.json              # Vercel deployment config
├── simulated_health_data.csv# Sample health dataset
├── Armstrong_Health.apk     # Android APK (v1)
├── Armstrong_Health_Updated.apk  # Android APK (v2 - Latest)
└── armstrong-android/       # Android Studio project source
```

---

## 🚀 Getting Started

### Run Locally (Web)

1. **Clone the repository**
   ```bash
   git clone https://github.com/lohithashwas/HEALTH-BAND.git
   cd HEALTH-BAND
   ```

2. **Open in browser**
   - Simply open `index.html` in any modern browser, **OR**

3. **Run with Python backend** (for bot/data features)
   ```bash
   pip install flask
   python app.py
   ```
   Then visit `http://localhost:5000`

### Deploy on Vercel
The project includes a `vercel.json` config. Deploy with:
```bash
npm install -g vercel
vercel --prod
```

---

## 🔑 Login Credentials

| Role | Username | Password |
|------|----------|----------|
| 👨‍⚕️ Doctor | `doctor` | `1234` |
| 🧑 Patient | `invincible` | `1234` |

---

## 📱 Android App

Two pre-built APK files are included:

| APK | Description |
|-----|-------------|
| `Armstrong_Health.apk` | Initial release |
| `Armstrong_Health_Updated.apk` | Latest updated build |

**Install on Android:**
1. Download the APK to your Android device
2. Enable **"Install from Unknown Sources"** in Settings → Security
3. Open the APK file and install

**Build from Source:**
```bash
cd armstrong-android
./gradlew assembleDebug
```
APK will be at: `armstrong-android/app/build/outputs/apk/debug/app-debug.apk`

---

## 👥 Team

**Team Armstrong / The Invincibles**

> Built with ❤️ for smarter, connected healthcare.

---

## 📄 License

This project is licensed under the **MIT License** — feel free to use, modify, and distribute.

---

<p align="center">
  Made with 💙 | HEALTH-BAND © 2026
</p>
