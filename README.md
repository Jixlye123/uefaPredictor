# ⚽ UEFA Match Outcome Predictor

A machine learning project that predicts the outcome (Win/Draw/Loss) of UEFA football matches using historical data and statistical features.

---

## 🚀 Features

- Predicts match outcomes based on team statistics and historical results
- Built with Python, Scikit-learn, and Pandas
- Interactive Streamlit web app to test predictions live
- Web scraping via BeautifulSoup to extract data
- Clean, ATS-friendly code with clear modularity and explanations

---

## 🧠 Model

- Classification model (Random Forest / Logistic Regression)
- Target: Win = 1, Draw = 0, Loss = -1 (from home team perspective)
- Key features: 
  - Goal difference
  - Home/away advantage
  - Neutral venue
  - Recent form (optional stretch goal)

---

## 🧰 Tech Stack

- Python 3.10+
- pandas, numpy, scikit-learn
- requests, BeautifulSoup4
- Streamlit (for frontend)
- matplotlib/seaborn (for data viz)

---

## 📈 Sample Results

```text
Accuracy: 68.92%
F1-Score: 0.70 (macro)
