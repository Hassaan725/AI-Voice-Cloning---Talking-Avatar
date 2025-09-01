# AI-Voice-Cloning---Talking-Avatar
AI-powered voice cloning with a realistic talking avatar, enabling lifelike speech and facial animation from just text or audio input.
# Week 1 - Text-to-Speech (TTS) Project

# Text to Speech with gTTS

This project converts text into speech using **Google Text-to-Speech (gTTS)** in Python.  
It generates an audio file (`output_audio.mp3`) that you can play on any media player.

---

## 📌 Requirements

- Python 3.x
- gTTS library

---

## ⚙️ Installation

1. Install Python (if not installed already).  
   Check with:
   ```bash
   python --version

# 🎙️ Chatterbox Voice Cloning (TTS)

This project demonstrates **voice cloning** using the [chatterbox-tts](https://pypi.org/project/chatterbox-tts/) library with PyTorch.  
It takes a **reference voice sample** (`.wav` file) and generates speech in the **same voice** for any input text.

---

## 📌 Requirements

- Python **3.11 (64-bit)**
- Virtual environment (`venv`)
- Dependencies:


---

## ⚙️ Setup Instructions

```powershell
# 1. Create project folder
mkdir C:\Users\DELL\chatterbox_project
cd C:\Users\DELL\chatterbox_project

# 2. Create virtual environment
python -m venv .venv

# 3. Activate environment
.venv\Scripts\activate

# 4. Upgrade pip
python -m pip install --upgrade pip

# 5. Install dependencies
pip install torch==2.6.0 torchaudio==2.6.0
pip install transformers==4.46.3 diffusers==0.29.0
pip install conformer==0.3.2 s3tokenizer==0.2.0
pip install librosa==0.11.0 numpy>=1.26.0
pip install chatterbox-tts==0.1.2


