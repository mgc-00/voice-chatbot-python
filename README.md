# Voice Chatbot (Python)

A voice-enabled chatbot built in Python that combines speech recognition, text-to-speech, and a pretrained conversational language model to support spoken user interaction.

## Overview

This project explores a simple voice-based conversational interface using Python. It captures spoken input, converts it to text, generates a response using DialoGPT, and returns the response using text-to-speech.

## Features

- Speech-to-text input using speech recognition
- Text-to-speech output for spoken responses
- Conversational response generation using DialoGPT
- Simple Python-based architecture for experimentation and extension

## Tech Stack

- Python
- SpeechRecognition
- pyttsx3
- PyAudio
- Hugging Face Transformers / DialoGPT

## Project Purpose

This project was created to explore conversational AI in a voice-based interface and to gain hands-on experience with speech processing, chatbot workflows, and Python application development.

## Setup

Clone the repository:
   ```bash
   git clone https://github.com/mgc-00/voice-chatbot-python.git

pip install -r requirements.txt
   cd voice-chatbot-python

python voice_chatbot.py

Notes
Depending on your environment, installing audio-related dependencies such as PyAudio may require additional platform-specific steps.
Initial model loading may take some time before the chatbot is ready for interaction.

Future Improvements
Improve conversation flow and response quality
Add better session memory and context handling
Expand voice and UI options
Improve setup compatibility across environments

