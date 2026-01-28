# ⚡ Lightning Classroom Coach Lite

> **Expression & Thought Organizer for Students** — Help organize your ideas into speakable short sentences in 10-20 seconds.

[![GitHub Pages](https://img.shields.io/badge/demo-GitHub%20Pages-blue)](https://yourusername.github.io/lightning-classroom-coach)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![iPad Optimized](https://img.shields.io/badge/iPad-Optimized-black?logo=apple)](https://www.apple.com/ipad/)

## 🎯 What is this?

Lightning Classroom Coach is a **thought organization tool** (not a cheating tool!) designed to help students:

- Quickly structure their ideas into **speakable sentences**
- Generate **SAFE**, **STRONG**, and **SMART QUESTION** response options
- Practice expressing ideas in American classroom style

**Perfect for:** International students, ESL learners, or anyone who needs help formulating quick classroom responses.

## 📱 iPad Optimized

This app is specifically optimized for **Apple iPad** classroom use:

| Feature | Implementation |
|---------|----------------|
| 🎯 **Touch Targets** | All buttons ≥ 44pt (Apple HIG compliant) |
| 📏 **Safe Area** | Supports notch & home indicator |
| 🚫 **No Zoom** | Prevents accidental double-tap zoom |
| ⬇️ **No Pull-to-Refresh** | Prevents accidental refresh |
| ⌨️ **Keyboard Handling** | Auto-scroll when keyboard opens |
| 🌙 **Dark Theme** | Low-key design for classroom discretion |
| 📲 **PWA Ready** | Add to Home Screen for app-like experience |
| 🔊 **iOS Voices** | Uses native iOS speech synthesis |

### Add to iPad Home Screen

1. Open in Safari
2. Tap **Share** button (⬆️)
3. Select **"Add to Home Screen"**
4. Now it works like a native app!

## ✨ Features

| Feature | Description |
|---------|-------------|
| 🚀 **Instant Draft** | Template-based response in <300ms |
| 🔄 **AI Upgrade** | OpenAI streaming for polished output |
| 📱 **iPad Optimized** | Big buttons, dark theme, touch-friendly |
| 🎤 **Text-to-Speech** | Practice pronunciation with iOS voices |
| 📋 **One-Click Copy** | Copy any response instantly |
| 🔒 **Privacy First** | API key stored locally, no server |

## 🖥️ Demo

**Live Demo:** [https://yourusername.github.io/lightning-classroom-coach](https://yourusername.github.io/lightning-classroom-coach)

Or simply download `index.html` and open in any browser.

## 📖 Usage

### Quick Start (No API Key Needed)

1. Open the app in your browser
2. Type keywords or paste your question
3. Press **Enter** or click **⚡ Quick** → Get instant template response

### With OpenAI API (Better Quality)

1. Click ⚙️ Settings
2. Select **OpenAI** as provider
3. Enter your [OpenAI API Key](https://platform.openai.com/api-keys)
4. Choose model (GPT-5.2 Instant recommended for speed)
5. Type your question and press **Enter**

### Keyboard Shortcuts

| Shortcut | Action |
|----------|--------|
| `Enter` | Quick generate |
| `Ctrl/Cmd + Enter` | Polished generate |
| `Esc` | Stop generation |

## 📤 Output Format

The app generates 4 types of responses:

- **🛡️ SAFE** — Low-risk, polite response (≤35 words)
- **💪 STRONG** — Opinionated but safe response (≤35 words)
- **❓ QUESTION** — Smart follow-up question (≤35 words)
- **📝 NOTES** — Key study points (2-5 bullets)

## 🔧 Configuration

### Using a Proxy (CORS Issues)

If you encounter CORS errors, you can use a proxy:

1. Open Settings ⚙️
2. Change **API Endpoint** to your proxy URL
3. Example: `https://your-proxy.com/v1/responses`

### Supported Models (January 2026)

| Model | Best For |
|-------|----------|
| `gpt-4o` | **Recommended** - stable, reliable |
| `gpt-4o-mini` | Fast & cheap, simple tasks |
| `gpt-4.1` | General purpose (2025) |
| `gpt-4.1-mini` | Fast version (2025) |
| `gpt-5.2` | Most powerful, reasoning |
| `gpt-5.2-chat-latest` | Fast GPT-5.2 responses |

> ⚠️ **Important**: This app uses the **Chat Completions API** (`/v1/chat/completions`), which works with standard API keys. Models like `gpt-5.2-pro` require organization verification and are not supported.

## 🛡️ Privacy & Compliance

- ✅ **No server** — Everything runs in your browser
- ✅ **No tracking** — No analytics or telemetry
- ✅ **Local storage only** — API key stored on your device
- ✅ **No audio recording** — TTS uses browser's built-in speech synthesis

## 📁 File Structure

```
lightning-classroom-coach/
├── index.html    # Main application (single file)
├── README.md     # This file
└── LICENSE       # MIT License
```

## 🚀 Deploy to GitHub Pages

1. Fork this repository
2. Go to **Settings** → **Pages**
3. Set source to **main branch** / **root**
4. Your app will be live at `https://yourusername.github.io/lightning-classroom-coach`

## 📝 License

MIT License — feel free to use, modify, and distribute.

## 🙏 Acknowledgments

- Built with vanilla HTML/CSS/JS (no frameworks)
- Powered by [OpenAI API](https://platform.openai.com/)
- Designed for iPad classroom use

---

**⚠️ Disclaimer:** This tool is designed to help students **organize their own thoughts**, not to generate answers for them. Use responsibly and ethically in academic settings.
