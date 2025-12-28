# AI-Powered Log Analyzer

**AI-Powered Log Analyzer** is a modern, browser-based application designed to help developers and system administrators analyze log files quickly and efficiently. It provides **smart insights**, error explanations, and suggested fixes using an **offline rule-based knowledge base**.

---

## Features

- ✅ Parse **multiple log files** at once  
- ✅ Filter logs by **level (INFO, WARNING, ERROR, DEBUG)**  
- ✅ Search logs with **keywords**  
- ✅ Smart **insights & suggested fixes** from a built-in knowledge base  
- ✅ Export analyzed logs as **CSV reports**  
- ✅ Lightweight, fully **offline** (no external API required)  
- ✅ Interactive **charts or summary statistics** (optional)  
- ✅ Dark mode for **better readability**  

---

## Demo

![Screenshot](assets/screenshot.png)  
*(Optional: Add a screenshot of your app UI here)*

---

## Getting Started

### Clone the Repository

```bash
git clone https://github.com/bilgambuyu/ai-log-analyzer.git
cd ai-log-analyzer


## Open the App

Simply open the index.html in your browser:
open index.html

Folder Structure

ai-log-analyzer/
│
├─ index.html
├─ scripts/
│   └─ analyzer.js
├─ styles/
│   └─ style.css
├─ kb/
│   └─ knowledge_base.js
├─ logs/
│   └─ sample log files
└─ assets/
    └─ screenshots/icons

How It Works

1. Upload log files from your computer.
2. The app parses timestamps, log levels, and messages.
3. Each log message is checked against the knowledge base rules.
4. Insights are displayed in a table with suggested fixes.
5. Filter, search, or export logs as needed.

Knowledge Base

The knowledge base is stored in kb/knowledge_base.js.
Each rule has:
- Pattern: regex to match log messages
- Explanation: plain-text description
- Fix: suggested action for the issue
Users can expand or edit the knowledge base to include custom patterns.

Future Enhancements

- Real-time log monitoring
- Hybrid offline AI for advanced insights
- Interactive timeline charts
- Alerts for critical errors
- Log correlation and pattern detection

