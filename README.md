# mindmetrics-ai #machine-learning #explainable-ai #gradio #mental-health #data-science
an interactive web app that predicts a user’s emotional well-being score (0–100) from a short questionnaire about their daily habits, mood, and lifestyle patterns. The model is trained on clinically validated psychological datasets (like PHQ-9, GAD-7, and WHO-5), and uses Explainable AI to show which factors most affect the prediction.
# MindMetrics v2 — Emotional Well‑Being Predictor

This project predicts emotional well-being (WHO‑5 %) from self-reported questionnaire data using machine learning.

## 🚀 Features
- **Models:** XGBoost, RandomForest, MLP (auto‑compare & tune)
- **Explainability:** SHAP for global + local explanations
- **UI:** Gradio questionnaire app
- **Dataset:** Synthetic clinical-style data (can replace with WHO‑5 / PHQ‑9 / GAD‑7)

## 🧠 How to Run (Google Colab)
1. Upload `MindMetrics_v2.ipynb` to [Google Colab](https://colab.research.google.com/).
2. Run the first cell to install dependencies.
3. Run all cells sequentially to:
   - Generate synthetic data
   - Train + evaluate models
   - Launch interactive Gradio UI
   - View SHAP explainability plots

## 📊 To Use Real Data
Replace the dataset cell with:
```python
df = pd.read_csv('/path/to/your.csv')
```
Ensure your dataset has:
`sleep_hours, exercise_days, social_hours, screen_time, stress_level, phq9, gad7, mood_self, who_pct`

## 🧾 Ethical Note
This is **not a medical diagnostic tool**. It’s for educational and research purposes only.

## 🌐 GitHub Push Instructions
1. Create a new GitHub repo (example: `MindMetrics`).
2. Upload `MindMetrics_v2.ipynb` and this `README.md`.
3. Add description and tags like: `Machine Learning`, `Explainable AI`, `Mental Health`, `Gradio`, `Python`.

---
Created by **Yaavooz** 🧠✨
