# 🧠 Hebbia Clone

A lightweight Hebbia-inspired tool that allows you to **upload documents** and automatically extracts structured insights into a **table using AI**.

This is a clone of Hebbia's document intelligence functionality — enabling users to get instant answers and tabular summaries from large PDFs, reports, and other document types.

---

## ✨ Features

- 📄 Upload documents (PDF, DOCX, TXT)
- 🧠 AI-powered extraction of key data
- 📊 Instant tabular representation of insights
- 🔍 Query interface for asking questions about the document
- ⚡ Fast and scalable backend (built for extensibility)

---

## 🚀 Getting Started

### 1. Install dependencies

```bash
# Backend (Python/FastAPI)
cd backend
npm install

# Frontend (React)
cd ../frontend
npm install
```

### 2. Setup environment variables

Create a `.env` file in both `backend/` and `frontend/` directories with appropriate API keys:

```env
# backend/.env
OPENAI_API_KEY=your_openai_key
PORT=3001
```

```env
# frontend/.env
REACT_APP_BACKEND_URL=http://localhost:3001
```

### 3. Run the app

```bash
# Start backend
cd backend
npm run start

# Start frontend
cd ../frontend
npm start
```

---

## 🖠 Tech Stack

- **Frontend:** React, Tailwind CSS
- **Backend:** Python, FastAPI
- **AI Models:** OpenAI GPT-4o
- **Parsing:** PDF.js, docx-parser

---

## 📂 Example Use Case

1. Upload an investor report PDF.
2. The AI reads through the document.
3. A table with extracted insights — like revenue, customer numbers, growth — is populated automatically.
4. Ask: _"What was the net profit in Q4?"_

---

## 🤝 Contributing

Pull requests welcome! For major changes, open an issue first to discuss what you’d like to change.

---

## 📄 License

[MIT](LICENSE)

---

## 🔗 Inspired By

- [Hebbia](https://hebbia.ai) — The original AI-powered document Q&A platform.
