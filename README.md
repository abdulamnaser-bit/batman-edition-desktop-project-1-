# 🦇 26AI — Batman Window Shell

> **A futuristic Batman-inspired Windows desktop shell powered by 26AI.**

26AI Batman Window Shell is a personal desktop customization project designed to transform the traditional Windows desktop experience into a futuristic, immersive **Batman-inspired AI workstation**.

The project combines a custom graphical interface, HUD-style visual elements, application launching, system controls, and AI-assistant integration into a unified desktop environment.

---

## 🧠 Project Overview

The goal of this project is to create a personalized Windows environment that feels more like a futuristic command center rather than a traditional desktop.

The system is designed around **26**, my personal AI assistant, with the **Friday voice engine** working behind the assistant.

The interface focuses on:

* 🦇 Batman-inspired visual design
* 🤖 AI assistant integration
* 🖥️ Custom Windows shell experience
* 🎯 HUD-style interface
* 🎙️ Voice interaction
* 🚀 Application launching
* ⚙️ System controls
* 🔍 Application search
* 📊 Real-time visual feedback

---

## ✨ Features

### 🦇 Batman-Inspired Interface

A dark futuristic interface inspired by Batman's technology and command-center aesthetics.

### 🤖 26AI Integration

The desktop environment is designed around my personal AI assistant **26**, which acts as the central AI interface.

### 🎙️ Voice Assistant

The **Friday voice engine** provides voice interaction for the assistant.

The intended architecture is:

```text
User Voice
     ↓
Speech Recognition
     ↓
26AI
     ↓
LLM / Command Processing
     ↓
System Action
     ↓
HUD Feedback
```

### 🖥️ Custom HUD

The project includes a custom **Heads-Up Display (HUD)** designed to provide information and system feedback without relying entirely on the standard Windows interface.

### 🔍 Application Search

A custom search interface allows applications to be located and launched from the shell.

### 🚀 Application Launcher

The system can detect installed applications and provide a centralized interface for launching them.

### ⚙️ System Controls

The interface is designed to provide quick access to commonly used Windows functions and system controls.

---

## 🛠️ Technologies

| Technology              | Purpose                                      |
| ----------------------- | -------------------------------------------- |
| Python                  | Core application logic                       |
| PySide6 / PyQt6         | GUI and HUD development                      |
| Ollama                  | Local LLM integration                        |
| LLM                     | Natural-language understanding and reasoning |
| Speech Recognition      | Voice input                                  |
| Piper TTS               | Voice output                                 |
| Windows APIs / Commands | System interaction                           |

---

## 🏗️ Architecture

```text
                    ┌──────────────────┐
                    │      USER        │
                    │ Voice / Keyboard │
                    └────────┬─────────┘
                             │
                             ▼
                    ┌──────────────────┐
                    │   26AI INTERFACE │
                    │    GUI / HUD     │
                    └────────┬─────────┘
                             │
                ┌────────────┴────────────┐
                │                         │
                ▼                         ▼
       ┌─────────────────┐       ┌─────────────────┐
       │ Speech / Voice  │       │ Keyboard / GUI  │
       │    Processing   │       │     Input       │
       └────────┬────────┘       └────────┬────────┘
                │                         │
                └────────────┬────────────┘
                             ▼
                    ┌──────────────────┐
                    │   26AI CORE      │
                    │ Command Handling │
                    └────────┬─────────┘
                             │
                             ▼
                    ┌──────────────────┐
                    │ Ollama + Local   │
                    │      LLM         │
                    └────────┬─────────┘
                             │
                             ▼
                    ┌──────────────────┐
                    │ Command / Action │
                    │    Processing    │
                    └────────┬─────────┘
                             │
              ┌──────────────┼──────────────┐
              ▼              ▼              ▼
          Applications    Windows       System
           Launcher       Commands      Controls
              │              │              │
              └──────────────┼──────────────┘
                             ▼
                    ┌──────────────────┐
                    │   HUD RESPONSE   │
                    │ Visual Feedback  │
                    └──────────────────┘
```

---

## 🎯 Project Goals

The main objectives of the project are:

1. Build a personalized Windows desktop environment.
2. Create a futuristic Batman-inspired interface.
3. Integrate an AI assistant directly into the desktop experience.
4. Enable voice-based computer interaction.
5. Explore local LLM integration using Ollama.
6. Develop practical AI + GUI + system automation skills.
7. Create a unique portfolio project demonstrating AIML and software-development capabilities.

---

## 📁 Project Structure

The exact structure may change as development continues, but the project is organized around components such as:

```text
26AI-Batman-Shell/
│
├── 26AI/
│   ├── core/
│   ├── voice/
│   ├── commands/
│   └── llm/
│
├── hud/
│   ├── interface/
│   ├── widgets/
│   └── animations/
│
├── launcher/
│   └── applications/
│
├── system/
│   └── controls/
│
├── assets/
│
├── requirements.txt
├── README.md
└── main.py
```

---

## 🧪 Current Development Status

**Status:** 🚧 Active Development

The project is continuously evolving.

Planned improvements may include:

* More advanced HUD animations
* Improved voice interaction
* Better application detection
* More Windows system controls
* AI-powered application search
* Context-aware commands
* Improved Ollama/LLM integration
* Custom Batman-style system panels
* Better performance optimization
* Additional personalization features

---

## ⚠️ Important Notice

This project is a **personal portfolio and educational project**.

The repository may contain only selected portions of the complete project. Certain implementation details, configurations, assets, or proprietary components may not be publicly included.

---

## 📜 Copyright & Usage

**Copyright © 2026 Abdul Naser. All rights reserved.**

This repository is provided for **educational and portfolio viewing purposes**.

The source code, architecture, documentation, designs, and original project materials contained in this repository may not be:

* Reused
* Redistributed
* Republished
* Modified and republished
* Incorporated into another project
* Used for commercial purposes

without prior permission from the author.

Forking or copying this repository does not transfer ownership or authorship of the original work.

For permission regarding reuse or other forms of distribution, please contact the author.

---

## 👨‍💻 Author

**Abdul Naser**

AIML Student | AI/ML Developer | Generative AI Enthusiast

This project was created as part of my personal exploration of:

* Artificial Intelligence
* Machine Learning
* Generative AI
* Large Language Models
* Natural Language Processing
* Python
* GUI Development
* Windows Automation
* Human-Computer Interaction

---

## 🦇 Project Philosophy

> **"Don't just use the computer. Build the system you want to use."**

26AI Batman Window Shell is an ongoing experiment in combining **AI, software engineering, interface design, and automation** to create a personalized computing environment.

---

**© 2026 Abdul Naser — All Rights Reserved.**

