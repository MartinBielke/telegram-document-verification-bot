# 🤖 Telegram Eligibility Verification Bot

A Python-based Telegram bot that performs fast record verification using a National ID number and generates consolidated reports from multiple administrative data sources.

---

## ✨ Features

* 🔍 Search records by National ID
* 🤖 Telegram conversational interface
* 🔄 Automatic data refresh
* 📊 Consolidated verification reports
* 🗂️ Multiple data source integration
* 📁 Local CSV or Google Sheets support
* ⚡ Lightweight and easy to deploy

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
```

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

### Create a `.env` file

```env
TELEGRAM_TOKEN=YOUR_TELEGRAM_BOT_TOKEN

# Optional
CSV_URL=YOUR_CSV_SOURCE_URL
```

### Run

```bash
python bot.py
```

If `CSV_URL` is not provided, the application automatically loads `sample_data.csv`.

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
* python-dotenv
* Google Sheets CSV API

---

## 📂 Project Structure

```
telegram-eligibility-verification-bot/
│
├── telegram_eligibility_verification_bot.ipynb
├── requirements.txt
├── README.md
├── LICENSE
├── sample.env
├── sample_data.csv
└── .gitignore

```

---

## 📄 Sample Dataset

This repository includes a synthetic dataset (`sample_data.csv`) that mirrors the structure of the production database.

All records are fictional and provided exclusively for testing and demonstration purposes.

No real personal information is included in this repository.

---

## 🔐 Environment Variables

The `.env` file must be created locally and is intentionally excluded from version control.

Create a `.env` file in the project root:

```env
TELEGRAM_TOKEN=YOUR_TELEGRAM_BOT_TOKEN

# Optional
CSV_URL=YOUR_CSV_SOURCE_URL
```

## 🔐 Environment Variables

Create a `.env` file in the project root.

The `.env` file is used for local configuration and is intentionally excluded from version control.

```env
TELEGRAM_TOKEN=YOUR_TELEGRAM_BOT_TOKEN

# Optional
CSV_URL=YOUR_CSV_SOURCE_URL
```

A `sample.env` file is included as   a template. If `CSV_URL` is not provided, the application will automatically load `sample_data.csv`.


### Behavior

* If `CSV_URL` is configured, the bot loads data from the remote CSV source.
* If `CSV_URL` is omitted, the bot automatically uses `sample_data.csv`.

---

## 📈 Future Improvements

* PostgreSQL backend
* Docker deployment
* REST API integration
* Authentication layer
* Audit logs
* Analytics dashboard

---

## 📄 License

This project is licensed under the MIT License. See the `LICENSE` file for details.

