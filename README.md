# Sleep-Disorder-Risk-Prediction-Using-Machine-Learning
:

🛌 Sleep Disorder Prediction Using Lifestyle & Biometric Data
🔍 A Machine Learning–Based Approach to Predict and Assess Sleep Disorders
📌 Overview
This project aims to predict common sleep disorders like Insomnia and Sleep Apnea using individuals' lifestyle and health attributes such as stress level, physical activity, heart rate, and sleep duration.

We apply data analysis and machine learning techniques to identify patterns and tag risk levels—helping people and healthcare professionals take early action.

🧠 Key Features
📊 Exploratory Data Analysis (EDA) using pandas, seaborn, and matplotlib

🧹 Data Preprocessing with encoding, scaling, and outlier handling

🌳 Random Forest Classifier for multi-class sleep disorder prediction

🚨 Risk Tagging System (🟢 No Risk, 🟡 Moderate, 🔴 High Risk)

📈 Visualization with KDE plots, countplots, correlation heatmaps, and line charts

📁 Dataset Used
Name: Sleep Health and Lifestyle Dataset

Source: Kaggle Dataset + chatgpt integrated synthetic records

Attributes:

Age, Gender, Occupation, BMI Category

Sleep Duration, Stress Level, Heart Rate

Physical Activity Level

Sleep Disorder (target variable)

⚙️ Tech Stack
Tool	Purpose
pandas, NumPy	Data manipulation and numeric operations
matplotlib, seaborn	Data visualization
scikit-learn	Machine learning model, preprocessing
Jupyter Notebook	Development and presentation

📌 Project Workflow
Data Cleaning & Preprocessing

Handled missing values, dropped irrelevant rows

Label encoding & one-hot encoding for categorical features

Scaled numerical features using StandardScaler

Data Analysis & Visualization

Countplot, histogram, KDE plots

Correlation heatmap to find related features

Age-group analysis via line chart

Model Building

Split data into training and testing sets

Trained a Random Forest Classifier

Evaluated with accuracy, classification report, and confusion matrix

Risk Tagging

Used predict_proba() to assign intuitive risk levels

Tagged predictions as 🟢 No Risk, 🟡 Moderate, 🔴 High Risk

📸 Sample Visuals
📍 Countplot of Sleep Disorder Types

📍 Line Chart: Average Sleep Duration by Age Group

📍 KDE Plots: Before and After Scaling

📍 Correlation Heatmap

🚀 Future Improvements
Add SHAP/LIME for model explainability

Deploy as a web app using Streamlit

Integrate with wearable data (e.g., Fitbit, Apple Watch)

Predict severity of disorders (not just type)

📜 How to Run
bash
Copy
Edit
# Step 1: Install required libraries
pip install pandas numpy matplotlib seaborn scikit-learn

# Step 2: Open the notebook
jupyter notebook Project.ipynb
🤝 Acknowledgements
Dataset from Kaggle and chatgpt(synthetic data integration)

Libraries by the open-source Python community
