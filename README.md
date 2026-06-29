# 🎙️ Jarvis AI Voice Assistant

<p align="center">

![Python](https://img.shields.io/badge/Python-3.x-blue?style=for-the-badge\&logo=python)
![AI](https://img.shields.io/badge/Google-Gemini-orange?style=for-the-badge\&logo=google)
![Speech Recognition](https://img.shields.io/badge/Speech-Recognition-success?style=for-the-badge)
![Status](https://img.shields.io/badge/Project-Active-brightgreen?style=for-the-badge)

</p>

---

# Table of Contents

* Introduction
* Features
* Project Objectives
* Technologies Used
* Python Modules
* Project Workflow
* Folder Structure
* Installation
* Configuration
* How to Run
* Voice Commands
* Working Principle
* Future Improvements
* Advantages
* Limitations
* Author
* License

---

# Introduction

Jarvis AI Voice Assistant is a Python-based desktop voice assistant capable of recognizing spoken commands and responding with natural voice output. The assistant uses Google's Speech Recognition service for speech-to-text conversion and Google Gemini AI for answering general questions.

The assistant can:

* Listen for a wake word ("Jarvis")
* Open websites
* Play music
* Read latest news headlines
* Answer questions using AI
* Speak responses naturally

This project demonstrates the integration of Artificial Intelligence, Speech Recognition, Text-to-Speech, and Web Automation in Python.

---

# Features

* 🎤 Wake word detection ("Jarvis")
* 🗣️ Voice command recognition
* 🤖 AI-powered responses using Google Gemini
* 🔊 Text-to-Speech output
* 🌐 Open websites instantly
* 🎵 Play songs from a custom music library
* 📰 Read latest news headlines
* 🧩 Modular code structure
* ⚡ Fast command execution

---

# Project Objectives

* Build an intelligent desktop voice assistant.
* Learn Speech Recognition using Python.
* Integrate Google Gemini AI.
* Automate common daily computer tasks.
* Demonstrate AI and Automation concepts.

---

# Technologies Used

| Technology                | Purpose                 |
| ------------------------- | ----------------------- |
| Python                    | Programming Language    |
| Google Speech Recognition | Speech-to-Text          |
| Google Gemini API         | Artificial Intelligence |
| pyttsx3                   | Text-to-Speech          |
| Requests                  | API Communication       |
| Webbrowser                | Open Websites           |
| Threading                 | Voice Synchronization   |

---

# Python Modules Used

| Module             | Description               |
| ------------------ | ------------------------- |
| speech_recognition | Converts voice into text  |
| pyttsx3            | Converts text into speech |
| webbrowser         | Opens websites in browser |
| requests           | Fetches online data       |
| threading          | Prevents speech conflicts |
| google.genai       | Connects with Gemini AI   |
| MusicLibrary       | Stores music links        |
| utility            | Stores website links      |

---

# Project Workflow

```
User Speaks
      │
      ▼
Wake Word Detection
      │
      ▼
Speech Recognition
      │
      ▼
Command Processing
      │
      ├───────────────► Open Website
      │
      ├───────────────► Play Music
      │
      ├───────────────► Read News
      │
      └───────────────► Ask Gemini AI
                           │
                           ▼
                    Generate Response
                           │
                           ▼
                 Text-to-Speech Output
```

---

# Folder Structure

```
Jarvis-AI-Assistant/

│
├── main.py
├── MusicLibrary.py
├── utility.py
├── README.md
├── requirements.txt
└── assets/
```

---

# Installation

Clone the repository

```bash
git clone https://github.com/yourusername/Jarvis-AI-Assistant.git
```

Move into the project folder

```bash
cd Jarvis-AI-Assistant
```

Install dependencies

```bash
pip install -r requirements.txt
```

---

# Requirements

```
speechrecognition

pyttsx3

requests

google-genai

pyaudio
```

Install manually if needed

```bash
pip install SpeechRecognition
pip install pyttsx3
pip install requests
pip install google-genai
pip install pyaudio
```

---

# Configuration

Before running the project, replace the following placeholders:

```python
api_key="YOUR_GEMINI_API_KEY"
```

and

```python
newsapi="YOUR_NEWS_API_KEY"
```

---

# How to Run

```bash
python main.py
```

The assistant initializes and waits for the wake word:

```
Jarvis
```

After activation, it starts listening for your command.

---

# Supported Voice Commands

| Command           | Action                |
| ----------------- | --------------------- |
| Jarvis            | Wake assistant        |
| Open Google       | Opens website         |
| Open YouTube      | Opens website         |
| Play song         | Plays music           |
| News              | Reads latest news     |
| General Questions | Answered by Gemini AI |

---

# Working Principle

1. Initialize microphone.
2. Wait for wake word.
3. Convert speech into text.
4. Process command.
5. Execute predefined tasks.
6. Send unknown queries to Gemini AI.
7. Convert response into speech.
8. Wait for next command.

---

# Advantages

* Easy to use
* AI-powered responses
* Hands-free interaction
* Modular architecture
* Lightweight
* Beginner-friendly
* Expandable

---

# Limitations

* Requires internet for AI and News.
* Uses predefined commands.
* Background noise may reduce accuracy.
* Limited offline functionality.

---

# Future Improvements

* GUI Interface
* Weather Updates
* Email Sending
* WhatsApp Automation
* Smart Home Integration
* Voice Authentication
* System Controls
* Calendar Integration
* Face Recognition
* Chat Memory
* Multi-language Support

---

# Project Highlights

* Speech Recognition
* AI Integration
* Natural Voice Output
* Website Automation
* Music Playback
* News Reader
* Python Automation
* Modular Design

---

# Author

**Abhiraj Patel**

Python Developer | AI Enthusiast

---

# License

This project is licensed under the MIT License.

---

# Acknowledgements

* Google Gemini API
* SpeechRecognition Library
* pyttsx3
* Python Community
* Open Source Contributors

---

## ⭐ If you found this project useful, consider giving it a Star on GitHub!
