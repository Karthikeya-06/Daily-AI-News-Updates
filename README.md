# Zapier Workflow: Daily AI News → Telegram

## 📌 Overview
This repository contains a Zapier automation that performs a **daily AI news check**, processes the data using **AI by Zapier**, and sends the summarized results directly to **Telegram**.  
It is designed to keep you updated with AI-related news in a simple, automated way.

---

## ⚙️ Workflow Steps
1. **Trigger – Schedule by Zapier**  
   Runs once per day to initiate the workflow.

2. **Action – AI by Zapier**  
   Analyzes the collected AI news and returns a concise summary.

3. **Action – Telegram**  
   Sends the summarized news update to a specified Telegram chat.

---

## 🚀 Setup Instructions
1. Open [Zapier](https://zapier.com) and create a new Zap.
2. Add the following steps:
   - **Schedule by Zapier** → set frequency (e.g., daily at 9 AM).
   - **AI by Zapier** → configure prompt to analyze and summarize AI news.
   - **Telegram** → connect your Telegram account and choose the target chat.
3. Test each step to confirm the workflow runs correctly.
4. Save and turn on the Zap.

---

## 📂 Repository Contents
- `zapier-workflow.json` → Documentation of the workflow steps.
- `workflow-diagram.png` → Visual diagram of the automation flow.
- `README.md` → This file, explaining the workflow and setup.

---

## 🔒 Notes
- Do **not** commit API keys, tokens, or personal credentials to GitHub.
- Use environment variables or placeholders (e.g., `TELEGRAM_API_KEY=YOUR_KEY_HERE`).
- Screenshots are included for clarity but should not expose sensitive data.

---

## ✅ Use Cases
- Daily AI/tech news updates sent to your Telegram.
- Automated summaries for quick reading.
- Can be extended to other messaging apps (WhatsApp, Slack, Discord).

---

## 📜 License
This project is shared for educational and personal productivity purposes.  
Feel free to fork and adapt it to your own needs.
