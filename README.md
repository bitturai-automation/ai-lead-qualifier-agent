# AI Lead Qualifier Agent 🤖

AI-powered lead qualification system that automatically scores 
incoming leads as HOT, WARM or COLD using Groq AI (Free).

## 🔧 Tools Used
- n8n (automation)
- Groq API — Llama 3.3 (free AI)
- Google Forms & Sheets

## ⚡ How It Works
1. Lead fills Google Form
2. n8n triggers automatically
3. Groq AI scores the lead (HOT/WARM/COLD)
4. Results logged in Google Sheets instantly

## 🚀 Setup Guide
1. Import `ai-lead-qualifier-googlesheets.json` in n8n
2. Connect Google Sheets credential
3. Add Groq API key (free at console.groq.com)
4. Activate workflow
5. Done!

## 📊 Output
Every lead gets:
- Score (HOT/WARM/COLD)
- Reason
- Recommended action
- Timestamp

## 👤 Built By
Bittu Rai — AI Automation Engineer
GitHub: github.com/bitturai-automation
```
