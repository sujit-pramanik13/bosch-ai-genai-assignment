# Bosch AI & GenAI Specialist Assignment

## Candidate Information
- Name: Sujit Pramanik
- Role Applied: AI & GenAI Specialist

---

## Project Overview

This project builds a machine learning classification model to predict loan approval status and analyzes demographic bias in model predictions.

The objective was to:
- Train a classifier for loan approval prediction
- Evaluate performance using standard ML metrics
- Analyze fairness across demographic groups
- Perform statistical bias testing

---

## Model Used
- Logistic Regression
- OneHotEncoding for categorical features
- Standard Scaling for numerical features
- Pipeline-based implementation for reproducibility

---

## Model Performance

- Accuracy: ~89%
- Precision: Strong positive class performance
- Recall: Balanced detection
- ROC-AUC: High discrimination ability (~0.94)

Optimal threshold selection was performed using Youden’s J statistic.

---

## Bias & Fairness Analysis

### Demographic Evaluation
Approval rates and ROC curves were analyzed across:
- Gender
- Education Level
- Home Ownership Status

### Key Findings
- Noticeable TPR gap between male and female groups
- Statistical testing using Chi-Square confirmed significant association (p < 0.05)

This suggests measurable demographic disparity in predictions.

---

## Repository Structure

- `bosch_ai_genai_assignment.ipynb` → Complete reproducible notebook
- `loan_data.xlsx` → Dataset
- `main.py` → Supporting script (if required)

---

## Conclusion

The model performs strongly in predictive accuracy. However, fairness evaluation highlights the importance of bias mitigation techniques before real-world deployment.

---

