
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
git clone https://github.com/<your‑username>/flight_chat.git
cd flight_chat

# Install dependencies
pip install requests
