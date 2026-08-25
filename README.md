# 🎉 Onam Excuse Generator 🍌

Enter your name and instantly get a **funny excuse** for being late to the Onam *sadya*! This is a single-page site built with plain HTML, CSS, and JavaScript, hosted on GitHub Pages. Playful tone fully intentional. 🌼

## 🔗 Live Site

👉 [onam-excuse-generator on GitHub Pages](https://sebin-gg.github.io/onam-excuse-generator/)

## 🚀 How It Works

1. Visit the [GitHub Pages link](https://sebin-gg.github.io/onam-excuse-generator/)
2. Enter your name
3. Get your personalized Onam excuse 😄

### 🌼 Example

> Anu, your Onam excuse is: You slipped on spilled payasam and needed recovery time 🥣!

## 💻 Run Locally

No build step or dependencies required. Just open `index.html` in your browser:

```bash
git clone https://github.com/sebin-gg/onam-excuse-generator.git
cd onam-excuse-generator
```

Then open `index.html` in any modern browser.

## 💡 Tech

- HTML
- CSS
- JavaScript

## 🔒 Security

This repo uses [gitleaks](https://github.com/gitleaks/gitleaks) for automatic secret scanning on every commit.

### Pre-commit Hook

A pre-commit hook scans for secrets before each commit. This helps prevent accidentally committing sensitive information such as:

- API keys
- Passwords
- Tokens
- Private keys

### Setup

To enable the pre-commit hook locally:

```bash
# Install pre-commit
pip install pre-commit

# Install hooks
pre-commit install
```

### Bypass (Emergency Only)

If you ever need to bypass the hook:

```bash
git commit --no-verify -m "emergency commit"
```

> ⚠️ Only use `--no-verify` in emergencies. Regular commits should always be scanned.

## 🙏 Credits

Created by [sebin-gg](https://github.com/sebin-gg). Features `mahabali.png` artwork. Happy Onam! 🌺
