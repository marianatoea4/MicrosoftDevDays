🌐 [Português (Brasil)](README.pt_BR.md) | [Español](README.es.md)

<div align="center">

# 🎮 Mona Mayhem

**VS Code & GitHub Copilot CLI Workshop** — Build a GitHub Contribution Battle Arena

[![Use this template](https://img.shields.io/badge/Use%20this%20template-2ea44f?style=for-the-badge&logo=github&logoColor=white)](https://github.com/marianatoea4/MicrosoftDevDays/generate)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge)](LICENSE)
[![Astro](https://img.shields.io/badge/Astro-v5-BC52EE?style=for-the-badge&logo=astro&logoColor=white)](https://astro.build/)

</div>

---

A workshop template for building a **retro arcade-themed website** with Astro that pits two GitHub users head-to-head in a contribution battle. This is the **starting point** — you'll build the app step by step using GitHub Copilot.

![Mona Mayhem Screenshot](https://github.com/user-attachments/assets/5eca79e2-cb9f-4e93-aa0d-23666ebde3b7)
*What you'll build by the end of the workshop*

---

## ⚡ What You'll Build & Learn

By the end of the workshop you'll have shipped a fully working retro arcade site **and** practiced these Copilot superpowers:

| | Skill | In practice |
|--|-------|-------------|
| 🧠 | **Context Engineering** | Teach Copilot your codebase with instructions, references, and constraints |
| 📐 | **Plan First** | Draft architecture before writing a single line of code |
| 🤖 | **Agentic Implementation** | Let Copilot carry out multi-step work with your supervision |
| 🎨 | **Iterative Design** | Transform visuals and refine interaction details interactively |
| ⚡ | **Parallel Workflows** | Split work across agents, sessions, or delegated tasks |

---

## 🛤️ Choose Your Track

The workshop supports **two tracks** — follow the one that matches your preferred workflow:

| | VS Code Track | CLI Track |
|--|--------------|-----------|
| **Tool** | VS Code + Copilot extension | GitHub Copilot CLI (`copilot`) |
| **Key features** | Chat, Plan Mode, Agent Mode, background agents, review loops | `@file` context, `/plan`, autonomous edits, `/fleet`, `/delegate`, `/review` |
| **Best for** | Editor-native workflows | Terminal-first workflows |

---

## 📚 Workshop

| Part | Title | Copilot Focus |
|------|-------|---------------|
| [00](workshop/00-overview.md) | Overview | Track selection and learning goals |
| [01](workshop/01-setup.md) | Setup & Context Engineering | Instructions, permissions, and environment setup |
| [02](workshop/02-plan-and-scaffold.md) | Plan & Scaffold | Planning the API and page architecture |
| [03](workshop/03-agent-mode.md) | Build the Game | Agentic implementation and iteration |
| [04](workshop/04-design-vibes.md) | Design-First Theming | Visual design planning and implementation |
| [05](workshop/05-polish.md) | Polish & Parallel Work | Parallelism, reviews, and quality passes |
| [06](workshop/06-bonus.md) | Bonus & Extensions | Open-ended feature ideas and extra Copilot experiments |

---

## 🚀 Quick Start

1. **Create your own repo** by clicking **[Use this template](https://github.com/marianatoea4/MicrosoftDevDays/generate)** above, or fork this repository.
2. Choose your workshop path:
   - **VS Code:** clone your repo and open it in VS Code.
   - **GitHub Copilot CLI:** clone your repo locally, install `copilot`, and work from your terminal.
3. Follow the [workshop guide](workshop/00-overview.md).

---

## ✅ Prerequisites

### Shared

- GitHub Copilot (Pro, Business, or Enterprise)
- Git
- Node.js

### VS Code track

- VS Code v1.107+
- GitHub Copilot extension signed in

### CLI track

- GitHub Copilot CLI (`copilot`)
- Node.js 22+ if you plan to install the CLI via `npm install -g @github/copilot`
- Or Homebrew / WinGet if you prefer a native package manager install

---

## 🔧 Technology Stack

| | |
|--|--|
| **Framework** | [Astro](https://astro.build/) v5 |
| **Runtime** | Node.js + [@astrojs/node](https://docs.astro.build/en/guides/integrations-guide/node/) adapter |
| **Font** | Press Start 2P (retro gaming font) |
| **API** | GitHub's contribution graph API |

---

## 📄 License

MIT
