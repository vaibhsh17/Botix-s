<div align="center">

# **Botix-S**
### Simple, customizable, and Easy-to-Use Discord chatbot.

![Progress](https://img.shields.io/badge/Progress-Working-brightgreen)
![Documentation Status](https://img.shields.io/badge/Docs-Maintained-blue)
![Version](https://img.shields.io/badge/Version-0.1.0-orange)
![Python](https://img.shields.io/badge/Language-Python-blue)
![Discord](https://img.shields.io/badge/Platform-Discord-5865F2)
</div>

---
<div align="center">

## 📌 About
</div>

- **Botix-S** is a lightweight Discord chatbot to automate coversations using predefined questions and answers.
- It follows a simple approach: questions and answers are storedin a structured JSON file, allowing responses to be customized without changing the main chatbot logic.
- The project aims to provide a beginner-friendly foundation for Discord bot development while gradually envolving toward a more flexible and customizable chatbot system.

<div align="center">

## 🚀 Current Progress
</div>

- The current version of Botix-S focuses on establishing a working Discord chatbot and maintaining a simple, understandable codebase.

**Implemented so far**:

- Discord bot creation and integration.
- Discord API communication through discord.py.
- Automatic message recieving and response handling.
- JSON-based question-and-answer storage.
- Question matching and automated replies.
- Secure bot token management using enviourment variables.
- Modular Python project structure.
- Discord Message Content Intent Configuration.
- Git and Github version control.
- Improvements to response loading and message matching.

<div align="center">

## ⚙️ How Botix-S Works
</div>

Botix-S follows a straightforward response-based architecture.
```
Discord User
             |
             v
       User Message
             |
             v
          Botix-S
             |
             v
       responses.json
             |
             v
      Question Matching
             |
             v
       Matching Answer
             |
             v
```
When a user sends a message in a Discord channel:

1. Botix-S recieves the message through the Discord Gateway.
2. The message is checked against the stored questions.
3. A matching question is identified.
4. The corresponding answer is sent to the Discord channel.

**important**: Botix-S only respond to questions for which predefined answers  are saved in data/responses.json. It does not currently generate independent  AI-based answers.

<div align="center">

## ✨ Core Features
</div>

<div align="center">

## 📂 Project Structure
</div>

```
Botix-S/
│
├── data/
│   └── responses.json
│
├── src/
│   └── bot.py
│
├── .env
├── .gitignore
├── requirements.txt
└── README.md
```

<div align="center">

## 🛠️ Technologies Used
</div>

Technology | Purpose
-
Python | Core Programming Language
discord.py | Python library for Discord integration
Discord API | Communication with Discord
JSON | Question-and-Answer storage
python-dotenv | Enviourment variable management
