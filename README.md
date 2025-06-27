# Crypto-Analyst-Bot


A powerful, multi-layered market intelligence automation system built with n8n, delivering real-time cryptocurrency analytics, sentiment classification, technical indicators, and actionable trading insights directly to Telegram.

🚀 Overview
This project is a next-generation automated trading assistant designed using n8n, enabling users to query any cryptocurrency (e.g., BTC, ETH, SOL) and receive:

🔍 Real-time market data from Binance

🧠 Sentiment analysis from live crypto news headlines

📊 Multi-timeframe technical indicators (15m, 1h, 1d)

🧮 Price action and volatility modeling

🎯 Trade setup insights: risk/reward levels, stop-loss & take-profit

🤖 AI-powered summaries using Langchain + Google Gemini + Mistral

Delivered instantly via Telegram Bot in beautifully formatted, HTML-enhanced messages.

💡 What Makes This Unique
✅ Unified Market Analysis Engine
This is not a single-feature bot—it merges technicals, sentiment, volatility, momentum, and AI in one structured workflow.

🧠 AI-Augmented Insights
It integrates Google Gemini & Mistral Cloud APIs to generate human-readable summaries, transforming raw data into decision-ready narratives.

🔁 Fully Automated & Modular
Built in n8n’s visual environment, this system is 100% event-driven. Input a trading pair (like SOL) on Telegram and get complete analytics in seconds—no manual intervention.

🧰 Designed for Traders
Includes:

RSI, MACD, Stoch RSI, Bollinger Bands, ATR

Multi-timeframe candle data (15m, 1h, 1d)

Price action insight: support/resistance recognition

Volatility modeling (ATR & 7-day history)

Momentum scoring and trend prediction

📰 Live Sentiment Analysis
Pulls news via NewsAPI, filters noise, and computes long-term and short-term sentiment using fine-tuned AI agents. It understands macro tone shifts in the news cycle.



🛠️ Setup Instructions
1. Prerequisites
n8n installed

API Keys:

Binance (no key needed for public data)

NewsAPI

Mistral Cloud

Google Gemini / PaLM

2. Import the Workflow
Go to your n8n editor → Import → Select My_workflow2.json

3. Set Credentials
Configure credentials for:

Telegram API

Mistral Cloud

Google Gemini

NewsAPI

4. Activate Workflow
Turn the workflow to active. Use /start or enter any trading pair in Telegram to begin.

🏗 Future Roadmap
✅ Whale tracking via order books

✅ Funding rate anomalies integration

🔄 Twitter/X sentiment parsing

📈 Chart snapshots using TradingView API

📡 Web dashboard for portfolio summary



