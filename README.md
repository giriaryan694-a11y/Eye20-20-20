# 👁️ Eye20-20-20 | Digital Eye Strain Prevention Tool

A preventative healthcare application designed to mitigate Computer Vision Syndrome (CVS) using the medically recommended **20-20-20 Rule**.

Developed by **Aryan Giri**

---

## 🏥 Project Overview
Prolonged screen exposure can lead to **Computer Vision Syndrome (CVS)**, with symptoms including dry eyes, blurred vision, headaches, and neck strain.

**Eye20-20-20** is a client-side wellness tool that automates the **20-20-20 Rule**, recommended by the American Optometric Association (AOA) to alleviate digital eye strain.

**The Logic**
- **20 Minutes:** Work undisturbed.
- **20 Seconds:** Take a break when alerted.
- **20 Feet:** Focus on an object 20 feet away to relax your eye muscles.

---

## ✨ Key Features
- **🛡️ Privacy-First Healthcare:** Runs 100% client-side. No user health data is collected or transmitted.
- **🌙 Ergonomic UI:** Deep Slate & Soft Green color palette reduces blue light emission and glare.
- **⏱️ Precision Tracking:** "Delta Timing" ensures timer accuracy even when the tab is backgrounded.
- **⏸️ Session Persistence:** Local cookies save session states, allowing pause/resume without losing progress.
- **🔊 Auditory Cues:** Non-jarring audio frequencies (440Hz/660Hz) guide the user.
- **🔔 Interruptive Notifications:** Desktop notifications ensure breaks are taken even if the browser is minimized.

---

## 🚀 How to Run (Local Deployment)
1. **Download:** Download the `index.html` file.
2. **Launch:** Open in any modern web browser.
3. **Permissions:** Allow "Notifications" when prompted.

---

## 📖 User Guide
- **Start Session:** Click **Start Focus** to begin a 20-minute work cycle.
- **Break Phase:** When the timer reaches `00:00`, the screen turns blue. Look away for 20 seconds until the audio chime signals the end of the break.
- **Pause/Resume:** Use the **Pause** button if stepping away.
- **Audio Settings:** Toggle the 🔊 icon to mute cues.

---

## ⚠️ Medical Disclaimer
This software is a **wellness aid only**. It is **not intended to diagnose, treat, cure, or prevent any disease**. Users with persistent eye discomfort should consult a qualified healthcare provider.

---

## 🛠️ Technical Stack
- **Frontend:** HTML5, CSS3, Vanilla JavaScript (ES6)
- **Audio Engine:** Web Audio API (Oscillator Nodes)
- **State Management:** `document.cookie`
- **Compatibility:** Cross-browser (Chromium, Gecko, WebKit)

---

## 👨‍💻 Developer
**Aryan Giri** — Healthcare Technology & Web Development

---

© 2024 Eye20-20-20. Open Source for Educational and Health Purposes.

🌐 **Live Demo:** [Eye20-20-20 Tool](https://giriaryan694-a11y.github.io/Eye20-20-20/)
