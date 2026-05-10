# 🧠 EchoMind // AI Digital Twin

![Version](https://img.shields.io/badge/Version-1.0.0-8A2BE2?style=for-the-badge)
![AI](https://img.shields.io/badge/AI-Gemini_1.5_Flash-00C2FF?style=for-the-badge&logo=googlebard)
![Frontend](https://img.shields.io/badge/Frontend-HTML%20%7C%20CSS%20%7C%20JS-121212?style=for-the-badge)
![Backend](https://img.shields.io/badge/Backend-FastAPI-009688?style=for-the-badge&logo=fastapi)

> 🚀 An AI-powered Digital Twin that transforms a developer portfolio into a real-time interactive experience.

---

# 🌌 Overview

**EchoMind** is an immersive AI Digital Twin platform built to represent a developer’s technical identity, projects, engineering mindset, and professional journey through conversational AI.

Instead of browsing static resumes or portfolios, recruiters, collaborators, and developers can directly interact with an intelligent AI twin trained on:

- GitHub repositories
- Technical projects
- Skills & experience
- Engineering philosophy
- Portfolio context

EchoMind combines:
- 🧠 LLM-powered conversations
- 🎤 Voice interaction
- ⚡ Real-time AI responses
- 📊 Dynamic UI visualizations
- 🖥️ Futuristic neural interface

into a next-generation developer portfolio experience.

---
## Preview

<img width="1907" height="898" alt="image" src="https://github.com/user-attachments/assets/5f89f4b6-ee60-4a65-8d6f-c82d00f06c03" />

<br/>

<img width="1897" height="898" alt="image" src="https://github.com/user-attachments/assets/54af18c8-2679-4320-9b94-60fa386b5eb3" />

### What EchoMind Does
- Acts as an AI-powered digital twin of a developer
- Answers recruiter and technical questions contextually
- Uses RAG + GitHub project analysis
- Supports HR and Tech Lead interaction modes
- Includes voice-based AI interaction

---

# ✨ Features

## 🧠 AI Digital Twin

- Interactive AI representation of a developer
- Context-aware responses powered by Gemini
- Adaptive conversational behavior
- Recruiter-style and Tech Lead-style interaction modes

---

## 🎭 Persona Protocol Modes

### 👨‍💼 HR Mode
- Friendly & professional responses
- Communication-focused
- Teamwork & soft-skill oriented

### 🧑‍💻 Tech Lead Mode
- Deep technical discussions
- Architecture-focused analysis
- Engineering-critical responses

---

## 🎚️ Experience Simulation Engine

Dynamically simulate different experience levels:

- Junior Developer
- Mid-Level Engineer
- Senior Engineer
- CTO Perspective

The AI changes response complexity based on the selected level.

---

## 🎤 Voice Interaction

### Speech-to-Text
- Real-time voice input using Web Speech API

### Text-to-Speech
- Browser-native AI voice playback
- No paid APIs required
- Fully free voice interaction system

---

## 📊 GitHub Intelligence Engine

EchoMind analyzes real GitHub repositories and project metadata to ground AI responses in actual development work.

### Includes:
- Repository analysis
- Language detection
- Tech stack extraction
- Project indexing
- Dynamic profile generation

---

## 🖥️ Futuristic Neural Interface

### Features:
- Cyberpunk-inspired HUD
- AI Core visualization
- Live terminal stream
- Animated neural effects
- Real-time system metrics
- Responsive UI design

---

## 📄 AI Report Generator

Generate downloadable technical assessment reports based on conversations.

The system can:
- Analyze discussions
- Evaluate technical depth
- Generate AI-assisted summaries
- Produce recruiter-style reports

---

## 🛡️ AI Safety Layer

- Prompt injection detection
- Defensive AI responses
- Secure conversational handling
- Identity grounding

---

# ⚙️ Tech Stack

## Frontend
- HTML5
- CSS3
- Vanilla JavaScript
- Mermaid.js
- Marked.js

## Backend
- Python
- FastAPI
- Uvicorn

## AI
- Google Gemini 3 Flash
- Prompt Engineering
- Hybrid RAG Architecture

## Voice
- Web Speech API
- Browser Speech Synthesis

---


## 📥 Getting Started

### Prerequisites
* **System:** Python 3.10+ or Docker installed.
* *(Optional)*: A GitHub Token (if you want the agent to read your repositories live).

### 1. Clone the repository
```bash
git clone https://github.com/Maa8nya/EchoMind-digital-twin.git
cd source-persona
```

### 2. Configuration

Create a `.env` file and add your keys:
```bash
GITHUB_TOKEN=your_token_here
GEMINI_API_KEY=your_api_key_here
```

### 3. Prepare Memory (RAG)

-   Place your **resume.pdf** in `backend/data/`.

-   Run the sync tool to fetch your latest GitHub data:

```bash
python backend/app/services/github_sync.py
```

*Note: The sync tool will create a `data` folder in the root directory.*

### 4. Run the Application

You can run the digital twin using **Python** (for development).


#### Run Locally (Python)

Useful for code inspection and rapid development.

```bash
# 1. Install dependencies
pip install -r requirements.txt

# 2. Start the server
python backend/app/main.py
```

*Visit `http://localhost:3000` to interact with the EchoMind.*


