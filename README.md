# 🤖 Telegram Eligibility Verification Bot

A Python-based Telegram bot that performs fast record verification using a national ID number and generates consolidated reports from multiple administrative data sources.

---

## ✨ Features

- 🔍 Search records by National ID
- 🤖 Telegram conversational interface
- 🔄 Automatic data refresh
- 📊 Consolidated verification reports
- 🗂️ Multiple data source integration
- ⚡ Lightweight and easy to deploy

---

## 🏗️ Architecture

```text
User
  │
  ▼
Telegram Bot
  │
  ▼
Data Source (CSV / Google Sheets)
  │
  ▼
Verification Engine
  │
  ▼
Formatted Report
````

---

## 🚀 Quick Start

### Clone the repository

```bash
git clone https://github.com/yourusername/telegram-eligibility-verification-bot.git
cd telegram-eligibility-verification-bot
```

### Install dependencies

```bash
pip install -r requirements.txt
```

### Configure environment variables

```env
TELEGRAM_TOKEN=YOUR_TOKEN
CSV_URL=YOUR_DATA_SOURCE_URL
```

### Run

```bash
python bot.py
```

---

## 💬 Commands

| Command   | Description                |
| --------- | -------------------------- |
| `/start`  | Start a verification query |
| `/status` | Check database status      |
| `/cancel` | Cancel current operation   |

---

## 🛠️ Tech Stack

* Python
* Pandas
* Requests
* python-telegram-bot
* Google Sheets CSV API

---

## 📂 Project Structure

```
telegram-eligibility-verification-bot/
│
├── bot.py
├── requirements.txt
├── README.md
├── LICENSE
├── sample.env
├── sample_data.csv
├── .gitignore
└── notebook.ipynb
```

---

## Dataset

This repository does not contain real records.

The included dataset is fully synthetic and intended exclusively
for testing and demonstration purposes.

The original production dataset contains sensitive information and
is therefore not distributed.

---

## Environment Variables

Create a `.env` file:

```env
TELEGRAM_TOKEN=YOUR_TELEGRAM_BOT_TOKEN
CSV_URL=YOUR_CSV_SOURCE_URL

## 📈 Future Improvements

* PostgreSQL backend
* Docker deployment
* REST API integration
* Authentication layer
* Audit logs
* Analytics dashboard

---

## 📄 License

MIT License

````

