# Feedback-form-agent

# 🧠 AI Feedback Management Agent (n8n + Gemini + Airtable + Slack)

This is an AI-powered Feedback Agent built using n8n, Google Gemini, Airtable, and Slack. It automates the entire process of receiving, categorizing, and responding to customer feedback — with zero manual intervention.

---

## 💡 What It Does

- Accepts feedback via a public form
- Uses **Gemini API** to classify feedback into:
  - Complaint  
  - Compliment  
  - Feature Addition Request
- Applies logic-based routing using a **Switch Node**
- Stores the record in **Airtable**
- Notifies the relevant team via **Slack**
- Sends an automated email to the user if it's a complaint

---

## 🔧 Tools Used

- [n8n] – automation
- [Google Gemini API] – for intent classification
- [Airtable] – to log feedback records
- [Slack] – for internal team alerts
- [Gmail] – auto-reply emails

---

## 📸 Screenshot

![Screenshot 2025-06-19 160804](https://github.com/user-attachments/assets/68484d99-84f2-42b9-9429-81ad847c6882)
![Screenshot 2025-06-19 160737](https://github.com/user-attachments/assets/2eb209bf-6ac0-4741-8be9-a98489488bfc)


---

## 📂 Folder Contents

- `feedback_form.json` – Exported n8n workflow
- `README.md` – Full documentation
- `screenshot.png` – Visual layout of the workflow

---

## 🛠 How to Use

1. Import the `feedback_form.json` file into your n8n instance
2. Set up required credentials:
   - Google Gemini API
   - Airtable API Key
   - Slack Webhook or OAuth
   - Gmail account for auto-email
3. Embed or connect your frontend form to the webhook trigger
4. Go live!

---

## 🚀 Benefits

✅ Saves manual effort  
✅ Responds to users instantly  
✅ Alerts the right team automatically  
✅ Keeps all feedback logged + trackable  
✅ Enhances overall customer experience

---

## 👤 Built By

**Aakarsh Shrivastava**  
[LinkedIn](https://www.linkedin.com/in/aakarsh-shrivastava-998bb21a0)

---

