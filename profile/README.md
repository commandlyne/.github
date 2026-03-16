<p align="center">
  <img src="https://raw.githubusercontent.com/clawworker/install/main/assets/logo.png" alt="ClawWorker" width="140" />
</p>

<h1 align="center">ClawWorker</h1>
<h3 align="center">Your AI Assistant, Everywhere.</h3>

<p align="center">
  <strong>One binary. Every cloud. Every channel. Every LLM.</strong>
</p>

<p align="center">
  <a href="https://github.com/clawworker/install">Install</a> &bull;
  <a href="https://github.com/orgs/clawworker/discussions">Discussions</a> &bull;
  <a href="https://github.com/clawworker/install/issues">Issues</a>
</p>

---

ClawWorker is a **single-binary AI assistant** that deploys anywhere — your laptop, a cloud VM, a Raspberry Pi, or a Kubernetes cluster. It connects LLMs to messaging platforms, productivity tools, and a built-in Web UI, all from one lightweight process.

```bash
curl -fsSL https://raw.githubusercontent.com/clawworker/install/main/install.sh | bash
```

---

## Deep Google Integration

ClawWorker is built with **first-class Google ecosystem support** — from Gemini as an AI backbone to full Google Workspace automation.

### Gemini — Native API, Not a Wrapper

ClawWorker talks to Gemini through the **official Google GenAI SDK** — not an OpenAI-compatible shim. This means you get full access to Gemini's native capabilities:

- **Gemini 2.5 Flash & Pro** — latest models with full function calling
- **Native streaming** — real token-by-token output, not polled
- **Extended thinking** — thought signature support for deeper reasoning
- **Rich media input** — send audio (wav, mp3, flac, ogg), video (mp4, mov, webm), and images directly in conversation
- **Vertex AI** — deploy on Google Cloud with project-level isolation and enterprise auth
- **Google OAuth** — device flow authentication, no API key needed

```bash
export CLAWWORKER_PROVIDER=gemini
export CLAWWORKER_API_KEY=your-gemini-key
export CLAWWORKER_MODEL=gemini-2.5-flash
```

### Google Workspace — Your AI-Powered Office

Connect your Google account once and ClawWorker becomes your **AI assistant across the entire Google suite**:

| Service | What ClawWorker Can Do |
|---|---|
| **Gmail** | Read, compose, reply, forward, manage drafts and labels |
| **Calendar** | Create events, find free time, manage attendees, auto-attach Meet links |
| **Drive** | Search, read, create, share files and folders — exports Docs/Sheets/Slides |
| **Meet** | Create meetings, list participants, capture and query transcripts |
| **Contacts** | Search, add, update contacts — used across all Google tools for name resolution |
| **Google Chat** | Two modes: Bot (webhook) for teams, or User (polling) for personal use |

Every Google tool resolves names through **Contacts** automatically — type "schedule a meeting with Sarah" and ClawWorker finds the right email.

### How It Connects

```
You ──→ ClawWorker ──→ Google Gemini (AI brain)
                   ├──→ Gmail (read/send email)
                   ├──→ Calendar (schedule/manage events)
                   ├──→ Drive (files/docs/sheets)
                   ├──→ Meet (create meetings, transcripts)
                   ├──→ Google Chat (messaging)
                   └──→ Contacts (name resolution)
```

One OAuth login. All services. No separate setup per tool.

---

## Beyond Google — Everything Else Too

### 10+ LLM Providers

| Provider | Highlights |
|---|---|
| **Google Gemini** | Native SDK, streaming, media input, extended thinking |
| **Vertex AI** | Enterprise Google Cloud deployment |
| **OpenAI** | GPT-4o, o1, o3 |
| **Anthropic** | Claude Opus, Sonnet, Haiku |
| **OpenRouter** | 200+ models, one API |
| **Ollama** | Run models locally — Llama, Mistral, Phi |
| **Groq** | Ultra-fast inference |
| **Mistral** | Mistral Large, Medium, Small |
| + more | Cerebras, XAI, LiteLLM, Cloudflare Workers AI |

### 15+ Messaging Channels

**Chat:** Telegram, Discord, Slack, WhatsApp, Signal, Matrix, IRC, LINE, Google Chat, Feishu/Lark, Nextcloud Talk, DingTalk, Mattermost, Teams, QQ

**Other:** Gmail, Twitch, iMessage (via BlueBubbles), Nostr, Voice calls (Telnyx)

### 40+ Built-in Tools

Shell, file I/O, browser automation, web search (Brave/Tavily/Perplexity), image generation (DALL-E), PDF/audio/video processing, persistent vector memory, cron scheduling, multi-agent orchestration, and more.

### Beautiful Interfaces

- **Web UI** — embedded htmx chat, zero setup
- **Terminal UI** — rich bubbletea TUI
- **CLI** — one-shot queries or REPL
- **REST API** — OpenAI-compatible endpoints

### Enterprise-Ready

Encrypted vault for secrets, tool execution policies, auth failover with key rotation, hot config reload, OpenTelemetry, Tailscale secure access.

---

## Get Started

```bash
# Install (Linux & macOS)
curl -fsSL https://raw.githubusercontent.com/clawworker/install/main/install.sh | bash

# Configure
clawworker onboard

# Run
clawworker gateway
```

<p align="center">
  <a href="https://github.com/clawworker/install"><strong>Installation Guide &rarr;</strong></a>
</p>

---

<p align="center">
  Built with care by <a href="https://codimite.com">Codimite</a>
</p>
<p align="center">
  Copyright &copy; 2026 ClawWorker. All Rights Reserved.
</p>
