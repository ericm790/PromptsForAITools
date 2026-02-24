# Akkio — Prompt Guide

## Overview
Akkio is a no-code AI platform for predictive analytics. It allows users to upload data, build machine learning models, generate predictions, and deploy AI solutions — all through an intuitive interface. Akkio specializes in lead scoring, churn prediction, revenue forecasting, and automated data workflows for agencies and business teams.

## How to Use

### System Prompt
1. Use `System_Prompt.txt` to configure AI behavior in predictive analytics workflows or chatbot integrations.
2. Adapt it for building internal no-code ML tools that guide business users through model building.

### User Prompts
- Upload your dataset, then use these prompts to guide model building and prediction.
- Clearly define your prediction target (what you're trying to predict).
- Describe the business context so the AI can recommend appropriate actions, not just predictions.

## Tips for Best Results
- **Define your goal clearly** — specify whether you want classification (yes/no) or regression (numeric value).
- **Include enough data** — aim for at least 1,000 rows and a balanced target variable for classification.
- **Describe your features** — explain what each column represents for better feature engineering.
- **Ask for explainability** — always request feature importance and reasoning behind predictions.
- **Think about deployment** — mention how you'll use the predictions (API, CRM integration, dashboard).
