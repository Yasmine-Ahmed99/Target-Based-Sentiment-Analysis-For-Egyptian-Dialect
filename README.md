# Arabic Aspect-Based Sentiment Analysis (ABSA)

This project implements an Aspect-Based Sentiment Analysis (ABSA) system for Arabic reviews using:

- 🧠 AraBERT (HuggingFace) for sentiment classification
- 🧾 SpaCy + Stanza for POS tagging and dependency parsing
- 🌐 Flask for serving a simple web interface/API

## 🧩 Features

- Extracts **target-aspect pairs** from Arabic reviews (e.g., "الخدمة - ممتازة")
- Predicts sentiment polarity: **Positive, Negative, Neutral**
- Supports batch processing of multiple sentences
- Outputs results as structured data (JSON,)

---

## 📦 Project Structure

```bash
arabic-absa/
├── app.py                 # Flask app
├── templates/
│   └── index.html         # Frontend (optional)
├── static/
│   └── style.css          # Styling (optional)
├── requirements.txt       # Python dependencies
└── README.md              # This file
