
# ✈️ Flight‑Chat Assistant

A conversational flight‑booking demo that runs entirely from your terminal.  
It can chat in natural language to “book” flights or show real flight data from a free API.

---

## 🚀 Features
- 💬 Talk normally – e.g. `sj to la tomorrow round sat`
- 🧠 AI Mode (OpenRouter) for natural, friendly conversations
- 📡 Live‑data Mode (AviationStack) for current flight listings
- 🌐 Opens **Google Flights** automatically with route + dates pre‑filled
- 🔒 Never requests or stores real payment data

---

## 🧰 Requirements
- **Python 3.10 or newer**
- Internet connection
- The free `requests` library
- Free API accounts for:
  - [OpenRouter](https://openrouter.ai) – chat engine  
  - [AviationStack](https://aviationstack.com) – flight data

---

## ⚙️ Installation & Setup

```bash
# Clone the project
git clone https://github.com/Blueything/flight_chat.git
cd flight_chat

# Install dependencies
pip install requests

# Usage
python flight_bot.py

AI Flight Booking Chat (OpenRouter)
(Type 'exit' to quit)

You: sj to lax tomorrow round sat
Bot: Here are flights…
You: yes
# Browser opens Google Flights with SJC→LAX and your dates pre‑filled

# Structure
flight_chat/
│
├─ flight_bot.py      ← main script (AI + Automation)
├─ README.md          ← this file
├─ .gitignore         ← excludes keys, logs, .env
└─ booking_log.txt    ← optional transcript / history
