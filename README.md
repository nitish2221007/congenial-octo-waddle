# 🚀 Xeno Mini CRM – SDE Internship Assignment 2025

Welcome to my submission for the **Xeno Software Development Engineering (SDE) Internship 2025**. This is a full-stack CRM platform designed for marketing teams to manage customer data, create targeted campaigns, and leverage AI-powered tools for intelligent segmentation and messaging.

---

## ✨ Demo

- 🔗 **Live App**: [Your Deployed Link Here]
- 📹 **Demo Video**: [YouTube or Loom Link Here]
- 📁 **GitHub Repo**: [Repo Link Here]

---

## 📌 Features

### ✅ 1. Data Ingestion APIs
- Secure REST APIs for ingesting customer and order data
- Built using Express.js
- API Documentation available via Swagger/Postman

### ✅ 2. Campaign Creation UI
- React-based frontend to define audience segments
- Rule builder with AND/OR logic
- Real-time audience size preview
- Redirects to campaign history page after saving

### ✅ 3. Campaign Delivery & Logging
- Campaign logs stored in MongoDB
- Simulated delivery via dummy vendor API
- 90% success, 10% failure rate
- Delivery Receipt API updates log statuses

### ✅ 4. Authentication
- Google OAuth 2.0 login
- Only logged-in users can create/view campaigns

### ✅ 5. AI Integration
- ✨ Prompt-to-rule conversion using OpenAI GPT
- Example: `"Users inactive for 3 months who spent over ₹5000"` → dynamic segment logic
- Other AI features: Smart message suggestions, campaign insights

---

## 🛠 Tech Stack

| Layer     | Technology             |
|-----------|------------------------|
| Frontend  | React.js, Tailwind CSS |
| Backend   | Node.js, Express.js    |
| Database  | MongoDB (Mongoose)     |
| Auth      | Google OAuth 2.0       |
| AI Tools  | OpenAI GPT API         |
| Extras    | Postman, Swagger       |

---

## 🧪 AI Features Summary

| Feature | Description |
|--------|-------------|
| 🔠 Prompt to Rules | Converts natural language into segment filters |
| 💬 Message Suggestions | AI-generated message variations based on campaign goal |
| 📊 Insight Summarization | Converts delivery stats into natural summaries |
| 🕒 Smart Scheduling (Mocked) | Suggests optimal campaign send time |
| 🏷️ Auto-tagging | Tags campaigns like “Win-back” or “VIP” |

---

## 📦 Project Structure