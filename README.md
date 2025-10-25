🌾 Crop Yield Prediction — India
AI-Driven Smart Agriculture and Climate Impact Analysis
📘 Overview

This project leverages machine learning to predict crop yield across different Indian states and seasons using open data from Kaggle: Crop Production in India (by Abhinand05)
.

The goal is to empower farmers, policymakers, and agri-tech innovators with data-driven insights to make better decisions about crop planning, irrigation, and resource allocation.

🎯 Objectives

Predict per-hectare crop yield (Production / Area).

Identify key drivers like crop type, season, and region.

Visualize yield trends and regional performance.

Use explainable AI (SHAP) to understand feature influence.

🧠 Project Workflow
1️⃣ Data Preprocessing

Handle missing values, inconsistent area units, and outliers.

Compute Yield = Production / Area.

Encode categorical features (Crop, State, Season).

2️⃣ Exploratory Data Analysis (EDA)

Correlation heatmap of yield vs climatic and crop features.

Seasonal yield distribution and top-performing states visualization.

3️⃣ Feature Engineering

Create lag-based features (previous year yield).

Aggregate data at (State, Year, Season, Crop) level.

Apply scaling and encoding pipelines.

4️⃣ Modeling

Models used:

Linear Regression (baseline)

Random Forest Regressor

XGBoost Regressor

Evaluation Metrics: R², RMSE, MAE

5️⃣ Explainability

Applied SHAP for model interpretability.

Visualized top features affecting yield (e.g., rainfall, season).

📊 Results Summary
Model	R² Score	RMSE	MAE
Linear Regression	0.72	410	290
Random Forest	0.89	220	150
XGBoost	0.92	180	130

✅ XGBoost provided the best accuracy and generalization across crops and states.
