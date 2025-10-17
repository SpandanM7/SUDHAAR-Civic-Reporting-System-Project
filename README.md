# 🏙️ SUDHAAR – Civic Issues Resolve System

### Empowering Citizens. Enabling Authorities. Enhancing Cities.

## 🚀 Project Overview

SUDHAAR is composed of Six(6) integrated modules working together through Firebase Cloud Services.

| Module | Description | Repository |
|--------|--------------|------------|
| 📱 **Android App (Citizen Side)** | Mobile application for citizens to report civic issues with geo-tagged photos and live tracking. | [SUDHAAR (Android App)](https://github.com/SpandanM7/SUDHAAR) |
| ☁️ **Android App Backend** | Firebase-based backend handling authentication, complaint storage, and image uploads for the mobile app. | [SUDHAAR-BACKEND](https://github.com/SpandanM7/SUDHAAR-BACKEND) |
| 💻 **Web Dashboard (Authority Side)** | Web portal for municipal authorities to view, manage, assign field teams and update reported issues. | [sudhaar-web](https://github.com/Sourish-spc/sudhaar-web) |
| ⚙️ **Web Dashboard Backend** | Cloud backend APIs and database management for the web dashboard. | [SUDHAAR-BACKEND-WEB](https://github.com/SpandanM7/SUDHAAR-BACKEND-WEB) |
| 📱 **Higher authority Web App** |  Web portal for higher authorities like state development bodies to oversee performance of municipal authorities and see analysis. | UNDER PRODUCTION|
| 📱 **Android App (Field Team Side)** | Mobile application for Field teams to get to know about their day-to-day duties. | UNDER PRODUCTION|
---


**SUDHAAR** is a smart civic issue management platform that bridges the gap between citizens and local authorities.  
It enables users to **report, track, and resolve public infrastructure problems** such as potholes, garbage, and streetlight faults through a mobile app, while providing a **web dashboard** for authorities to manage complaints efficiently.

---


## 🧩 System Architecture


[ Citizen (Android App) ]
|
| Firebase Authentication / Firestore / Storage
↓
[ Firebase Cloud Services ]
↑
|
[ Authority Web Dashboard ]


Both the Android app and the web dashboard interact with the same Firebase backend, ensuring **real-time data synchronization**, **secure authentication**, and **seamless communication**.

---

## ⚙️ Tech Stack

**Mobile (Citizen App):**
- Kotlin, Android Studio  
- Firebase Firestore, Firebase Storage, Firebase Authentication  
- Google Maps API (Geo-tagging)

**Web (Authority Dashboard):**
- HTML, CSS, JavaScript  
- Firebase SDK, REST APIs  
- Firebase Hosting (Deployment)

**Backend (Cloud):**
- Firebase Cloud Functions / Node.js  
- Firestore Database  
- Cloud Storage

---

## 🔑 Key Features

### 👥 Citizen App
- Report issues with **title, description, image, and GPS location**
- **Geo-tagging** via Google Maps API  
- **Firebase Authentication** for secure user access  
- Real-time **issue tracking and updates**

### 🏢 Authority Dashboard
- **View, update, and filter** complaints in real-time  
- Manage issue status: *Pending → In Progress → Resolved*  
- View issue images and map location  
- Real-time sync with citizen app

### ☁️ Cloud Backend
- Handles **data validation**, **image storage**, and **status updates**  
- Built using **Firebase Cloud Functions** for scalability  
- Uses **Firestore rules** for data security and access control

---

## 📸 Screenshots (optional)

| Android App | Web Dashboard |
|--------------|---------------|
| ![App Screenshot](#) | ![Dashboard Screenshot](#) |

*(Add your screenshots later by replacing the # with image links.)*

---

## 🧠 Future Enhancements
- 🔹 AI-based issue classification using image recognition  
- 🔹 Map clustering to visualize issue density  
- 🔹 Analytics dashboard for city-level insights  
- 🔹 Multi-language support for inclusivity  

---

## 🧑‍💻 Contributors

- **[Spandan M](https://github.com/SpandanM7)** — Project Lead & Full-Stack Developer  
  - Android App Development  
  - Firebase Backend Integration  
  - Web Dashboard & Backend Development  

---

## 📜 License

This project is open-source and available under the **[MIT License](LICENSE)**.

---

## 🌐 Quick Links

- 📱 [Android App](https://github.com/SpandanM7/SUDHAAR)  
- ☁️ [Android App Backend](https://github.com/SpandanM7/SUDHAAR-BACKEND)  
- 💻 [Web Dashboard](https://github.com/SpandanM7/sudhaar-web)  
- ⚙️ [Web Dashboard Backend](https://github.com/SpandanM7/SUDHAAR-BACKEND-WEB)

---

> “SUDHAAR aims to make civic governance transparent, efficient, and citizen-driven through technology.”

