# Telegram Translation Bot 🌍

An AI-powered Telegram translation bot built with **n8n**, **Telegram**, **OpenRouter**, and **AI Agent**.

The bot can translate messages into the requested language, remember previous messages using memory, and handle missing information or workflow errors.

## 🚀 Features

- 🌍 AI-powered text translation
- 🤖 Telegram bot integration
- 🧠 AI Agent with Simple Memory
- 💬 Conversational translation
- 🔄 Remembers previous messages
- ⚠️ Error handling workflow
- 👋 `/start` welcome message
- 🔎 Detects missing text or target language

## 🛠️ Technologies

- n8n
- Telegram Bot API
- OpenRouter
- AI Agent
- Simple Memory
- GitHub

## 🔄 Workflow

### Main Translation Workflow

```text
Telegram Trigger
       ↓
    AI Agent
     ↙    ↘
Chat Model  Simple Memory
       ↓
Send Telegram Message
-----------------------------

### Error Handler Workflow
Error Trigger
      ↓
Send Telegram Message
