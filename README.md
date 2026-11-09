<p align="center">
  <img src="logo.webp" width="280" alt="GHOSTSHIELD LABS logo">
</p>

<h1 align="center">GHOSTSHIELD LABS</h1>

<p align="center"><b>Defence Through Intelligence.</b></p>

<p align="center">
  Independent security research and tooling by Jose:<br>
  malware analysis · Active Directory labs · offensive research · local AI
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white" alt="TypeScript">
  <img src="https://img.shields.io/badge/PowerShell-5391FE?logo=powershell&logoColor=white" alt="PowerShell">
  <img src="https://img.shields.io/badge/Windows-0078D4?logo=windows&logoColor=white" alt="Windows">
</p>

---

## 🛡️ Tools

Open source (MIT) and ready to use.

| Project | What it does | Get it |
|---|---|---|
| **[MalLab](https://github.com/joser14/MalLab)** | Windows malware analysis lab: static triage, YARA and Sigma, threat-intel lookups and detonation in a hardened Windows Sandbox. One installer; samples never run on the host. | [Download v1.2.2](https://github.com/joser14/MalLab/releases/latest) |
| **[OrchestraAI](https://github.com/joser14/OrchestraAI)** | Your own private AI team on your PC. A composer plans the task, workers carry it out, and results land as files and PDFs. Runs locally on Ollama + OpenClaw, from a 4 GB laptop up to a GPU box. Windows, macOS, Linux. | [Download v0.3.2](https://github.com/joser14/OrchestraAI/releases/latest) |
| **[AD-LAB](https://github.com/joser14/AD-LAB)** | One-script Active Directory lab on Hyper-V: a domain controller with AD CS, two Windows 11 clients and SQL Server 2022, built unattended from ISOs on an isolated network. | [Source](https://github.com/joser14/AD-LAB) |

## 🔒 Private projects

Not public. The research repos are shared on request with vetted researchers and defenders.

**PHP2SHELL-POC**: Memory-corruption research against the PHP runtime, tracked as CVE-2026-109618 and CVE-2026-109619 ("PHP2SHELL"). It's packaged as a proof-of-concept with a web UI that streams each stage of the chain live. The aim is to show defenders exactly how the issue plays out, step by step. It's meant for controlled lab use only.

**POC-2**: The deeper research track for the same two CVEs. It splits the exploit into modular pieces and backs them with a regression test suite. A full technical write-up covers each primitive, including the dead ends along the way. Everything is built to be reproduced in an isolated environment.

**aiinjectionapp**: A "Break the Bot" prompt-injection challenge built for a live security summit. Teams try to talk a guarded AI chatbot into giving up secrets it has been told to protect. The site is fully static, so it's simple to host and hard to break. It ships with acceptance tests and print-ready briefing sheets for the teams.

**onyx**: "Rein in the Agent", a browser puzzle game from the same summit. Teams sort a rogue AI agent's jobs onto rule mats such as no spending, no sharing and no deleting. The agent fights back by trying to pull jobs off the mats. Get the sort right and the lock opens; it runs on Cloudflare Workers.

**qr-code-app**: The scoring system behind the summit's team scavenger hunt. Teams scan QR codes at each stop, and every team is locked to a single phone to keep things fair. The app times each station and feeds a scorer's sheet and a live leaderboard. It runs on Cloudflare Workers with a D1 database.

**wowhelper**: A suite of World of Warcraft addons gathered in one hub window, built for solo leveling. A small side panel shows only what needs doing right now. The helpers display information and never play for you, so they stay within the game's terms of service. Every helper is covered by automated tests.

**game**: A 3D game built in Unity with the High Definition Render Pipeline. It has its own custom editor and build tooling, and uses the new Input System. Vehicle art is in progress, and Steam integration is planned. It's still in early development.

**Site**: The source for my personal website, [joserscave.app](https://joserscave.app). It's a static site served as-is, with no build step. It's deployed as its own Cloudflare Worker, separate from my other projects. It's the home base that ties everything else together.

## 📫 Contact

Want access to a research project, or to collaborate? Open an issue on any public repo above.
