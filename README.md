# Voice Chatbot (Python)

A voice-enabled chatbot built in Python that combines speech recognition, text-to-speech, and a pretrained conversational language model to support spoken user interaction.

## Overview

This project explores a simple voice-based conversational interface using Python. It captures spoken input, converts it to text, generates a response using DialoGPT, and returns the response using text-to-speech.

## Features

- Speech-to-text input using SpeechRecognition
- Text-to-speech output using pyttsx3
- Conversational response generation using DialoGPT
- Simple Python-based architecture for experimentation and extension

## Tech Stack

- Python
- SpeechRecognition
- pyttsx3
- PyAudio
- NumPy
- PyTorch
- Hugging Face Transformers / DialoGPT

## Project Purpose

This project was created to explore conversational AI in a voice-based interface and to gain hands-on experience with speech processing, chatbot workflows, and Python application development.

## Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/mgc-00/voice-chatbot-python.git
Move into the project directory:

bash
cd voice-chatbot-python
Install dependencies:

bash
pip install -r requirements.txt
Run the chatbot:

bash
python voice_chatbot.py

Notes
Installing audio-related dependencies such as PyAudio may require additional platform-specific steps depending on your operating system and Python environment.
Initial model loading may take some time before the chatbot is ready for interaction.

Future Improvements
Improve conversation flow and response quality
Add better session memory and context handling
Expand voice and UI options
Improve setup compatibility across environments
