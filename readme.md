# 🤖 AI Study Buddy (Agentic AI Project)

An autonomous AI-powered study reminder system built using **n8n** and **Perplexity AI**.

The system generates a daily study topic and sends it automatically via email using scheduled workflows (Cron), demonstrating real agentic AI behavior without manual input.

---

## 🚀 Features

- ⏰ Daily automated trigger using Cron
- 🧠 AI-generated study topics (Perplexity LLM)
- ✉️ Email delivery via Gmail integration
- 🧩 No database required
- 🔁 Fully autonomous after setup

---

## 🏗️ System Architecture

Cron Trigger
↓
Perplexity AI (HTTP Request)
↓
Set Node (Data Handling)
↓
Gmail (Daily Study Reminder)

---

## 🛠️ Technologies Used

- n8n (Workflow Automation)
- Perplexity AI (LLM)
- Gmail API
- JavaScript expressions (n8n)
- Cron scheduling

---

## 🧠 How It Works

1. Cron node triggers the workflow every day
2. Perplexity AI generates the study topic for the day
3. The topic is processed using a Set node
4. Gmail node sends a clean, formatted study reminder email

---

## 📂 Project Files

- `AI_Study_Buddy.json` → Exported n8n workflow

---

## 📌 Use Cases

- Students preparing for exams
- Daily learning habit formation
- Demonstration of agentic AI systems
- Automation + AI portfolio project

---

## 📈 Future Improvements

- Day counter (Day 1, Day 2, ...)
- Telegram / WhatsApp notifications
- Weekly revision reminders
- Progress tracking

---

## 👤 Author

**Hairun Nisha M**  
Computer Science Student  
