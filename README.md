# Tds-Virtual-TA

A virtual assistant built for the *Tools in Data Science* (TDS) course at IIT Madras.

It can automatically answer student queries based on:

- 📘 Course Content (Jan 2025-Apr 2025)
- 🗣️ Discourse Q&A Posts (Jan 1 – Apr 14, 2025)
- 📸 Optional screenshot images (base64 format)
- 🧠 AI-powered responses via [AIPipe.org](https://aipipe.org)

---

## 🌐 Live Deployment

- 🧪 Swagger UI Docs: [https://tds-virtual-ta-three.vercel.app/docs](https://tds-virtual-ta-three.vercel.app/docs)
- 📡 Base API URL: `https://tds-virtual-ta-three.vercel.app`

---

## 🔍 API Endpoints

### `POST /query`

This is the main endpoint to ask questions to the TDS Virtual TA.

#### 📝 Input Format (JSON):

```json
{
  "question": "Your question text goes here",
  "image": "base64-encoded string of a screenshot (optional)"
}
