# 💰 FinGenius – Your Smart Finance Buddy (Hackathon Project)

FinGenius is a Generative AI-powered personal finance assistant designed specifically for users in Pakistan. Built during the Pak Angels GenAI Hackathon, it empowers users to manage money smarter — set savings goals, track spending, get financial advice, and receive smart reminders, all with a friendly chatbot interface.

---

## 🚀 Features

### 🎯 Must-Have Features
- **User Profile Form** – Collects income, expenses, and savings targets using Gradio UI.
- **Budget Calculator** – Computes savings using simple logic: `Savings = Income - Expenses`.
- **Goal Tracker** – Visual tracker using progress bars to show savings progress.
- **Finance Chatbot** – Uses Groq API (LLaMA3) to answer user questions and provide advice.
- **SMS Alerts** – Sends reminders or spending alerts via Twilio WhatsApp API.
- **Dashboard** – Visualizes budget data using Plotly charts (pie, bar, etc.).

---

### ✨ Bonus Features (If time allows)
- **AI Financial Tips** – Suggests ways to save or spend better using dynamic LLM prompts.
- **Tax Estimator** – Uses hardcoded Pakistani tax brackets to estimate taxes.
- **Receipt OCR** – Scans receipts with TabbyOCR to auto-log spending.
- **Finance RAG (Optional)** – Retrieves answers from SBP/blog articles using LangChain.

---

## 🧠 Tech Stack

| Tool | Purpose |
|------|---------|
| Gradio | UI forms, chatbot, dashboard |
| Python | Core logic and processing |
| Groq API | Generative AI responses |
| Twilio API | SMS/WhatsApp alerts |
| Plotly | Charts and visualizations |
| TabbyOCR | Receipt scanning |
| LangChain (Optional) | RAG from bank articles |

---

## 📦 Installation

```bash
git clone https://github.com/your-team-name/fingenius.git
cd fingenius
pip install -r requirements.txt
python app.py
````

---

## 📁 Project Structure

```
fingenius/
├── app.py
├── utils/
│   ├── finance_logic.py
│   ├── chatbot.py
│   ├── sms_alerts.py
│   └── ocr.py
├── static/
│   └── sample_receipts/
├── data/
│   └── dummy_user_data.json
├── requirements.txt
└── README.md
```

---

## 📤 Deployment Notes

* Run via local Gradio app or deploy to Hugging Face Spaces / Streamlit.
* For SMS alerts, configure `TWILIO_ACCOUNT_SID`, `TWILIO_AUTH_TOKEN`, and verified number in `.env`.

---

## 📅 Built With ❤️ During

**Pak Angels GenAI Hackathon 2025**
Powered by Aspire Pakistan

---

## 👨‍💻 Team KULYAE (Rearranged Name Pending)

Team lead: [Kashif Ali](https://www.linkedin.com/in/kashif-ali-arain)
QUEST Nawabshah – 6th Semester BSIT Student

Thanks to all team members for collaboration, late-night coding, and awesome vibes.

---

````

---

## 📄 `requirements.txt`

```txt
gradio==4.15.0
openai
groq
twilio
plotly
tabbyocr
langchain
faiss-cpu
python-dotenv
pandas
matplotlib
tqdm
requests
````
