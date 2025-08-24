# NOVA – Voice-Based Intelligent Personal Assistant

NOVA is a Python-based personal assistant that takes voice commands and performs tasks like opening applications, searching the web, fetching weather updates, sending emails, and more. The goal was to build something lightweight and extensible, with core features that also work offline.

✨ Key Features

Voice to text using speech_recognition

Text to speech with pyttsx3

Can open apps, search Google/Wikipedia/YouTube, and fetch weather info

Simple email support through SMTP

Modular design so that new commands can be added easily

Works offline for basic commands (opening apps, TTS, file management)

🛠 Tech Stack

Python 3.9+

Libraries: speech_recognition, pyttsx3, wikipedia, pywhatkit, requests, smtplib, os, subprocess

⚡ Getting Started

Clone the repository and install the required libraries:
git clone https://github.com/<your-username>/nova-ai-assistant.git
cd nova-ai-assistant
pip install -r requirements.txt

Run the program:
python main.py


