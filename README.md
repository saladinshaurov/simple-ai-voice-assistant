# Simple AI Voice Assistant

A lightweight Python voice assistant powered by [ElevenLabs Conversational AI](https://elevenlabs.io/).  
This project demonstrates real-time conversation between a user and an AI agent using ElevenLabs’ streaming API.

---

## Features
- Real-time conversational speech (text-to-speech + microphone input)
- Custom agent prompt and first message
- Modular callback hooks to print agent and user responses
- Secure environment variable handling with `.env`
- Simple and extendable codebase (under 100 lines)

---

## Requirements
- Python 3.9 – 3.13  
- A free [ElevenLabs account](https://elevenlabs.io) and API key  
- macOS/Linux/Windows with PortAudio installed (for `pyaudio`)

---

## Setup

## Clone the repository
```bash
git clone https://github.com/saladinshaurov/simple-ai-voice-assistant.git
cd simple-ai-voice-assistant