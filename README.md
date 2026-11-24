# 🤖 jan-bangla

[![Offline AI](https://img.shields.io/badge/type-offline%20ai%20chat-blue)](https://github.com/tunnabri-ops/jan-bangla)
[![Language](https://img.shields.io/badge/UI-Bangla-orange)](https://github.com/tunnabri-ops/jan-bangla)

**Offline Bangla AI chat with local models — no cloud, no key, your chats stay on your machine.**

> বাংলা সংস্করণ নিচে আছে। / Bangla version below.

## ✨ Features

- **Small-model presets** in `models.json` (for low-end phones and PCs):
  - Qwen2.5 3B Q4_K_M — ~2 GB, Bangla chat, fast on 8 GB RAM
  - Qwen2.5 7B Q4_K_M — ~4.7 GB, better Bangla, needs 8 GB+ RAM
  - Qwen3 4B Q4_K_M — ~2.6 GB, newer, good Bangla reasoning
- **Local server** — `http://localhost:1337`, OpenAI-compatible
- **Bangla system prompt** in `bangla-prompts.md` — answers always in clear Bangla, short sentences, with examples

## 🚀 How to use

1. Download a model from the app's model hub (see the preset list in `models.json`).
2. Set the Bangla system prompt from `bangla-prompts.md`.
3. Chat offline — the model runs on your own machine.

## ⚠️ Honest limits

- **8 GB RAM minimum** for the desktop app.
- The app is desktop-only today — a mobile PWA / lightweight web UI is still to come.
- A one-click preset downloader for the 3–4B models is still to come.

## 🇧🇩 বাংলা

**জান বাংলা — ইন্টারনেট ছাড়াই বাংলায় AI চ্যাট।**

- ছোট মডেল (Qwen2.5 / Qwen3 3–4B) নামিয়ে নিজের কম্পিউটারে চালান
- `bangla-prompts.md`-এর বাংলা সিস্টেম প্রম্পট ব্যবহার করুন — উত্তর সবসময় পরিষ্কার বাংলায় আসবে

## 📄 License

MIT — use it however you like; credit is appreciated.
