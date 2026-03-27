# 📬 Gmail AI Auto-Labeling — n8n Edition

Self-hosted replacement of the original Make.com workflow. 
Automatically classifies and labels incoming Gmail emails 
using OpenAI, with zero subscription costs beyond the 
self-hosted server.

## 🔧 Tools Used
- n8n (self-hosted on VPS)
- Gmail API
- OpenAI (GPT)
- Google Sheets

## ⚙️ How It Works
1. **Trigger**: Monitors Gmail inbox for new emails
2. **AI Classification**: GPT classifies each email as 
   LEAD_QUALIFIED, LEAD_NOT_QUALIFIED, IMPORTANT, 
   IMPORTANT/Meeting, or Newsletter/AI News
3. **Labeling**: Applies the correct Gmail label automatically
4. **Logging**: Qualified leads and AI news logged to 
   Google Sheets

## 💡 Why n8n Instead of Make?
- **Cost**: Self-hosted n8n on VPS vs. Make subscription 
  + per-operation costs
- **Control**: Full ownership of the workflow and data
- **Scalability**: No execution limits

## 📈 Business Impact
- Identical functionality to the Make version — 
  at a fraction of the cost
- Demonstrates ability to migrate and optimize 
  automation stacks
- Part of a larger email intelligence pipeline
