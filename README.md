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
Main Components
Text-to-Speech (TTS): Utilizes pyttsx3 to convert text to speech.
Speech Recognition: Uses SpeechRecognition to recognize user voice commands.
Email Functionality: Sends emails via SMTP using smtplib.
Web Browser Control: Opens specified websites using webbrowser.
Music Playback: Plays music from a defined directory using os.
Sample Commands
"Wikipedia [topic]" - Searches Wikipedia for the specified topic.
"Open YouTube" - Opens YouTube in the default web browser.
"Play music" - Plays the first song in the specified music directory.
"The time" - Tells the current time.
"Email to Bujji" - Sends an email to a specified address.

