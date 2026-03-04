# Ankush AI — Chat Platform

A clean, white/grey AI chat interface with two AI personalities, deployable to Vercel in seconds.

## Features
- 🧑‍💻 **Ankush** — witty, sharp, confident boy personality
- 👩‍🎤 **Tanaya** — warm, empathetic, thoughtful girl personality
- 🔑 API key input bar (stored in localStorage, never sent anywhere except OpenAI)
- ✏️ Custom system prompt editor — override AI behaviour
- 🔔 Sound effects (toggle on/off)
- 💬 Typing indicator, message animations, auto-resize input
- 📱 Fully responsive

## Deploy to Vercel

### Option 1 — Drag & Drop (Fastest)
1. Go to [vercel.com](https://vercel.com) → New Project
2. Drag this entire folder into the upload box
3. Click Deploy — done!

### Option 2 — GitHub + Vercel
1. Push this folder to a GitHub repo
2. Go to [vercel.com](https://vercel.com) → New Project → Import from GitHub
3. Select your repo → Deploy

### Option 3 — Vercel CLI
```bash
npm i -g vercel
vercel deploy
```

## Usage
1. Open your deployed URL
2. Paste your **OpenAI API key** (`sk-...`) in the top bar
3. Choose **Ankush** or **Tanaya**
4. (Optional) Expand **Custom System Prompt** to change the AI's behaviour
5. Start chatting!

## Notes
- Uses `gpt-4o-mini` by default (fast & cheap). Change the `model` field in `index.html` to use `gpt-4o` etc.
- API keys are saved in your browser's `localStorage` — they never leave your browser except to call OpenAI directly.
