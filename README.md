
# 🤖 Telegram Bot (n8n Automation)

A fully automated **Telegram Bot** built using **n8n**, designed to interact with users, answer questions, and automate workflows — **without writing any code**.
This bot can handle messages, reminders, study help, and more, powered entirely by visual automation in n8n.

---

## 🚀 Features

* 💬 Automatically responds to Telegram user messages
* 🧠 Connects with AI or external APIs for intelligent replies
* ⏰ Sends reminders, notifications, or updates
* 🔄 Easy to customize using n8n’s visual workflow builder
* ⚙️ Works 24/7 once deployed — no coding required

---

## 🛠️ Tools & Platform

* **Platform:** [n8n](https://n8n.io/)
* **Integration:** Telegram Bot API
* **Nodes Used:**

  * Telegram Trigger
  * Telegram Send Message
  * AI or OpenAI Node (optional)
  * Function / Set / If Nodes
  * Delay or Schedule Trigger (for reminders)

---

## ⚙️ Setup Instructions

### 1. Create Your Telegram Bot

1. Open Telegram and search for **@BotFather**
2. Type `/newbot` and follow the steps
3. Copy the **API Token** you receive — you’ll need it in n8n

---

### 2. Configure n8n

1. Log in to your **n8n dashboard**

2. Create a **new workflow**

3. Add the following nodes:

   | Node                            | Purpose                           |
   | ------------------------------- | --------------------------------- |
   | **Telegram Trigger**            | Receives new messages from users  |
   | **Function / IF Node**          | Process or filter user messages   |
   | **Telegram Send Message**       | Sends reply messages              |
   | **(Optional) AI Node**          | Generate smart responses using AI |
   | **(Optional) Schedule Trigger** | Send daily reminders or updates   |

4. In **Telegram Trigger Node**, paste your **Bot Token**.

5. Click **"Execute Workflow"** to test.

6. When ready, click **Activate Workflow** so it runs continuously.

---

## 🧠 Example Use Cases

* 📚 **Study Assistant Bot** — answers questions and sets reminders
* 🎬 **Movie Recommendation Bot** — suggests films using AI APIs
* 📅 **Daily Reminder Bot** — sends motivational or study messages
* 💼 **Customer Support Bot** — replies automatically to common queries

---

## 📄 Example Workflow Structure

```
📲 Telegram Trigger  
   ↓
🔍 IF Node (Check message text)  
   ↓
💬 Telegram Send Message (reply)  
   ↓
🧠 (Optional) OpenAI / AI Node (generate response)


`


---

## 💡 Tips

* Use **n8n Cloud** for 24/7 uptime
* Combine with **Google Sheets Node** to log messages or user data
* Add **Webhook / HTTP Request Node** to integrate with other tools

---

## 📁 Folder & File Summary

```
telegram-bot-n8n/
│
├── README.md          # Documentation (this file)
├── telegram-bot.json  # Exported n8n workflow
└── assets/            # Optional images or bot screenshots
```

---

## 🚀 Deployment Options

* **n8n Cloud** — easiest way, no setup needed
* **Self-Hosted n8n** — install via Docker or desktop app
* **Integrate with AI APIs** — connect OpenAI, Hugging Face, or Gemini

---

## 👤 Author

**[Shashank]**
Built with ❤️ using **n8n** & **Telegram Bot API** — no code, just automation.

