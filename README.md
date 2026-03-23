# SocioBuzz — Social Media Trend Prediction Dashboard

> Predict the viral potential of a social media post **before** it goes live.

[![Live Demo](https://img.shields.io/badge/Live%20Demo-Streamlit-FF4B4B?logo=streamlit&logoColor=white)](https://sociobuzz-dashboard-fyp.streamlit.app/)

---

## 🚀 Try It Live

**No installation needed** — just open the app in your browser:

👉 **[https://sociobuzz-dashboard-fyp.streamlit.app/](https://sociobuzz-dashboard-fyp.streamlit.app/)**

---

## What is SocioBuzz?

SocioBuzz is a machine learning-powered web application built as a Final Year Project (FYP). It combines engagement analysis, sentiment scoring, and temporal growth signals to estimate whether a social media post is likely to go viral — across six major platforms.

## Features

- **Viral probability prediction** using XGBoost, Random Forest & Logistic Regression
- **Sentiment & toxicity analysis** via VADER NLP (auto-detected from post text)
- **Multi-platform support** — Twitter, Instagram, Facebook, YouTube, Reddit, TikTok
- **Interactive Analytics dashboard** with engagement insights and hashtag trends
- **Content recommendations** generated from your prediction results

## Built With

| Tool | Purpose |
|------|---------|
| Python | Core language |
| Streamlit | Web app framework |
| Scikit-learn | ML preprocessing & models |
| XGBoost | Gradient boosting classifier |
| Plotly | Interactive charts |
| VADER Sentiment | NLP sentiment scoring |

---

## Running Locally

If you'd prefer to run the project on your own machine:

1. Clone the repository
   ```bash
   git clone https://github.com/your-username/SocioBuzz.git
   cd SocioBuzz
   ```

2. Run the notebook — this installs dependencies and generates the model artifacts automatically

3. Then start the app:
   ```bash
   streamlit run app.py
   ```

> **Note:** The notebook must be run first to generate the `.joblib` model files used by the app.

---

## Project Structure

```
SocioBuzz/
├── app.py                    # Streamlit application
├── Notebooks/
│   └── SocioBuzz_EDA_Modelling.ipynb
├── Other_imp_byproducts/     # Trained model artifacts (.joblib)
├── Datasets/                 # Raw and processed data
└── requirements.txt
```

---

*Built as part of a Final Year Project (FYP).*
