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

Telegram Trigger → AI Agent → Send Telegram Message

AI Agent uses:
- OpenRouter Chat Model
- Simple Memory

### Error Handler Workflow

Error Trigger → Send Telegram Message

The Error Handler workflow sends a notification when an error occurs in the main translation workflow.

## 💬 Example

**User:** hava güneşli. almancaya çevir

**Bot:** Die Sonne scheint.

The bot can also continue the conversation using previous messages.

**User:** Bugün hava çok güzel.

**User:** Almanca

**Bot:** Heute ist das Wetter sehr schön.

## 📂 Project Files

- `Telegram translation workflow.json` — Main translation workflow
- `Telegram Translator - Error Handler.json` — Error handling workflow

## 🔐 Setup

1. Import the main workflow JSON file into n8n.
2. Import the Error Handler workflow.
3. Create your Telegram credentials.
4. Configure your OpenRouter credentials.
5. Select an available OpenRouter model.
6. Activate/publish the workflows.

> **Note:** API keys, bot tokens, and other sensitive credentials should never be uploaded to GitHub.

## 👩‍💻 Author

**Şeymanur Sayıt**

This project was created as a practical AI automation project using n8n and Telegram.
