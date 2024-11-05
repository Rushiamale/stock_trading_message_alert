# Stock Price and News Alert System

This project is a Python-based application that monitors the stock price of a specified company (e.g., Tesla) and sends alerts via SMS when the stock price fluctuates significantly (by 5% or more). The alert includes recent news headlines related to the company to help understand potential reasons behind the price changes.

## Project Overview

The script performs the following steps:
1. **Fetch Stock Prices**: It retrieves daily stock prices from Alpha Vantage.
2. **Check Price Changes**: If the stock price increases or decreases by 5% or more, it triggers a news alert.
3. **Fetch Related News**: It fetches the top 3 news articles related to the company from NewsAPI.
4. **Send SMS Alerts**: It sends the news articles' titles and descriptions as SMS notifications using Twilio.

## Requirements

- Python 3.x
- Twilio Python SDK
- Requests library

Install the dependencies with:
```bash
pip install requests twilio
