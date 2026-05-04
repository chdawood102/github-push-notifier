# 🚀 GitHub Push Notifier

An event-driven automation that sends a real-time 
email notification every time code is pushed to 
a GitHub repository.

## 💡 What It Does

When you push code to GitHub → n8n receives the 
signal → Gmail sends an automatic email saying 
"I just shipped X to repo Y"

## 🛠️ Built With

- **n8n Cloud** — Workflow automation
- **GitHub Webhooks** — Push event trigger
- **Gmail** — Email notifications

## ⚙️ How It Works

1. GitHub sends a webhook POST request to n8n
2. n8n receives the payload with commit details
3. Gmail node formats and sends notification email

## 📧 Email Contains

- What was shipped (commit message)
- Which repository
- Which branch
- Link to see the changes
- Timestamp

## 🔧 Setup

1. Import `GitHub_Push_Notifier.json` into n8n
2. Connect your Gmail credential
3. Add your n8n Production webhook URL to GitHub
4. Push code and receive instant notifications!

## 👨‍💻 Author

**Dawood Ali**  
GitHub: https://github.com/chdawood102

## 📅 Built

May 2026 — as part of n8n automation portfolio