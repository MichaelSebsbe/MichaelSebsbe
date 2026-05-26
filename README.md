# 👋 Hi, I'm Michael Sebsbe

**Full-stack Mobile & Web Developer**
📍 Toronto, Canada

I build scalable, production-ready mobile and web applications with a strong focus on **performance, developer experience, and real-world reliability**. My background spans **iOS, Android, backend services, and modern web tech**.

---

## 🛠️ What I Work With

**Languages & Frameworks**

* TypeScript / JavaScript
* Swift (iOS, watchOS, WKWebView)
* Python
* React / React Native
* Node.js

**Mobile**

* iOS (Swift, UIKit, SwiftUI)
* React Native (Expo)
* OTA update systems
* Push notifications (APNs, Android)

**Backend & Infra**

* Node.js services
* RabbitMQ (event-driven systems)
* REST & WebSocket APIs
* Docker & CI/CD pipelines
* Cloud deployments

---

## 📌 Featured Projects

### 📲 EasyPush

A **Node.js push notification service** using **RabbitMQ** as a message broker.
Designed for scalable, async delivery of iOS push notifications via APNs.

* TypeScript
* Message queues
* Service-oriented architecture

---

### ✈️ FlyPieter

A **WKWebView wrapper** for a browser-based flight simulator experience.

* Swift
* iOS WebView integrations
* Native ↔ Web communication

---

### 🐍 Async Notification Service – Python Client

A Python client library for interacting with an async notification service.

* Python
* Clean API design
* Client-side reliability

---

## 🌟 Open Source Contributions

### ✨ React Native Paper – ProgressBar Fix

Merged into **[@callstack/react-native-paper](https://github.com/callstack/react-native-paper)** (popular React Native UI library).

Fixed a visual bug where determinate `ProgressBar` fill border radius was scaled down at low progress values. Updated the animation approach to preserve rounded fill styles while maintaining native driver compatibility.

* **Impact**: Improved visual consistency for thousands of app developers
* **Tech**: TypeScript, React Native, Animation transforms
* [View PR #4950](https://github.com/callstack/react-native-paper/pull/4950)

---

### 🔄 React Native OTA Hot Update – Bundle Fallback

Merged into **[@vantuan88291/react-native-ota-hot-update](https://github.com/vantuan88291/react-native-ota-hot-update)** (production OTA update system).

Fixed a critical crash on Samsung devices where SharedPreferences restoration after app reinstall caused startup failures. Implemented validation logic and graceful fallback to embedded bundle when stored paths are stale or missing.

* **Impact**: Prevents production crashes in backup/restore scenarios
* **Problem solved**: `JSBigFileString::fromPath - Could not open file` errors
* **Tech**: Android, Java, SharedPreferences, edge-case reliability
* [View PR #131](https://github.com/vantuan88291/react-native-ota-hot-update/pull/131)

---

## 📈 Open Source & Activity

* Merged contributions in established open-source projects
* Consistent commits across public and private repositories
* Focused on **bug fixes, edge cases, and production stability**
* Pull requests with real-world impact

---

## 💡 How I Think About Software

* Performance matters — users notice delays
* Frontend is the *API for humans*
* Systems should fail **gracefully**
* Good DevOps saves teams time
* Clean architecture beats clever hacks

---

## 📫 Get in Touch

* 📧 Email: **[MichaelSebsbe@gmail.com](mailto:MichaelSebsbe@gmail.com)**
* 💼 GitHub: [github.com/MichaelSebsbe](https://github.com/MichaelSebsbe)

---

Thanks for stopping by 👀
Always happy to collaborate or talk architecture.
