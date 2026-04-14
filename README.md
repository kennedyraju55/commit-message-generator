# 📝 Commit Message Generator

**Generate meaningful commit messages using local Gemma 3 AI**

![Python](https://img.shields.io/badge/Python-3.8+-3776ab?style=flat-square&logo=python)
![Ollama](https://img.shields.io/badge/Ollama-Compatible-005a9c?style=flat-square)
![Gemma3](https://img.shields.io/badge/Gemma%203-LLM-4285f4?style=flat-square)
![License](https://img.shields.io/badge/License-MIT-green?style=flat-square)
![Privacy First](https://img.shields.io/badge/Privacy-First-ff69b4?style=flat-square)

## What It Does

- Analyzes code changes and suggests descriptive commit messages with Gemma 3
- Follows conventional commit format automatically
- No external APIs — all processing stays on your machine

## Tech Stack

Python, Ollama, Gemma 3, Git

## Quick Start

1. Clone: git clone https://github.com/kennedyraju55/commit-message-generator.git && cd commit-message-generator
2. Install: pip install -r requirements.txt
3. Pull model: ollama pull gemma3:4b
4. Generate: python generate.py

## Architecture

Integrates with Git to analyze staged changes, sending diffs to Gemma 3 via Ollama for intelligent message generation.

## Why Local?

- **No API Keys Required** — Zero external dependencies
- **Complete Privacy** — Code stays on your machine
- **Offline Operation** — Works without internet
- **Cost-Free** — No monthly API bills

## Contributing

Found a bug? Have an improvement? Open an issue or submit a PR! All contributions welcome.

## License

MIT License — See LICENSE file for details

---

**Part of 114+ privacy-first AI tools by Nrk Raju**