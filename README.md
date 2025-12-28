# 🎓 ZENTOX EDUTECH

<div align="center">

![Zentox EduTech](https://img.shields.io/badge/ZENTOX-EDUTECH-6366f1?style=for-the-badge&logo=data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iMTAwIiBoZWlnaHQ9IjEwMCIgdmlld0JveD0iMCAwIDEwMCAxMDAiIGZpbGw9Im5vbmUiPjxjaXJjbGUgY3g9IjUwIiBjeT0iNTAiIHI9IjQ1IiBmaWxsPSIjNjM2NmYxIiBvcGFjaXR5PSIwLjIiLz48cGF0aCBkPSJNMzAgMzUgTDUwIDI1IEw3MCAzNSBMNzAgNjUgTDUwIDc1IEwzMCA2NSBaIiBmaWxsPSIjNjM2NmYxIi8+PC9zdmc+)

### Track Attention, Not Just Time ⏱️

[![Live Demo](https://img.shields.io/badge/demo-live-success?style=flat-square)](http://localhost:8000)
[![License](https://img.shields.io/badge/license-MIT-blue?style=flat-square)](LICENSE)
[![Made with Love](https://img.shields.io/badge/Made%20with-❤️-red?style=flat-square)](https://github.com/yourusername/zentox-edutech)

**An AI-powered study companion that revolutionizes learning by tracking focus and attention, not just screen time.**

[Features](#-features) • [Tech Stack](#-tech-stack) • [Installation](#-installation) • [Demo](#-demo) • [Contributing](#-contributing)

</div>

---

## 🌟 Overview

Zentox EduTech is a next-generation educational platform that combines **AI-powered sleep detection**, **real-time focus tracking**, and **intelligent study analytics** to help students study more effectively. Unlike traditional study timers that only track duration, Zentox tracks **quality** of study time using computer vision and machine learning.

### 🎯 The Problem
- 📚 Students study for hours but retain little
- 😴 Falling asleep while "studying" inflates time logs
- 📊 No way to measure actual focus and attention
- 🎵 Passive listening doesn't equal active learning

### ✨ Our Solution
- 🤖 **AI Sleep Detection** - Pauses timer when you fall asleep
- 📈 **Effective Time Tracking** - Only counts focused study hours
- 🎯 **Focus Mode** - Multi-tab browser with YouTube, Spotify, web in one place
- 💡 **AI Tutor** - 24/7 assistant powered by Google Gemini
- 📊 **Smart Analytics** - Graded sessions (A-F) based on focus quality

---

## ✨ Features

### 🎯 **Focus Mode V2** (Our Flagship Feature!)
The ultimate study environment combining everything students need:

- **📺 Multi-Tab Browser**
  - YouTube player with playlist support
  - Spotify integration for study music
  - Web browser for research
  - Custom URL loader

- **⏱️ Custom Study Timer**
  - Pomodoro (25/5), Extended (50/10), Deep Work (90/15)
  - Fully customizable work/break durations (5-180 min)
  - Auto-switching between work and break sessions
  - Visual progress tracking

- **😴 Real AI Sleep Detection**
  - Webcam-based eye tracking
  - Brightness analysis algorithm
  - 3 sensitivity levels (Low/Medium/High)
  - Instant alerts with alarm sound
  - Auto-pauses media when sleeping

- **📊 Session Statistics**
  - Total Time vs Effective Time
  - Sleep alert counter
  - Efficiency percentage
  - Color-coded performance indicators

### 💬 **AI Educator Assistant**
24/7 intelligent tutor powered by Google Gemini 2.0:
- Multi-level concept explanations
- Code examples in 5+ languages
- Personalized study plans
- Instant doubt solving
- Context-aware responses

### 💻 **Integrated Code Compiler**
Practice coding without leaving the platform:
- Support for Python, JavaScript, Java, C, C++
- Real-time code execution
- Syntax highlighting
- Built-in examples library

### 📈 **Effective Hours Analytics**
Track quality, not just quantity:
- **Formula**: Focus × Time = Effective Hours
- Performance grading (A-F) based on:
  - Focus score (sleep detection)
  - Break optimization
  - Distraction tracking
- Progress dashboard with insights

### 🔐 **Firebase Authentication**
Secure Google Sign-In integration:
- One-click authentication
- User profile management
- Session persistence
- Secure data storage

### 💳 **Payment Integration**
Full subscription management:
- **Basic**: Free tier (2 hours/day)
- **Pro**: ₹299/month (unlimited access)
- Secure payment processing
- Instant activation
- Recurring billing support

---

## 🛠️ Tech Stack

### **Frontend**
```
HTML5, CSS3, Vanilla JavaScript
├── Design: Glassmorphism, Dark Theme
├── Animations: CSS Transitions, Keyframes
├── Icons: Custom SVG, Inline Graphics
└── Responsive: Mobile-first approach
```

### **Backend**
```python
Python 3.8+
├── Flask (API Server)
├── Google Gemini AI (Chatbot)
├── Firebase (Authentication)
└── Payment Gateway Integration
```

### **AI & ML**
```
├── Google Gemini Pro (AI Tutor)
├── MediaPipe (Face Detection - Ready)
├── OpenCV (Computer Vision - Ready)
└── Custom Algorithms (Sleep Detection)
```

### **APIs & Services**
- 🔥 **Firebase** - Authentication & Database
- 🤖 **Google Gemini API** - AI Responses
- 📺 **YouTube Embed API** - Video Integration
- 🎵 **Spotify Embed API** - Music Integration
- 💳 **Payment Gateway** - Khata Pay/Razorpay

---

## 📂 Project Structure

```
ZENTOX-EDUTECH/
│
├── frontend/
│   ├── index.html              # Main landing page
│   ├── focus-mode.html         # Focus Mode feature
│   ├── styles.css              # Main stylesheet
│   ├── focus-mode.css          # Focus Mode styles
│   ├── app.js                  # Main JavaScript
│   ├── focus-mode.js           # Focus Mode logic
│   ├── payment.js              # Payment integration
│   └── README.md               # Frontend docs
│
├── multi_tool_agent/
│   ├── zentox_agent.py         # AI agent with 8 tools
│   ├── .env                    # API keys (not in repo)
│   └── README.md               # Agent documentation
│
├── ai_backend.py               # Google Gemini server
├── payment_backend.py          # Payment processing
├── serve_frontend.py           # Development server
├── firebase-config.js          # Firebase setup
│
├── docs/
│   ├── START_HERE.md           # Quick start guide
│   ├── FOCUS_MODE_V2_GUIDE.md  # Focus Mode documentation
│   ├── PAYMENT_INTEGRATION.md  # Payment setup
│   └── LOGO_UPDATE.md          # Branding guide
│
└── README.md                   # This file
```

---

