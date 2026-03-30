# 🧠 Autonomous Focus Intelligence System

A system that tracks user focus using camera input and system activity, and responds in real time to improve productivity.

---

## 📌 Overview

This project monitors attention using computer vision and active window tracking.  
It detects when a user is focused or distracted and can take simple actions like alerts or restrictions.

---

## ⚡ Features

- Face & Eye Tracking (MediaPipe + OpenCV)  
- Active Window Detection  
- Focus Detection (Focused / Distracted)  
- Basic Automated Actions (alerts, restrictions)  
- Focus Time & Usage Stats  
- Gradio Dashboard  

---

## 🏗️ Architecture

```
Camera + System Activity
        ↓
Focus Detection
        ↓
Decision Logic
        ↓
Actions + Dashboard
```

---

## 🛠️ Tech Stack

- Python  
- OpenCV  
- MediaPipe  
- Gradio  
- System APIs  

---

## ▶️ How to Run

```bash
git clone https://github.com/msainavtej/IITH_Hackathon.git
cd your-repo-name

python -m venv venv
source venv/bin/activate   # Windows: venv\Scripts\activate

pip install -r requirements.txt
python main.py
```

---

## 📂 Structure

```
main.py             # entry point  
focus_tracker.py    # vision + focus logic  
activity.py         # active window tracking  
ui.py               # Gradio interface  
focus_data.csv      # logs  
```

---

## 🎯 Use Cases

- Studying / exam prep  
- Remote work  
- General productivity  

---

## 🚀 Future Work

- Better focus detection  
- Browser integration  
- Smarter insights  

---

## 👥 Team

Built during a hackathon by a team of 4.
