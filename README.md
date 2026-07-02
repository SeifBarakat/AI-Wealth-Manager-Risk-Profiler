# AI Wealth Manager & Risk Profiler

A sophisticated AI-driven tool designed to analyze financial behavioral patterns and provide personalized portfolio recommendations. This project leverages machine learning to minimize human bias in financial decision-making.

## 🚀 Project Overview
This project is an End-to-End Machine Learning Pipeline that helps investors determine their "Risk Profile" (Aggressive, Moderate, or Conservative) and suggests an optimal Asset Allocation strategy.


## 🛠 Tech Stack
- Python: The core programming language.
- Scikit-Learn: Used for building the RandomForest classification model.
- Imbalanced-learn (SMOTE): Applied to handle class imbalance in financial datasets.
- Gradio: Built a professional, interactive web-based dashboard.
- Matplotlib/Seaborn: Used for exploratory data analysis (EDA) and visualizing model performance.

## 📊 Key Features
- Smart Risk Profiling: Accurately categorizes investors based on their financial profile.
- Custom Portfolio Recommendations: Tailored asset distribution advice for each risk tier.
- Interactive Dashboard: A visual interface to explore data distributions and model insights.
- Explainable AI: Visualizes "Feature Importance" to show how the model arrives at decisions.
- Multilingual Support: Interface supports both English and Arabic.

## 📉 Model Performance

By utilizing SMOTE (Synthetic Minority Over-sampling Technique), we successfully addressed data imbalances, ensuring the model performs reliably even for minority classes.

## 📋 How to Run
1. Ensure you have the dataset Finance_Trends.csv.
2. Run the notebook in Google Colab or your local environment.
3. Install the necessary dependencies:
   ```bash
   pip install -r requirements.txt
