Jarvis - Voice Controlled Virtual Assistant

Jarvis is a Python-based virtual assistant that combines voice recognition, text-to-speech, web automation, music playback, and AI-powered conversational capabilities. It responds to voice commands starting with a wake word ("Jarvis") and can perform a variety of tasks like opening websites, playing music, reading the news, and answering general queries using OpenAI's GPT model.

Features:-

1. Voice Activation: Trigger Jarvis with the wake word "Jarvis".
2. Web Navigation: Opens popular websites like Google, YouTube, Facebook, and LinkedIn on voice command.
3. Music Playback: Plays pre-defined YouTube music links via commands like "play skyfall".
4. News Headlines: Reads top headlines using NewsAPI for the latest updates.
5. AI Chatbot Integration: Uses OpenAI's GPT (via openai package) to answer general knowledge or task-based queries.
6. Speech Output: Uses Google Text-to-Speech (gTTS) with Pygame for high-quality audio feedback.


Files Overview

1. Main.py: Core logic for voice recognition, command processing, and AI responses.
2. Client.py: Standalone test script to interact with OpenAI's GPT models.
3. musicLibrary.py: Contains a dictionary mapping song names to YouTube URLs.


Requirements

1. Python 3.7+
2. speechrecognition, pyttsx3, webbrowser, pygame, gtts, requests, openai, pyaudio, pocketsphinx (optional for offline recognition)

