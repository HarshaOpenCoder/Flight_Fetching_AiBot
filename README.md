# Flight Fetching AI Bot ✈️🤖

An AI-powered assistant that fetches **live flight details** using natural language queries.

You can ask things like:

> "Show me the status of Indigo flight 6E123 from Hyderabad to Delhi today"

and the bot will call external APIs in the background to fetch and format the result.

---

## 🧠 What this project does

- Understands **user questions in plain English** about flights.
- Uses **OpenAI** function calling / tools to:
  - Parse the user’s intent (source, destination, flight number, date, etc.).
  - Decide when to call the external flight API.
- Uses the **AviationStack API** (or similar) to get:
  - Live / recent **flight status**
  - Departure & arrival airports
  - Scheduled / actual times
  - Airline & flight number
- Responds back with a **clean, human-friendly answer**.

---

## 🏗️ Tech Stack

- **Language:** Python  
- **LLM:** OpenAI Chat Completions API (tools / function calling)  
- **Flight Data:** AviationStack API (or any flight-tracking API)  
- **Environment:** Jupyter Notebook + Python scripts

Main files (adjust if different in your repo):

- `project_fetching_train_details.ipynb` – exploration / development notebook
- `main.py` or `app.py` – main script to run the bot (if you have one)
- `requirements.txt` – Python dependencies

---

## ⚙️ Setup Instructions

### 1. Clone the repository

```bash
git clone https://github.com/HarshaOpenCoder/Flight_Fetching_AiBot.git
cd Flight_Fetching_AiBot
