# 📬 Gmail AI Auto-Labeling with Lead Qualification

Automatically classifies and labels incoming Gmail emails using 
OpenAI, routes them by priority, and logs qualified leads + 
AI newsletter sources to Google Sheets.

## 🔧 Tools Used
- Make (formerly Integromat)
- Gmail
- OpenAI (GPT)
- Google Sheets
- Make Router

## ⚙️ How It Works
1. **Trigger**: Watches Gmail inbox for new emails
2. **Router**: Splits flow — leads vs. general emails
3. **AI Classification**: GPT analyzes content and qualifies each email as LEAD_QUALIFIED, LEAD_NOT_QUALIFIED, IMPORTANT, IMPORTANT/Meeting, or Newsletter/AI News
4. **Labeling**: Automatically applies the correct Gmail label
5. **Logging**: Qualified leads → saved to "Leads" Google Sheet. AI newsletters → saved to "AI News" Google Sheet (feeds the LinkedIn Publisher flow)

## 📈 Business Impact
- Zero manual inbox management
- Leads get immediate priority attention
- AI news data feeds automated LinkedIn content pipeline
- Saves ~1-2 hours/day of email triage
