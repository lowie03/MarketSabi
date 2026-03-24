# MarketSabi: The Smart Ledger for Nigerian SMEs

## Project Overview
MarketSabi is a digital inclusion tool designed for Nigerian market traders who rely on paper-based sales ledgers. By sending a photo of handwritten records to a Telegram bot, the system uses AI vision to extract data into a structured Google Sheet, building a formal financial identity.

## Tech Stack
- **Automation**: n8n
- **AI Model**: Gemini 2.5 Flash (Vision & Analysis)
- **Database**: Google Sheets
- **Interface**: Telegram Bot API

## How It Works
1. **Input**: Vendor takes a photo of their handwritten sales book and sends it to the Telegram Bot.
2. **Extraction**: n8n triggers the AI vision model to transcribe the ledger into JSON data.
3. **Storage**: Data is cleaned via JavaScript and appended to a Google Sheet.
4. **Coaching**: The AI Coach analyzes the history and sends business advice back in Nigerian Pidgin.

## Impact
This project addresses the **Financial Inclusion** pillar by helping "invisible" traders build a verifiable digital history, making them eligible for formal banking services and credit.

## Live Demo
You can interact with the live MarketSabi bot on Telegram here: [https://t.me/Yamskibot]
