# VoiceBox

[![GitHub stars](https://img.shields.io/github/stars/ibrahimrifats/voiceBox?style=social)](https://github.com/ibrahimrifats/voiceBox/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/ibrahimrifats/voiceBox?style=social)](https://github.com/ibrahimrifats/voiceBox/network/members)
[![GitHub issues](https://img.shields.io/github/issues/ibrahimrifats/voiceBox)](https://github.com/ibrahimrifats/voiceBox/issues)
[![GitHub license](https://img.shields.io/github/license/ibrahimrifats/voiceBox)](LICENSE)

---

## Overview  
**VoiceBox** is a hybrid **Voice + Chat interaction system** that integrates **Google Colab, FastAPI, and Local VS Code** into a single pipeline.  

- Speech-to-Text (STT)  
- Text-to-Speech (TTS)  
- Real-time API communication between Colab runtime and local development environment  

---

## Screenshots  

| Voice | Chat |
|-------------|-------------|
| <img width="1915" height="888" alt="image" src="https://github.com/user-attachments/assets/5238f61b-d911-4af4-b1be-b7b038183877" /> | <img width="369" height="792" alt="image" src="https://github.com/user-attachments/assets/6232596d-051d-4587-93ae-fbc6e86771d5" /> |

---

## System Components  

### Colab – Chatterbox  
- Provides **Text-to-Voice generation**  
- Runs with **FastAPI inside Colab**  

### FastAPI (Colab Runtime)  
- Exposes endpoints for **Voice-to-Text** and **Text-to-Voice**  
- Handles requests inside Colab environment  
- Sends responses to local VS Code project  

### Local Project (VS Code)  
- Connects to the Colab FastAPI server  
- Processes API responses  
- Implements MCP (Message Control Protocol) for:  
  - Confirm booking  
  - Cancel booking  
  - Answer user requests  

---

## Architecture  


### Low-Level Architecture  

| Low-Level Architecture |
|-------------------------|
| <img width="1182" height="441" alt="Group 6" src="https://github.com/user-attachments/assets/71a5dd1e-ccce-43b3-a4d9-bb746ec2b7fe" /> |



---

## Tech Stack  
- Python  
- FastAPI  
- Whisper / Speech APIs (STT)  
- Chatterbox / gTTS / ElevenLabs (TTS)  
- Google Colab  
- VS Code  
- MCP (Message Control Protocol)  

---

## Getting Started  

### 1. Clone Repository  
```bash
git clone https://github.com/your-username/voiceBox.git
cd voiceBox





