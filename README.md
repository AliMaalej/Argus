# 🧠 ARGUS – AI-Powered Intelligent Security Platform

## 🎯 Project Objective

**ARGUS** is an **AI-powered web platform** built with **Django + Python** to enhance **security monitoring** through **computer vision** and **artificial intelligence**.  

It integrates several intelligent modules:

- 🔐 **Secure authentication** (facial recognition)  
- 🎥 **Live video streaming**  
- 🤖 **Automatic detection** (person, object, motion)  
- ⚠️ **Alert and notification system**  
- 📊 **Alert history and automated analytics**  
- 😊 **Real-time emotion detection**  
- 🗣️ **Voice control for security actions**  

---

## 🧩 Project Overview

**ARGUS** is an intelligent surveillance platform that combines **facial recognition**, **object/person detection**, **motion tracking**, **emotion analysis**, and **voice command detection** to automate and strengthen security operations.  

---

## 😊 Live Emotion Detection

Detect emotions in real time using your webcam, with results displayed as overlays on the live video feed.  

### ▶️ Start it with:
```bash
python emotion_launcher.py
```

## ⚙️ How It Works

1. Navigate to `/emotion/live/` in the web UI.  
2. Click **“Launch Live Emotion Detection.”**  
3. The web app sends a request to the local launcher.  
4. The launcher opens a desktop window showing your webcam feed and emotion labels (powered by **DeepFace**).  
5. The window may take a few seconds to appear.

---

## 🧱 Requirements

- Run `emotion_launcher.py` locally before using this feature.  

> **Note:** This feature runs entirely on your **local machine** for privacy and performance.  
> The web UI only triggers the desktop app — no video data is streamed to the server.

---

## ⚙️ Technologies Used

| Category | Technologies |
|-----------|---------------|
| **Backend** | Django (Python 3.13) |
| **Frontend** | HTML5, CSS3, Bootstrap 5 |
| **Database** | SQLite |
| **AI / Computer Vision** | DeepFace, OpenCV, YOLOv5, MediaPipe |
| **NLP Analysis** | OpenAI API, Hugging Face Summarization |
| **Version Control** | Git + GitHub |

---

## 🚀 Quick Setup

1. Clone the repository  
```bash
git clone https://github.com/your-username/argus.git
cd argus
```
2. Create and activate a virtual environment (Python 3.11)  
```bash
python -m venv venv
.\venv\Scripts\activate  # On Windows
source venv/bin/activate # On macOS/Linux
```
3. Install dependencies  
```bash
pip install -r requirements.txt
```
4. Download SpaCy language model  
```bash
python -m spacy download en_core_web_md
```
5. Apply migrations  
```bash
python manage.py migrate
```
6. Run the server  
```bash
python manage.py runserver
```
Visit → [http://127.0.0.1:8000/](http://127.0.0.1:8000/)

---

## 🧰 Troubleshooting

- Ensure you are using **Python 3.11**  
- If dependencies fail, reinstall with:  
```bash
pip install --upgrade pip setuptools wheel
```

---

## 📜 License

**Academic Project – Non-Commercial Use Only**  
© 2025 **ARGUS Project** – All Rights Reserved  
