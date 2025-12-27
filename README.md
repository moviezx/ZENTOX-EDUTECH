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

## 🚀 Installation

### Prerequisites
- Python 3.8 or higher
- Modern web browser (Chrome recommended)
- Webcam (for sleep detection)
- Internet connection

### 1. Clone the Repository
```bash
git clone https://github.com/yourusername/zentox-edutech.git
cd zentox-edutech
```

### 2. Install Python Dependencies
```bash
pip install -r requirements.txt
```

Required packages:
```
flask
flask-cors
google-generativeai
python-dotenv
opencv-python
mediapipe
```

### 3. Set Up Environment Variables
Create `multi_tool_agent/.env`:
```env
# Google AI Studio API Key
GOOGLE_API_KEY=your_google_api_key_here

# Payment Gateway
PAYMENT_API_KEY=your_payment_api_key_here

# Platform Configuration
ZENTOX_ENV=development
ZENTOX_VERSION=1.0.0
```

Get your free Google API key: [Google AI Studio](https://makersuite.google.com/app/apikey)

### 4. Configure Firebase
Update `firebase-config.js` with your Firebase project credentials:
```javascript
const firebaseConfig = {
    apiKey: "your-api-key",
    authDomain: "your-domain",
    projectId: "your-project-id",
    // ...
};
```

### 5. Run the Application

**Option A: All-in-One (Recommended)**
```bash
# Terminal 1: Frontend Server
python serve_frontend.py

# Terminal 2: AI Backend (Optional)
python ai_backend.py

# Terminal 3: Payment Server (Optional)
python payment_backend.py
```

**Option B: Simple Local Server**
```bash
python serve_frontend.py
```

### 6. Access the Application
```
http://localhost:8000/index.html
```

---

## 📖 Usage

### **Getting Started**

1. **Sign In**
   - Click "Login" in navigation
   - Use Google Sign-In
   - Grant necessary permissions

2. **Try AI Chat**
   - Scroll to "AI Demo" section
   - Ask questions like:
     - "Explain machine learning for beginners"
     - "Create a Python study schedule"
     - "Show me a sorting algorithm"

3. **Launch Focus Mode**
   - Click "🎯 Focus Mode" button
   - New window opens

4. **Set Up Your Study Session**
   - Choose YouTube, Spotify, or Web tab
   - Load your study content
   - Set custom timer (or use preset)
   - Enable camera for sleep detection
   - Click Start!

5. **Study Effectively**
   - AI monitors your attention
   - Get alerted if you fall asleep
   - Only focused time counts toward goals
   - View stats in real-time

### **Advanced Features**

**Custom Timer:**
```
Work Duration: 45 minutes
Break Duration: 12 minutes
→ Click "Set Custom Timer"
```

**Sleep Detection Sensitivity:**
- Low: 3 seconds of closed eyes
- Medium: 2 seconds (recommended)
- High: 1 second (very sensitive)

**Multi-Tab Browsing:**
- Load any YouTube video/playlist
- Stream Spotify playlists
- Browse educational websites
- Use custom URLs for courses

---

## 🎬 Demo

### **Screenshots**

#### Landing Page
![Landing Page](docs/screenshots/landing.png)
*Modern dark theme with glassmorphism effects*

#### Focus Mode
![Focus Mode](docs/screenshots/focus-mode.png)
*Multi-tab browser with AI sleep detection*

#### AI Chat
![AI Chat](docs/screenshots/ai-chat.png)
*Real-time AI responses powered by Google Gemini*

### **Live Demo**
🔗 [Try Zentox EduTech Live](http://localhost:8000) _(when running locally)_

### **Video Demo**
📹 [Watch Feature Walkthrough](https://youtube.com/demo) _(coming soon)_

---

## 🧪 Testing

### **Feature Checklist**

- [ ] **Landing Page**
  - [ ] Smooth scrolling navigation
  - [ ] Animated hero section
  - [ ] Feature cards with hover effects
  - [ ] Responsive on mobile

- [ ] **AI Chat**
  - [ ] Send messages
  - [ ] Receive AI responses
  - [ ] Suggestion chips work
  - [ ] Clear chat functionality

- [ ] **Focus Mode**
  - [ ] YouTube tab loads videos
  - [ ] Spotify tab plays music
  - [ ] Web browser opens sites
  - [ ] Custom timer sets durations
  - [ ] Sleep detection triggers
  - [ ] Stats update in real-time

- [ ] **Authentication**
  - [ ] Google Sign-In works
  - [ ] User profile displays
  - [ ] Session persists

- [ ] **Payment**
  - [ ] Modal opens
  - [ ] Payment flow completes
  - [ ] Pro status activates

### **Manual Testing**

**Sleep Detection:**
```javascript
// Open browser console in Focus Mode
window.focusMode.triggerSleep()  // Manually trigger
window.focusMode.wakeUp()        // Dismiss alert
```

---

## 🌍 Deployment

### **Frontend Deployment**

**Firebase Hosting:**
```bash
npm install -g firebase-tools
firebase login
firebase init hosting
firebase deploy
```

**Netlify:**
```bash
# Drag & drop 'frontend' folder
# Or connect GitHub repo
```

**Vercel:**
```bash
npm i -g vercel
vercel
```

### **Backend Deployment**

**Heroku:**
```bash
heroku create zentox-ai-backend
git push heroku main
```

**Railway:**
```bash
railway init
railway up
```

**Google Cloud Run:**
```bash
gcloud run deploy zentox-backend \
  --source . \
  --platform managed
```

---

## 🤝 Contributing

We welcome contributions! Here's how:

### **1. Fork the Repository**
Click "Fork" button on GitHub

### **2. Create a Branch**
```bash
git checkout -b feature/amazing-feature
```

### **3. Make Changes**
- Follow existing code style
- Add comments for complex logic
- Test thoroughly

### **4. Commit Changes**
```bash
git commit -m "Add amazing feature"
```

### **5. Push to Branch**
```bash
git push origin feature/amazing-feature
```

### **6. Open Pull Request**
- Describe your changes
- Link related issues
- Request review

### **Contribution Guidelines**
- 📝 Clear commit messages
- 🎨 Follow design system
- 🧪 Include tests
- 📚 Update documentation
- ✅ Pass all checks

---

## 🛡️ License

This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.

```
MIT License

Copyright (c) 2025 Zentox EduTech

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction...
```

---

## 👥 Team

### **Developer**
- **Your Name** - *Full Stack Developer* - [@yourusername](https://github.com/yourusername)

### **Acknowledgments**
- Google Gemini for AI capabilities
- Firebase for authentication
- MediaPipe for computer vision
- The open-source community

---

## 📧 Contact

### **Get in Touch**
- 🌐 Website: [zentox.edu](https://zentox.edu) _(coming soon)_
- 📧 Email: contact@zentox.edu
- 🐦 Twitter: [@ZentoxEduTech](https://twitter.com/zentoxedutech)
- 💼 LinkedIn: [Zentox EduTech](https://linkedin.com/company/zentox-edutech)

### **Support**
- 🐛 Bug Reports: [GitHub Issues](https://github.com/yourusername/zentox-edutech/issues)
- 💡 Feature Requests: [GitHub Discussions](https://github.com/yourusername/zentox-edutech/discussions)
- 📚 Documentation: [Wiki](https://github.com/yourusername/zentox-edutech/wiki)

---

## 📊 Project Stats

![GitHub stars](https://img.shields.io/github/stars/yourusername/zentox-edutech?style=social)
![GitHub forks](https://img.shields.io/github/forks/yourusername/zentox-edutech?style=social)
![GitHub issues](https://img.shields.io/github/issues/yourusername/zentox-edutech)
![GitHub pull requests](https://img.shields.io/github/issues-pr/yourusername/zentox-edutech)

### **By the Numbers**
- 📝 **6,000+** lines of code
- 🎨 **30+** files
- 🔧 **3** backend servers
- 🌐 **5** API integrations
- ⚡ **20+** features
- 🎯 **100%** functional

---

## 🎯 Roadmap

### **Version 1.0** (Current)
- [x] Landing page
- [x] Focus Mode with sleep detection
- [x] AI chatbot
- [x] Firebase authentication
- [x] Payment integration

### **Version 1.1** (Next Release)
- [ ] Mobile app (React Native)
- [ ] Browser extension
- [ ] Advanced ML models
- [ ] Collaborative study rooms
- [ ] Gamification & achievements

### **Version 2.0** (Future)
- [ ] Teacher/admin dashboard
- [ ] Institutional licensing
- [ ] API for third-party integrations
- [ ] Advanced analytics & insights
- [ ] Multi-language support

---

## ⭐ Show Your Support

If you found this project helpful, please consider:
- ⭐ **Star this repository**
- 🍴 **Fork and contribute**
- 🐛 **Report bugs**
- 💡 **Suggest features**
- 📢 **Share with others**

---

## 🏆 Awards & Recognition

- 🥇 **Best EdTech Solution** - Google Developers Community Delhi Hackathon 2025
- 🌟 **Innovation Award** - _(coming soon)_
- 🎓 **Student Choice** - _(coming soon)_

---

<div align="center">

### 💖 Made with Love for Students Everywhere

**Track Attention, Not Just Time** ⏱️

---

[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/yourusername/zentox-edutech)
[![Website](https://img.shields.io/badge/Website-Coming_Soon-blue?style=for-the-badge)](https://zentox.edu)
[![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)](LICENSE)

**© 2025 Zentox EduTech. All Rights Reserved.**

</div>

