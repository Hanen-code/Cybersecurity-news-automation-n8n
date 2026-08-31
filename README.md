# 🛡️ Cybersecurity News Automation

An automated cybersecurity news workflow built with n8n, SerpApi, Google Gemini, and Telegram.

## 📌 About the Project

This project automatically collects the latest cybersecurity news, processes the results, summarizes the news using AI, and sends the final summaries to a Telegram chat.

The goal is to automate the process of monitoring cybersecurity news and receiving concise updates without manually searching for new articles.

## ⚙️ How It Works

The workflow follows these steps:

1. ⏰ Schedule Trigger
   - Runs the workflow automatically at a scheduled interval.

2. 🔎 SerpApi
   - Searches Google for the latest cybersecurity news.

3. 💻 JavaScript
   - Processes and organizes the search results.

4. 🤖 Google Gemini
   - Summarizes the collected cybersecurity news using AI.

5. ✈️ Telegram
   - Sends the generated summaries directly to a Telegram chat.

## 🧰 Technologies Used

- n8n – Workflow automation
- SerpApi – Search API for retrieving cybersecurity news
- Google Gemini – AI-powered news summarization
- JavaScript – Data processing and formatting
- Telegram Bot API – Sending news summaries

## 🔄 Workflow

```text
Schedule Trigger
       ↓
   HTTP Request
       ↓
   SerpApi Search
       ↓
JavaScript Processing
       ↓
   Google Gemini
       ↓
   Data Formatting
       ↓
     Telegram
