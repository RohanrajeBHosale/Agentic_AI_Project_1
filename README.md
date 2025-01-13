# Phi Agent Project: Multi-AI Financial & Web Research

This project demonstrates the use of the `phi` library to create a multi-agent system for financial research and web information gathering. It leverages Groq's LLMs, along with the `yfinance` and `duckduckgo` tools.

## Overview

This project creates three distinct AI agents:

1.  **Web Search Agent:** Responsible for searching the internet using DuckDuckGo to gather relevant information.
2.  **Financial Agent:**  Utilizes `yfinance` to retrieve financial data such as stock prices, analyst recommendations, and fundamental data.
3.  **Multi-AI Agent:**  Orchestrates the other two agents to perform complex tasks, such as gathering financial data and summarizing news articles about a specific company.

These agents work together to provide comprehensive answers, combining both financial insights and current news.

## Features

- **Multi-Agent System:** Integrates specialized agents to handle different tasks.
- **Groq LLMs:** Leverages the power of Groq's language models.
- **Financial Data:** Uses `yfinance` to access stock information, analyst recommendations, and fundamental data.
- **Web Search:** Uses DuckDuckGo to find news and relevant information.
- **Clear Output:** Provides well-formatted, markdown output (including tables where appropriate).
- **Streaming output:**  Output is streamed in real-time.
- **Easy-to-Use:** Simple, modular design for easy extension.

## Getting Started

### Prerequisites

- **Python 3.7+**
- **A Groq API Key:** Obtain one from the Groq website.
- **Environment Variables:** Install `python-dotenv`
  ```bash
  pip install python-dotenv
