# AI Email Categorizer

Automatically categorizes incoming emails using AI, logs them to Google Sheets, and creates tasks for urgent ones.

## What it does
- Reads incoming emails via Gmail
- AI categorizes them as: urgent, order, question, lead, spam, internal, or other
- Logs every email to Google Sheets
- Creates Google Tasks for urgent emails
- Alerts the team via Telegram
- Ignores threads already handled by a human

## How it works
1. New email arrives → Gmail triggers the workflow
2. AI analyzes and categorizes the email
3. Email data is logged to Google Sheets
4. If urgent → Google Task is created + Telegram alert is sent

## Tech Stack
- n8n
- Gmail API
- Google Gemini (AI)
- Google Sheets
- Google Tasks
- Telegram

## Why it matters
Saves time by automatically categorizing and prioritizing emails, so your team can focus on what matters most.
