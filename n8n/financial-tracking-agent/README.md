# 💰 AI Financial Tracking Agent (Income & Expenses)

An agentic n8n workflow that records personal or family 
income and expenses automatically via conversational input — 
accepting text, audio, images, or files, and logging everything 
to Google Sheets after user confirmation.

## 🔧 Tools Used
- n8n (self-hosted)
- OpenAI (GPT + Whisper for audio transcription)
- Google Sheets
- Telegram or WhatsApp (input channel)

## ⚙️ How It Works
1. **Input**: User sends a message — text, voice note, 
   image (receipt), or file
2. **AI Extraction**: Agent identifies transaction type 
   (income/expense), amount, category, and date
3. **Confirmation**: Agent asks user to confirm before logging
4. **Logging**: Confirmed data is recorded automatically 
   to Google Sheets
5. **Agentic behavior**: Handles follow-up questions, 
   corrections, and ambiguous inputs

## 📈 Business Impact
- Eliminates manual bookkeeping for families and small businesses
- Works via natural language — no forms or spreadsheets needed
- Accepts any input format: voice, photo of receipt, or text
- Built on self-hosted n8n — zero per-execution costs

## 🔮 Roadmap
- RAG integration for financial history queries
- Monthly summary reports
- Budget alerts and anomaly detection
