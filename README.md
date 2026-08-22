# 🎉 Onam Excuse Generator 🍌

A fun and simple webpage that generates **funny excuses** for why you might be late to the Onam *sadya*!  

---

## 🚀 How to Use
1. Visit the hosted page: [GitHub Pages Link](https://sebin-gg.github.io/onam-excuse-generator/)
2. Enter your name
3. Get your personalized Onam excuse 😄

---

## 🌼 Example
> Anu, your Onam excuse is: You slipped on spilled payasam and needed recovery time 🥣!

---

## 💡 Tech
- HTML
- CSS
- JavaScript

## 🔒 Security

This repository uses [gitleaks](https://github.com/gitleaks/gitleaks) for automatic secret scanning on every commit.

### Pre-commit Hook

A pre-commit hook is configured to scan for secrets before each commit. This helps prevent accidentally committing sensitive information like:
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

In case of emergency, you can bypass the hook:

```bash
git commit --no-verify -m "emergency commit"
```

> ⚠️ Only use `--no-verify` in emergency situations. Regular commits should always be scanned.

