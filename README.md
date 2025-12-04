# Jarvis — Simple Voice Assistant

A lightweight voice assistant built using **SpeechRecognition** and **pyttsx3**.  
It listens for a wake word (**"hey jarvis"**) and performs simple voice-based actions such as opening websites.

---

## 🚀 Features
- Wake-word detection (“hey jarvis”)
- Opens Google, YouTube, LinkedIn, Instagram via voice
- Text-to-speech responses
- Simple, easy-to-modify command handling

---

## 📦 Installation

1. Create a virtual environment (optional but recommended):
   ```bash
   python -m venv venv
   # Windows
   venv\Scripts\activate
   # macOS / Linux
   source venv/bin/activate
Install dependencies:

pip install -r requirements.txt

⚠️ Windows PyAudio Note

If PyAudio fails to install, run:

pip install pipwin
pipwin install pyaudio

▶️ Usage

Run the program:

python main.py


Then say the wake word:
“hey jarvis”

Available commands:

open google

open youtube

open linkedin

open instagram

quit / exit / stop

📁 Project Files

main.py — main source code

requirements.txt — required libraries

📌 Notes

This is a beginner-friendly voice assistant project and can be easily extended with new features such as:

Playing music

Opening desktop apps

System automation commands
