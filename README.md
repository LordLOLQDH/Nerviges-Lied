# Audio Loop & Volume Controller

## 📌 Overview
This project is a simple audio automation tool that continuously plays a selected audio track in a loop while maintaining a fixed system volume level.

It is intended for educational and experimental purposes only.

---

## ⚙️ Features
- Continuous playback of a selected audio file
- Automatic volume adjustment to a predefined level
- Runs in the background while active
- Simple start/stop control (if implemented)

---

## 🚀 How It Works
The script:
1. Loads the selected audio file
2. Plays it in a continuous loop
3. Monitors system volume
4. Resets volume to the configured level if it changes

---

## 🖥️ Requirements
- Python 3.x (or your runtime environment)
- Required libraries (example):
  - `pygame` / `pydub` / `playsound` (depending on implementation)
  - `pycaw` (Windows volume control, if used)

Install dependencies:
```bash
pip install -r requirements.txt
