# 🤖 Jarvis Assistant Bot

Jarvis is a simple voice-enabled personal assistant built with Python. It can listen to your commands, talk back using text-to-speech, tell jokes, and play sounds — a fun and functional base for building advanced AI assistants.

---

## 🧠 Features

- 🎙️ Speech Recognition (voice commands)
- 🗣️ Text-to-Speech responses using `pyttsx3`
- 😂 Random jokes with `pyjokes`
- 🔊 Sound playback with `playsound`
- 💬 Easy to customize and extend

---

## 📦 Requirements

Make sure Python 3.11+ is installed. Install dependencies using:

```bash
pip install pyttsx3 SpeechRecognition pyjokes playsound==1.2.2
⚠️ Use playsound==1.2.2 because later versions may fail during installation.

🧰 Project Structure
bash
Copy
Edit
Jarvis-Bot/
├── main.py              # Main bot script
├── README.md            # You're reading this
└── requirements.txt     # (Optional) Dependencies list
