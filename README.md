

# 🗣️ Telegram Voice Agent

Your very own **AI-powered Voice Assistant** on **Telegram** 🎙
This project lets you chat with an intelligent Telegram bot that can **listen, understand, and talk back** — just like a real person.
Using **n8n**, **ElevenLabs**, and **OpenRouter AI**, you can create a personal assistant that handles **voice and text conversations** naturally.

---

## 🚀 Features

* 🎧 **Voice-to-Text & Text-to-Voice** communication
* 🤖 **AI-generated smart and human-like replies**
* 💬 Works directly inside **Telegram**
* 🧠 **Memory support** for contextual conversations
* 🔗 Seamless integration with **n8n**, **ElevenLabs**, and **OpenRouter**
* ⚙️ **No heavy coding required** — just workflow automation

---

## 🧩 Prerequisites

Before getting started, ensure you have:

* A **Telegram account**
* Access to [BotFather](https://telegram.me/BotFather) (to create your bot)
* An [n8n](https://n8n.io) account
* API key from [ElevenLabs](https://elevenlabs.io)
* API key from [OpenRouter](https://openrouter.ai)
* Basic familiarity with n8n nodes and workflows

---

## ⚙️ Setup Instructions

To build and configure your Voice Agent (including bot creation, n8n workflow setup, and AI integration),
please follow the detailed step-by-step guide in the provided PDF:

📘 **[Voice_Agent.pdf](./Voice_Agent.pdf)**

The PDF includes complete instructions on:

* Creating your **Telegram bot** using BotFather
* Setting up **Telegram Trigger**, **Get File**, and **Send Audio** nodes in n8n
* Connecting **ElevenLabs** for speech transcription and generation
* Integrating **AI Agent** with **OpenRouter** for intelligent responses
* Adding **Simple Memory** for context-based replies
* Sending both text and audio responses back to the user

---

## 🧠 Workflow Overview

1. **Telegram Trigger Node** → Receives messages (voice/text)
2. **Get File Node** → Fetches voice messages from Telegram
3. **ElevenLabs Node (Speech-to-Text)** → Converts voice to text
4. **AI Agent Node (OpenRouter)** → Generates intelligent replies
5. **Simple Memory Node** → Maintains conversational context
6. **ElevenLabs Node (Text-to-Speech)** → Converts reply into voice
7. **Send Audio Node** → Sends AI-generated voice reply to user

---

## 🗨️ Example Conversation

```
User: (sends a voice message) “What’s the weather like today?”
Bot: (responds with audio) “It’s a sunny 28°C today — perfect for a walk outside!”
```

---

## ✅ Summary

With this setup, you’ve built your own **Telegram Voice Assistant** capable of:

* Listening to your voice
* Understanding natural language
* Thinking using advanced AI
* Speaking back with human-like tones

You now have a **fully functional conversational AI** — running entirely within **Telegram** and powered by **n8n automation**.

---



## 🧩 Future Enhancements

* Add **custom voices** or emotional tones via ElevenLabs
* Integrate **Google Gemini** or **OpenAI GPT models**
* Enable **multi-language** support
* Store chat history in Notion or Google Sheets




