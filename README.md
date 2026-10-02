# 🤖 AI Chatbot Interface

A clean, modern, client-side chat interface for Google's Gemini 2.0 Flash model — no backend, no login, just open the page, paste your Gemini API key, and start chatting. Single `index.html`, works anywhere static hosting works.

## ✨ Features

- **Chat with Gemini 2.0 Flash** — bring your own API key (stored in your browser only, never sent anywhere else)
- **Rich message rendering** — Markdown (via Marked.js), math (KaTeX), syntax highlighting (Highlight.js)
- **Dark / light theme** — toggle with one click, preference persisted in localStorage
- **Chat history** — previous conversations saved locally in the browser, start new chats anytime
- **Typing indicator** — animated feedback while the model responds
- **Suggested prompts** — quick-start suggestions on the landing view
- **Attachments** — attach files/images to your prompts via the attachment modal
- **Responsive design** — Tailwind CSS, works on desktop and mobile

## 🛠 Tech Stack

- Plain HTML, CSS, JavaScript (single-file app)
- Tailwind CSS (CDN)
- Marked.js — Markdown rendering
- KaTeX — math/typesetting rendering
- Highlight.js — code syntax highlighting
- Gemini API (`generativelanguage.googleapis.com/v1beta/models/gemini-2.0-flash`)

## 🚀 Quick Start

1. Clone or download this repo.
2. Open `index.html` in any modern browser — or serve it with any static server:
   ```bash
   npx serve .
   ```
3. Paste your free Gemini API key ([get one from Google AI Studio](https://aistudio.google.com/app/apikey)) when prompted.
4. Start chatting.

No build step, no dependencies to install, no backend.

## 📁 Project Structure

```
AI-Chatbot-Interface/
└── index.html   # the entire app — UI, styling, and chat logic
```

## 🔑 API Key

The app requires a Gemini API key, entered in the UI. The key is stored in your browser's localStorage only — this project has no server and cannot see or collect it.

## 🌐 Live Demo

Deployed on GitHub Pages: https://girishlade111.github.io/AI-Chatbot-Interface/

---

Built by Girish Lade — [ladestack.in](https://ladestack.in) | [GitHub](https://github.com/girishlade111)
