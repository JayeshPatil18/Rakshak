# 🛡️ Rakshak
### AI-Powered Women Safety & Emergency Response System

> **Rakshak** is an intelligent women safety platform that enables users to instantly seek help using AI-powered emergency detection. By combining voice recognition, eye gesture detection, health monitoring, and live location tracking, Rakshak ensures emergency alerts reach trusted contacts and responders within seconds—even without an internet connection.

---

## 🌟 Why Rakshak?

In critical situations, every second matters.

Rakshak is designed to eliminate the delay between danger and help by providing multiple emergency trigger methods. Whether the user is unable to reach their phone, loses internet connectivity, or is physically restrained, Rakshak offers alternative ways to request immediate assistance.

---

## 🚀 Key Highlights

<table>
<tr>
<td width="50%">

### 🚨 Smart SOS
- One-tap emergency button
- Voice activated SOS
- Offline SMS fallback

</td>

<td width="50%">

### 🤖 AI Assistance
- Eye blink detection
- Health-based alerts
- AI emergency guidance

</td>
</tr>

<tr>
<td>

### 📍 Live Tracking
- Real-time GPS location
- Continuous location updates
- Trusted contact notifications

</td>

<td>

### 🔔 Instant Response
- Firebase Push Notifications
- Police & Hospital alerts
- Emergency responder support

</td>
</tr>
</table>

---

# ⚙️ How It Works

```text
Emergency Detected
        │
        ▼
SOS Triggered
(Button • Voice • Eye Blink • Health)
        │
        ▼
Current GPS Location Captured
        │
        ▼
AI Processes Emergency
        │
        ▼
Emergency Alert Generated
        │
        ▼
────────────────────────────────────
Trusted Contacts
Police
Hospitals
Nurses
Emergency Responders
────────────────────────────────────
        │
        ▼
Real-Time Tracking Until Safe
```

---

# 🧠 Core Features

### 🚨 Multiple Emergency Triggers
- SOS Button
- Voice Commands
- Eye Blink Detection
- Health Monitoring

### 📡 Smart Emergency Communication
- Live GPS Tracking
- Push Notifications
- SMS Backup
- Emergency Contact Alerts

### 🤖 AI Integration
- IBM Granite LLM
- Speech Recognition
- Google ML Kit
- Intelligent Emergency Assistance

### ☁️ Cloud Infrastructure
- Firebase
- IBM Cloud
- MongoDB
- FastAPI / Node.js

---

# 🏗️ System Architecture

```text
                Android Application
                       │
 ┌─────────────────────┼─────────────────────┐
 │                     │                     │
 ▼                     ▼                     ▼
Google ML Kit     Speech-to-Text      Google Maps
 │                     │                     │
 └──────────────┬──────┴──────────────┬──────┘
                ▼
          Backend APIs
      (FastAPI / Node.js)
                │
      ┌─────────┼──────────┐
      ▼         ▼          ▼
 Firebase    MongoDB   IBM Cloud
      │
      ▼
 Emergency Notifications
      │
      ▼
Police • Hospitals • Nurses • Contacts
```

---

# 💻 Technology Stack

| Category | Technologies |
|----------|--------------|
| **Android** | Kotlin, XML |
| **AI** | Google ML Kit, IBM Granite LLM, Speech-to-Text |
| **Backend** | FastAPI, Node.js |
| **Database** | Firebase, MongoDB |
| **Cloud** | IBM Cloud |
| **Maps** | Google Maps API |
| **Notifications** | Firebase Cloud Messaging |

---

# 📸 Application Screens

| | | | |
|:-:|:-:|:-:|:-:|
| <img src="https://github.com/user-attachments/assets/a24715f4-f58c-4d7f-b12c-bffada726f6a" width="180"/> | <img src="https://github.com/user-attachments/assets/17ed4c05-daef-419d-b1d8-ef6b0bba69cd" width="180"/> | <img src="https://github.com/user-attachments/assets/927885c7-28e8-4751-b6e6-2e4b1ebcd822" width="180"/> | <img src="https://github.com/user-attachments/assets/d611309b-80d5-4371-b50c-4979636ae3ab" width="180"/> |
| <img src="https://github.com/user-attachments/assets/9a431239-d5ab-4c1d-92ab-d9af9f176f60" width="180"/> | <img src="https://github.com/user-attachments/assets/7b665fb1-20a3-46e0-a108-f5d51cefa2d9" width="180"/> | <img src="https://github.com/user-attachments/assets/daff908c-4d28-42c3-a6d6-45d6a90bae4d" width="180"/> | <img src="https://github.com/user-attachments/assets/a1817a96-f45c-497d-aa3b-d092fc8bb8f4" width="180"/> |

---

# 🚀 Quick Setup

```bash
git clone https://github.com/JayeshPatil18/DevClash-Rakshak
cd DevClash-Rakshak
```

1. Open in Android Studio
2. Configure Firebase
3. Add Google Maps API Key
4. Build & Run

---

# 🎯 Vision

Rakshak aims to make emergency assistance faster, smarter, and more accessible by leveraging Artificial Intelligence, cloud computing, and real-time communication technologies to protect women and vulnerable individuals anytime, anywhere.

---

## 📄 License

Licensed under the **MIT License**.
