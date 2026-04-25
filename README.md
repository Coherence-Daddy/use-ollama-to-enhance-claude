# Use Ollama to Enhance Claude — Two-Engine Setup

> Pair Claude Desktop on Anthropic with Claude Code routed through **Ollama** in your terminal. Strategy stays on Pro. Heavy footwork runs on a free open-source model. **Cut your Claude Code bill ~90%.**

[![Live Tutorial](https://img.shields.io/badge/Live%20tutorial-coherencedaddy.com-FF6B4A?style=for-the-badge)](https://coherencedaddy.com/tutorials/use-ollama-to-enhance-claude)
[![Made by Coherence Daddy](https://img.shields.io/badge/Made%20by-Coherence%20Daddy-0E0E10?style=for-the-badge)](https://coherencedaddy.com)

---

## What this is

A 21-slide visual walkthrough that pairs your **Anthropic Claude Desktop** app with an **Ollama-backed Claude Code** terminal session — so the strategic work stays on Pro while the heavy lifting runs on a free open-source model (Gemma, Qwen, DeepSeek, your pick).

- **Auto-detects your OS** — macOS, Windows + WSL2, Linux
- **Copy-paste prompt** — drop one block into Claude and it does ~98% of the setup for you
- **Verifies both engines side-by-side** at the end so you know it actually worked
- **Self-contained HTML** — no build step, opens in any browser

## Why this exists

Claude Pro on the Desktop app is great for thinking, planning, and architecture. Claude Code in the terminal eats quota fast — context-heavy tasks like lints, refactors, file batch ops, and grep-and-replace can burn through your monthly limit in days.

The fix: route Claude Code through **Ollama** (local or cloud-hosted free model). Two engines, same UX, one bill cut by an order of magnitude.

## Quick start

### 1) Open the live tutorial (recommended)

The hosted version has the full visual deck, OS-aware steps, and the copy-paste prompt:

**→ [coherencedaddy.com/tutorials/use-ollama-to-enhance-claude](https://coherencedaddy.com/tutorials/use-ollama-to-enhance-claude)**

### 2) Or use the copy-paste prompt directly

If you want to skip the visuals and let Claude do it all for you:

1. Open [`prompts/copy-paste-prompt.md`](./prompts/copy-paste-prompt.md)
2. Copy the entire file contents
3. Paste into a fresh Claude Desktop / Claude.ai conversation
4. Follow along — it auto-detects your OS, installs everything, configures the router, and verifies both engines

### 3) Or run the presentation locally

```bash
git clone https://github.com/Coherence-Daddy/use-ollama-to-enhance-claude.git
cd use-ollama-to-enhance-claude/presentation
open index.html   # macOS
# or just drag index.html into a browser
```

## What you'll have when you're done

| Engine | Where it runs | What it's for |
|---|---|---|
| **Claude Desktop (Anthropic)** | Native app | Strategy, architecture, code review, tricky bugs |
| **Claude Code → Ollama** | Your terminal | Lints, refactors, repetitive edits, file batch ops |

Two side-by-side panes. Same UX. One of them is free.

## What's in this repo

```
.
├── README.md                          ← this file
├── LICENSE                            ← MIT
├── prompts/
│   └── copy-paste-prompt.md           ← the canonical setup prompt
└── presentation/
    ├── index.html                     ← 21-slide visual walkthrough
    ├── cd-face-coral.png              ← brand asset
    └── copy-paste-prompt.md           ← (mirror of /prompts version, kept beside the deck)
```

The presentation is the **same exact HTML** served at [coherencedaddy.com/tutorials/use-ollama-to-enhance-claude](https://coherencedaddy.com/tutorials/use-ollama-to-enhance-claude). Open it locally, host it yourself, or fork it for your own walkthroughs.

## Topics

`claude-code` `ollama` `gemma` `llm-tools` `cost-optimization` `agentic-coding` `anthropic` `open-source-llm`

## License

MIT — see [`LICENSE`](./LICENSE). Use it, fork it, ship a YouTube walkthrough of it. No attribution required, but if you do credit it, link to [coherencedaddy.com](https://coherencedaddy.com).

---

## About Coherence Daddy

[Coherence Daddy](https://coherencedaddy.com) is a 508(c)(1)(A) faith-driven technology organization on a mission to help humanity be more coherent. We build private, secure self-help tools — and the occasional tutorial that saves you a few hundred bucks on AI bills.

- **Website:** [coherencedaddy.com](https://coherencedaddy.com)
- **Free tools (523+):** [freetools.coherencedaddy.com](https://freetools.coherencedaddy.com)
- **Tutorials:** [coherencedaddy.com/tutorials](https://coherencedaddy.com/tutorials)
- **X / Twitter:** [@coherencedaddy](https://x.com/coherencedaddy)

If this saved you a real chunk of money, the kindest thing you can do is ⭐ this repo and share the tutorial link.
