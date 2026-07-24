# Contributing to FilmBee

Thanks for your interest in contributing. Whether it's a bug fix, a new feature, or better docs, we appreciate the help.

## Security

**Never commit API keys, bot tokens, or files containing secrets.**

- Use environment variables or a `.env` file (always in `.gitignore`).
- If you accidentally push a token, revoke it immediately via BotFather.

## Getting Started

### Reporting Bugs

Check the Issues tab first. If it hasn't been reported, open a new issue with:

- Your OS and environment
- Python version
- Steps to reproduce
- Logs (with sensitive info removed)

### Local Development

1. **Fork** the repository.
2. **Clone** your fork locally.
3. Create a virtual environment:
   ```bash
   python3 -m venv venv
   source venv/bin/activate  # Linux/Mac
   venv\Scripts\activate     # Windows
   ```
4. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
5. Create a branch: `git checkout -b feature/your-feature-name`

### Pull Requests

- Push your branch to your fork.
- Open a PR against the `main` branch.
- Describe what your code changes and why.

## Coding Standards

We follow PEP 8.

- **Formatting:** Run `black` or `flake8` before committing.
- **Imports:** Standard library, then third-party, then local.
- **Naming:** `snake_case` for variables and functions, `CamelCase` for classes.

## Join the Team

If you're interested in working on our internal tooling (media server, Telegram bots, automation pipelines), reach out on [Telegram](https://t.me/EithonX). We're always looking for people who want to build with us.
