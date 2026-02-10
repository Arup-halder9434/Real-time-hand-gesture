# ✋ Real-Time Hand Gesture Recognition

A real-time **hand gesture–controlled particle visualization** project built using **JavaScript**, **MediaPipe Hands**, and **WebGL-style canvas rendering**.  
This project uses your webcam to track hand movements and dynamically interact with animated particles in real time.

> 🚀 Developed by **Arup Halder**  
> 🔐 Cybersecurity & Web Enthusiast  

---

## 🌐 Live Demo
🔗 https://real-time-hand-gesture.vercel.app  
*(Replace with your actual Vercel URL if different)*

---

## 🧠 Features

- 🎥 **Real-time hand tracking** using MediaPipe
- ✋ Detects hand position and movement via webcam
- ✨ Interactive particle effects responding to gestures
- ⚡ Smooth animation & optimized performance
- 🌍 Runs directly in the browser (no backend required)
- 🔒 HTTPS supported (required for camera access)

---

## 🛠️ Tech Stack

- **HTML5**
- **CSS3**
- **JavaScript (ES6)**
- **MediaPipe Hands**
- **Canvas API**
- **Vercel** (Deployment)

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
