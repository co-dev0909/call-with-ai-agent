# 🧠 Call with AI Agent

A voice-interactive web UI built with **Next.js** and **ElevenLabs**, enabling real-time conversations with an ElevenLabs agent. Users can start and stop a session, and visually observe when the agent is speaking or listening through animated button feedback.

- 🔗 GitHub: [github.com/aimaster-dev/call-with-ai-agent](https://github.com/aimaster-dev/call-with-ai-agent)
- 🌐 Live Demo: [call-with-ai-agent.vercel.app](https://call-with-ai-agent.vercel.app)

---

## 🚀 Features

- 🎙️ Voice input using browser microphone access
- 🧠 Agent session control using ElevenLabs' SDK
- 💬 Live status updates for speaking vs listening
- ✨ Animated visual feedback via Tailwind CSS
- 🔐 Environment-based agent ID management

---

## 📁 Project Structure

```

.
├── public/
├── src/
│   └── app/
│       ├── components/
│       │   └── conversation.tsx      # Core conversation logic and UI
│       ├── globals.css
│       ├── layout.tsx
│       └── page.tsx                  # Root page using <Conversation />
├── .gitignore
├── next.config.ts
├── package.json
├── tsconfig.json
└── README.md

````

---

## 🛠️ Getting Started

### 1. Clone the project

```bash
git clone https://github.com/aimaster-dev/call-with-ai-agent.git
cd call-with-ai-agent
````

### 2. Install dependencies

```bash
npm install
```

### 3. Configure environment variables

Create a `.env.local` file at the root:

```env
NEXT_PUBLIC_AGENT_ID=your_elevenlabs_agent_id_here
```

> ✅ Must begin with `NEXT_PUBLIC_` to be available on the client side.

### 4. Start development server

```bash
npm run dev
```

Open `http://localhost:3000` to view it in your browser.

---

## 🧪 Deployment

This project is deployed using [Vercel](https://vercel.com/).

### 🔧 Vercel Setup

1. Go to your project on Vercel
2. Navigate to **Settings → Environment Variables**
3. Add:

```
Name: NEXT_PUBLIC_AGENT_ID
Value: your_agent_id
Environment: All (Production, Preview, Development)
```

4. Redeploy the project.

---

## 📦 Tech Stack

* **Next.js 15+**
* **TypeScript**
* **Tailwind CSS**
* **@11labs/react**
* **Vercel (for hosting)**

---

## 🧠 Powered by

[ElevenLabs](https://www.elevenlabs.io/) — Realistic voice AI for conversational experiences.

---

## 📄 License

MIT — free to use, modify, and distribute.

---
