# Contributing to FilmBee 🐝

Welcome to the hive! We are thrilled you want to help us build better media automation tools. Whether you are fixing a bug, adding a feature to a bot, or improving documentation, your help is appreciated.

## 🚨 Security First (Important!)

**NEVER commit API Keys, Bot Tokens, or `config.py` files containing secrets.**
* Always use Environment Variables or a `.env` file (which is added to `.gitignore`).
* If you accidentally push a token, revoke it immediately via BotFather.

## 🛠️ How to Contribute

### 1. Reporting Bugs
* Check the "Issues" tab to see if it has already been reported.
* If not, open a new issue. Include:
    * Your OS / Environment.
    * Python version.
    * Steps to reproduce the error.
    * Logs (removing any sensitive info).

### 2. Local Development (Python/Bots)
1.  **Fork** the repository.
2.  **Clone** your fork locally.
3.  Create a virtual environment:
    ```bash
    python3 -m venv venv
    source venv/bin/activate  # Linux/Mac
    # or
    venv\Scripts\activate  # Windows
    ```
4.  Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```
5.  Create a branch for your feature: `git checkout -b feature/my-cool-feature`.

### 3. Pull Requests (PRs)
* Push your branch to your fork.
* Open a Pull Request against our `main` branch.
* Describe clearly what your code changes.

## 🎨 Coding Standards

We follow standard Python PEP 8 guidelines.
* **Linters:** We recommend using `flake8` or `black` before committing.
* **Imports:** Keep imports organized (Standard library > Third party > Local).
* **Variables:** Use `snake_case` for variables/functions and `CamelCase` for classes.

Thank you for building with FilmBee! 🐝
