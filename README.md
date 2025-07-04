# 🏠 Smart Home ASR (Voice-Controlled Smart Home)

🎯 **Smart Home Automation System with voice control (ASR)** using Python.  
Tích hợp nhận dạng giọng nói (Speech Recognition), điều khiển thiết bị qua GPIO và giao diện người dùng (GUI).

---

## 📌 Table of Contents
- [Features](#features)
- [Project Structure](#project-structure)
- [Installation](#installation)
- [Usage](#usage)
- [License](#license)

---

## 🚀 Features
✅ Voice-controlled commands via ASR (Automatic Speech Recognition)  
✅ Real-time GPIO device control (simulate smart home appliances)  
✅ Customizable command mapping (`command_map.py`)  
✅ Friendly GUI (`gui.py`) to visualize and control devices  
✅ Configurable vocabulary & speech settings

---

## 📂 Project Structure
```
.
├── Báo cáo .docx.pdf         # Project report
├── README.md
├── asr_speech_recognition.ipynb # Jupyter notebook ASR pipeline
├── audio.py, voice.py        # Audio capture & voice processing
├── command_map.py            # Maps voice commands to actions
├── config.py                 # Configuration parameters
├── gpio_control.py           # GPIO handling (smart devices)
├── gui.py                    # Tkinter GUI
├── main.py                   # Main entry point
├── requirements.txt          # Python dependencies
├── utils.py, vocab.txt
```

---

## ⚙️ Installation
Create a virtual environment (optional but recommended):

```bash
python -m venv venv
source venv/bin/activate  # or venv\Scripts\activate on Windows
```

Install dependencies:
```bash
pip install -r requirements.txt
```

---

## 🚀 Usage

### Run the main system
```bash
python main.py
```

This starts the ASR engine, listens for commands and controls GPIO accordingly.  
It also launches the GUI to display device status.

### Jupyter Notebook (demo ASR pipeline)
```bash
jupyter notebook asr_speech_recognition.ipynb
```

---

## 📜 License
MIT License.

---

🚀 **Enjoy & Star this repo if you like it!**
