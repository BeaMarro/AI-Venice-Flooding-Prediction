# 🌊 Venice AI Flooding Prediction System

An AI-powered system designed to forecast sea level rise and predict potential flooding events in the city of Venice, Italy. This project leverages time-series analysis and machine learning to provide proactive insights for urban climate resilience.

---

## 🧭 Overview

Venice faces frequent challenges from acqua alta (high tides), endangering its cultural heritage and infrastructure. This project aims to predict future sea levels to help authorities and locals take timely actions against flooding events.

- 🏫 **Institution**: Fontys University of Applied Sciences  
- 🧑‍💻 **Type**: Individual AI research project  
- 📅 **Duration**: 2 weeks (June 2024)

---

## 🔮 Machine Learning Approach

### 📈 Forecasting Model: Meta Prophet

- Chosen for its ability to handle **seasonality**, **trend shifts**, and **holidays**.
- Fine-tuned with **hyperparameter optimization** to improve forecasting precision.
- Evaluated with **R² score** using cross-validation:
  
  > 🧠 **Accuracy**: `76%` R² over 5-year projection

### 🔍 Key Engineering Steps:
- Standardized time-series data for tide and sea levels.
- Adjusted historical tide gauge readings to surface sea levels.
- Feature selection with correlation and domain-based heuristics.

---

## 🔬 Data Analysis

A multi-variable time series built from:
- 🌡️ Temperature (atmospheric)
- 🌬️ Wind speed & direction
- 🌊 Sea and tide levels

### Domain-specific insights:
- Applied conversions to align sea level readings with **official oceanographic standards**
- Cross-referenced historical flood data to verify thresholds
- Visualized correlations and seasonal cycles using Matplotlib and Seaborn

---

## 🛠️ Tech Stack
🐍 Python
📦 Prophet (Meta)
📊 Pandas, Seaborn, Matplotlib
📁 Jupyter Notebooks
📁 Data folder: data/ contains raw and cleaned datasets

---

## 📄 License
This project is shared for educational and portfolio purposes only. Commercial use, redistribution, or modification is not allowed without explicit written permission. All rights reserved © 2025 Beatrice Marro.

## 👤 Author
Beatrice Marro GitHub: https://github.com/beamarro
