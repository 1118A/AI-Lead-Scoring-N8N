# 🚀 AI Lead Scoring Automation (n8n + Grok)

## 📌 Overview
This project is an AI-powered lead scoring system built using n8n, Google Sheets, and Grok (xAI).

It automatically captures, analyzes, and scores leads based on behavior and engagement.

---

## ⚙️ Features

- 🔗 Telegram-Bot lead capture
- 📊 Google Sheets integration (store/update leads)
- 🤖 AI Agent (Grok) for lead scoring
- 🧠 Score classification (Hot / Warm / Cold)
- 🔔 Slack alerts for high-value leads
- 🔄 Upsert logic (no duplicate leads)

---

## 🧠 Workflow

Telegram → Data Cleaning → Google Sheets (Upsert)  
→ AI Agent (Grok) → Score Generation  
→ Update Sheet → Slack Alert  

---

## 🛠️ Tech Stack

- n8n (Automation)
- Google Sheets (Database)
- Grok (xAI) – AI Scoring
- Telegram & APIs
- Slack Integration

---

## 📸 Screenshots

<img width="1595" height="577" alt="image" src="https://github.com/user-attachments/assets/7535db2f-716b-46a8-9efc-3e048272b4c6" />


---

## 🚀 How to Use

1. Import `workflow.json` into n8n  
2. Connect Google Sheets credentials  
3. Add Grok API key  
4. Configure Slack webhook  
5. Run workflow  

---

## 📬 Example Input

```json
{
  "email": "test@gmail.com",
  "company": "ABC",
  "job_title": "Manager",
  "visits": 10,
  "pages": 5,
  "utm_source": "Google Ads"
}
