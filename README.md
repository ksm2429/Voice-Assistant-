# Voice Assistant - Atkinson

A simple AI voice assistant built with Python that can perform various tasks like searching Wikipedia, sending emails, and playing music.

## Features

- Voice recognition and speech synthesis
- Search Wikipedia for information
- Open websites (YouTube, Google, Stack Overflow)
- Play music from a specified directory
- Retrieve the current time
- Open Visual Studio Code
- Send emails using SMTP

## Installation

pip install pyttsx3
pip install SpeechRecognition
pip install wikipedia

### Prerequisites

- Python 3.x
- Pip (Python package installer)

### Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/ksm2429/Voice-Assistant.git
   cd Voice-Assistant

2. Install the required packages:
   ```bash
   pip install pyttsx3
   pip install SpeechRecognition
   pip install wikipedia

## Main Components
1) Text-to-Speech (TTS): Utilizes pyttsx3 to convert text to speech.
2) Speech Recognition: Uses SpeechRecognition to recognize user voice commands.
3) Email Functionality: Sends emails via SMTP using smtplib.
4) Web Browser Control: Opens specified websites using webbrowser.
5) Music Playback: Plays music from a defined directory using os.
### Sample Commands:
- "Wikipedia [topic]" - Searches Wikipedia for the specified topic.
- "Open YouTube" - Opens YouTube in the default web browser.
- "Play music" - Plays the first song in the specified music directory.
- "The time" - Tells the current time.
- "Email to Bujji" - Sends an email to a specified address.

