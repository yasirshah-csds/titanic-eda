# 🚢 Titanic Dataset — Exploratory Data Analysis & Survival Prediction

A data analysis and machine learning project applying the classic [Kaggle Titanic dataset](https://www.kaggle.com/competitions/titanic) to explore passenger survival patterns and build a predictive classification model.

---

## 📌 Project Overview

This project works through the full data science pipeline on one of the most well-known datasets in machine learning: load, clean, explore, visualize, and model. The goal is to understand which passenger features most influenced survival, and to build a model that predicts survival outcomes from those features.

---

## 🔍 Key Questions Explored

- Which passenger demographics had the highest survival rates?
- How did class, gender, and age interact with survival outcomes?
- Can a machine learning model accurately predict survival from available features?

---

## 📊 Visualizations Produced

- Survival rate breakdowns by passenger class, gender, and age group
- Distribution plots for key numerical features (age, fare)
- Correlation heatmap across all features
- Comparative bar charts for categorical survival analysis

---

## 🧠 Technical Highlights

- **Data cleaning**: Handled missing values across age, cabin, and embarkation columns using imputation strategies
- **Feature engineering**: Transformed categorical variables for use in the model
- **Predictive modeling**: Built a classification model using scikit-learn to predict passenger survival
- **Model evaluation**: Assessed performance using accuracy metrics

---

## 🛠️ Tech Stack

- **Python**
- **pandas** — data loading, cleaning, and transformation
- **matplotlib** — core plotting
- **seaborn** — statistical visualizations and heatmaps
- **scikit-learn** — machine learning model training and evaluation

---

## 📁 Dataset

- **Source**: [Kaggle — Titanic: Machine Learning from Disaster](https://www.kaggle.com/competitions/titanic)
- **Size**: 891 training rows × 12 columns
- **Features**: Passenger class, name, sex, age, siblings/spouses aboard, parents/children aboard, ticket, fare, cabin, embarkation port, survival label

---

## 🚀 Getting Started

```bash
# Clone the repository
git clone https://github.com/SkillzNoHax/titanic-eda.git
cd titanic-eda

# Install dependencies
pip install pandas matplotlib seaborn scikit-learn

# Launch the notebook
jupyter notebook titanic.ipynb
```

---

## 👤 Author

**Skillz** — Data Science Student, University of Michigan–Dearborn  
🔗 [GitHub](https://github.com/SkillzNoHax)
