# 🌱 Smart Greenhouse Platform

A smart web-based platform for monitoring crops, getting AI-powered recommendations, and making intelligent farming decisions.

![Version](https://img.shields.io/badge/version-3.0.0-brightgreen)
![License](https://img.shields.io/badge/license-MIT-green)
![HTML](https://img.shields.io/badge/built%20with-HTML%2FJS-orange)

---

## 🚀 Features

| Feature | Description |
|---|---|
| 📊 Live Dashboard | Real-time temperature, water, health & light monitoring |
| 📈 Live Chart | Auto-updating temperature trend graph |
| 🌐 Weather Monitor | Location-based weather lookup |
| 🤖 AI Crop Recommendations | Smart suggestions based on temp, soil, weather & water |
| 🌱 Crop Guide | Knowledge base of 12+ crops |
| 💬 AI Assistant | Real GPT-4o-mini powered chat (or local fallback) |
| 🔔 Alert System | Auto-alerts for low water & high temperature |
| ⚙️ Settings Panel | Configurable thresholds and preferences |
| 📱 Mobile Responsive | Works on all screen sizes |

---

## 🖥️ Run Locally (via CMD)

### Option 1 — Python (Recommended, no install needed)

```bash
# Python 3 (most systems have this)
python -m http.server 8080

# Then open in browser:
# http://localhost:8080
```

### Option 2 — Node.js

```bash
# Install serve globally (one-time)
npm install -g serve

# Run the server
serve . -p 8080

# Then open:
# http://localhost:8080
```

### Option 3 — Use the included run scripts

**Windows:**
```bash
run-windows.bat
```

**Mac/Linux:**
```bash
chmod +x run-unix.sh
./run-unix.sh
```

---

## 📁 Project Structure

```
smart-greenhouse/
├── index.html              ← Main application (single file)
├── README.md               ← This file
├── run-windows.bat         ← Windows localhost launcher
├── run-unix.sh             ← Mac/Linux localhost launcher
└── .gitignore              ← Git ignore rules
```

---

## 🔑 Enable Real AI Agent

1. Open the app → click **"Connect Real AI Agent"**
2. Paste your OpenAI API key (`sk-...`)
3. Get a key at [platform.openai.com/api-keys](https://platform.openai.com/api-keys)

> Without a key, the app runs in **Local Mode** with built-in farming knowledge.

---

## 🌍 GitHub Setup

```bash
# Clone or initialize
git init
git add .
git commit -m "🌱 Initial commit - Smart Greenhouse Platform v3.0"

# Push to GitHub
git remote add origin https://github.com/YOUR_USERNAME/smart-greenhouse.git
git branch -M main
git push -u origin main
```

---

## 📜 License

MIT © 2025 Smart Greenhouse Platform
