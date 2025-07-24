# Predicting-Film-Award-Recognition-Using-Production-Features
Predicting Film Award Recognition Using Production Features 
# 🏆 Predicting Film Award Recognition Using Machine Learning

Machine learning analysis that predicts Oscar and Golden Globe nominations with 82% accuracy using production features.

## 📊 Project Overview

Ever wondered what makes an "Oscar-worthy" film? This project uses machine learning to decode the patterns behind award nominations, analyzing 45,000+ films to identify the production characteristics that correlate with critical acclaim.

**Key Finding**: Films can be predicted for award nominations based solely on objective production features - before anyone even watches them.

## 🎯 Results

- **82% Accuracy** in predicting award nominations (Random Forest)
- **78% Accuracy** with Support Vector Classification
- Analyzed **45,000+ films** from 1927-2024
- Identified **key predictive features**: Release timing, genre, budget, runtime

## 💡 Key Insights

1. **Q4 Release = 3x Higher Nomination Chance**
2. **Drama + Biography genres dominate** (65% of nominations)
3. **Sweet spot runtime**: 110-150 minutes
4. **Studio prestige matters** more than budget size

## 🛠️ Tech Stack

- **Languages**: Python
- **ML Libraries**: Scikit-learn, XGBoost
- **Data Analysis**: Pandas, NumPy
- **Visualization**: Matplotlib, Seaborn
- **Datasets**: TMDB, IMDb, Oscar/Golden Globe databases

## 🚀 Quick Start

```bash
# Clone repository
git clone https://github.com/Abdinasir03/oscar-prediction-analysis.git

# Install dependencies
pip install -r requirements.txt

# Run Jupyter notebook
jupyter notebook notebooks/film_award_prediction.ipynb
