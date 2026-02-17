# 📈 Automated Financial Sentiment Analysis Tool

## Overview
This project is a specialized monitoring system designed to track financial market sentiment in real-time. By integrating financial news aggregators with localized NLP models, the system provides instant, actionable insights for traders and analysts.

## Key Features
- Real-time Data Fetching: Automated scraping and API integration with Yahoo Finance.

- Localized NLP Processing: Utilizes FinBERT (Financial BERT), a model specifically pre-trained on financial corpora, ensuring high accuracy in sentiment scoring (Bullish/Bearish/Neutral).

- Automated Delivery: A dedicated Telegram Bot that pushes instant notifications with sentiment scores and news summaries directly to the user.

- R&D Approach: Developed and tested within Jupyter Notebooks for rapid prototyping and data visualization.

## Technical Workflow
1. Data Acquisition: Scheduled tasks to pull the latest headlines and news bodies.

2. Analysis: The news text is cleaned and passed through the FinBERT pipeline to calculate sentiment weights.

3. Filtering: Only high-confidence or market-moving signals are selected.

4. Notification: The Telegram API formats the data into a readable alert for mobile/desktop.

## Tech Stack
- Language: Python

- AI Models: FinBERT (Hugging Face)

- APIs: Yahoo Finance (yfinance), Telegram Bot API

- Tools: Jupyter Notebook (prototyping)

Project Screenshots
(Сюди ідеально підійде скріншот із телефону або десктопу, де видно повідомлення від твого Telegram-бота з новиною та оцінкою)
