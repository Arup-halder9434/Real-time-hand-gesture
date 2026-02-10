# ✋ Real-Time Hand Gesture Recognition

A real-time **hand gesture–controlled particle visualization** project built using **JavaScript**, **MediaPipe Hands**, and **HTML5 Canvas**.  
The system tracks hand movements via webcam and dynamically interacts with animated particles in real time.

> 👨‍💻 Created by **Arup Halder**  
> 🔗 GitHub Profile: https://github.com/Arup-halder9434  
> 📂 Project Repository: https://github.com/Arup-halder9434/Real-time-hand-gesture  

---

## 🌐 Live Demo
🚀 https://real-time-hand-gesture-jet.vercel.app/

---

## ✨ Features

- ✋ Real-time hand gesture detection
- 🎥 Webcam-based tracking using MediaPipe Hands
- 🌌 Interactive particle animations
- ⚡ Smooth and responsive performance
- 🌍 Fully browser-based (no backend)
- 🔐 HTTPS supported for camera access

---

## 🛠️ Tech Stack

- HTML5  
- CSS3  
- JavaScript (ES6)  
- MediaPipe Hands  
- Canvas API  
- Vercel (Deployment)

---

## 📂 Project Structure



---

## 🚀 Deployment (Vercel)

This project is deployed as a **static site** on Vercel.

### Vercel Settings:
- **Framework Preset:** Other
- **Build Command:** None
- **Output Directory:** Root

### `vercel.json`
```json
{
  "version": 2,
  "routes": [
    {
      "src": "/(.*)",
      "dest": "/index.html"
    }
  ]
}

git clone https://github.com/Arup-halder9434/Real-time-hand-gesture.git
cd Real-time-hand-gesture
python3 -m http.server 8000

http://localhost:8000
