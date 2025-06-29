# 📧 Gmail AI Responder

This project auto-replies to emails using OpenAI's GPT API and sends them via Gmail's SMTP.

---

## ⚙️ How It Works

1. You provide the incoming email content.
2. GPT-3.5-Turbo generates a natural reply.
3. The reply is emailed back via Gmail SMTP.

---

## 🚀 How to Use

1. Clone this repo.
2. Install dependencies: `pip install openai`
3. Fill in:
   - Your OpenAI API key
   - Gmail address + [App Password](https://myaccount.google.com/apppasswords)
   - Test recipient email
4. Run:
```bash
python3 gmail_ai_responder.py
