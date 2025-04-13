# VidyAI-# VidyAI++ Backend – Multilingual AI Tutoring Module

 **Objective**  
This module powers the AI-driven multilingual tutoring system for *VidyAI++*, aimed at providing localized, personalized lessons and quizzes to underprivileged (BPL) students in Indian government schools. It uses GPT for lesson generation, Google Translate for localization, and gTTS for speech output.

---

## Features

- Generates class-wise lesson content using OpenAI GPT-3.5
- Translates content to regional Indian languages using Google Translate
- Converts lessons into audio using gTTS (Text-to-Speech) 
- Returns structured lesson text, quiz questions, and audio link
- API ready for integration with frontend (React, Next.js, etc.)
- Personalized Tutoring​
- Real-Time Chatbot​
- Data Security
- Voice/text input​
- Text-to-speech​
- Emotion detection (via webcam)​
- Learning style adaptation (with quizzes)​
- Multilingual translation​
- ​Mentor matching​
- Points + streak system (with persistence)​


## Tools

- **Backend Framework**: FastAPI
- **AI Model**: OpenAI GPT-3.5
- **Translation**: Google Translate API (Unofficial)
- **TTS**: gTTS (Google Text-to-Speech)
- **Language Support**: Hindi (`hi`), Tamil (`ta`), Telugu (`te`), etc.

---

## 📦 Installation

```bash
git clone https://github.com/yourusername/vidyai-backend.git
cd vidyai-backend
python -m venv env
source env/bin/activate
pip install -r requirements.txt
