# Multi-Source AI Lead Aggregator

Unified lead capture system that processes leads from Instagram, Discord, and web forms — all through one AI-powered workflow. The AI doesn't just score leads — it also responds to customers in real time.

## What it does
- Receives leads from multiple sources: Instagram DMs, Discord messages, and website forms
- Normalizes data from all sources into one unified format
- AI scores each lead (Hot/Warm/Cold)
- AI generates and sends a reply to the customer
- Logs all leads to Google Sheets
- Alerts on hot leads via Telegram

## How it works
1. Lead comes in from any source (Instagram, Discord, or web)
2. Switch node detects the source
3. Edit Fields normalizes the data
4. AI analyzes the lead and generates a reply
5. The reply is sent back to the customer via the same channel
6. Google Sheets stores the lead
7. Telegram alerts if the lead is hot

## Tech Stack
- n8n
- Google Gemini (AI)
- Google Sheets
- Telegram
- Discord API

## Why it matters
Businesses receive leads from multiple platforms. This system unifies them all into one pipeline — and ensures every lead gets an instant, intelligent response.
