# Mobile Banking Adoption in Emerging Economies

This project investigates mobile banking adoption patterns across **Pakistan**, **India**, and **Kenya** using synthetic data modeled on the **World Bank Global Findex 2021**. The aim is to understand what factors influence digital banking behavior in emerging markets using **machine learning and classification techniques**.

---

## Project Overview

- Analyze how demographic, financial, and geographic factors affect mobile banking usage
- Apply ML models to predict mobile banking adoption
- Compare feature importance and model performance
- Relate results to published academic literature and real-world trends

---

## Repository Contents

| File | Description |
|------|-------------|
| `Synthetic_Mobile_Banking_Data.csv` | Cleaned and labeled dataset with 1,200 individuals |
| `Mobile_Banking_Coursework2.ipynb` | Full Colab notebook (preprocessing, models, evaluation, plots) |
| `README.md` | This file |

---

## Methods Used

- **Data Preprocessing**:
  - Label Encoding
  - Feature Scaling
  - SMOTE for class balancing

- **Models Applied**:
  - `Logistic Regression`
  - `Random Forest Classifier`
  - `XGBoost Classifier`

- **Evaluation Metrics**:
  - Accuracy, Precision, Recall, F1-Score
 
  | Model               | Accuracy | Precision | Recall | F1 Score |
  |---------------------|----------|-----------|--------|----------|
  | Logistic Regression | 0.76     | 0.66      | **0.84** | 0.74   |
  | Random Forest       | **0.76** | 0.71      | 0.69   | 0.70     |
  | XGBoost             | 0.75     | **0.71**  | 0.66   | 0.68     | 

  - Confusion Matrix
  <img width="539" height="455" alt="download (16)" src="https://github.com/user-attachments/assets/1542e81b-6121-4c7b-a81e-a02ca5c3695e" />
  <img width="539" height="455" alt="download (17)" src="https://github.com/user-attachments/assets/dbc99a29-578f-4bc1-ac9b-e2cbcb010cba" />
  <img width="539" height="455" alt="download (18)" src="https://github.com/user-attachments/assets/a677c6e3-e30e-49c7-9cba-6dd63c8a0d20" />

  - ROC-AUC Curve
  <img width="547" height="435" alt="download (19)" src="https://github.com/user-attachments/assets/5115cdb1-3dce-454a-8800-4936293404f7" />
  
  - Feature Importance (XGBoost)
  <img width="684" height="435" alt="download (20)" src="https://github.com/user-attachments/assets/63964823-af92-4ae7-a6ad-51699c9685f4" />



---

## Key Insights

- 🇵🇰 **Pakistan**: Highest adoption (~39.5%), driven by platforms like Easypaisa and JazzCash.  
- 🇰🇪 **Kenya**: ~37.5% adoption, aligned with M-Pesa’s mobile money dominance.  
- 🇮🇳 **India**: ~37.25%, backed by UPI, Aadhaar and financial inclusion schemes.

> “Owns_Account” was the strongest predictor of mobile banking usage across all models.

---

## Academic Contribution

This project builds on existing literature (e.g., Jack & Suri, Chaudhary & Gupta) by applying **machine learning models** to simulate and predict individual mobile banking behavior — offering a predictive complement to prior correlational research.

---

## References

- World Bank Global Findex 2021  
- Jack, W. & Suri, T. (2011). "Mobile Money: The Economics of M-Pesa"  
- Chaudhary, R. & Gupta, K. (2021). Digital Financial Inclusion in India  
- GSMA Mobile Money Report 2022

---

## How to Run

1. Clone the repo or open the notebook in Google Colab  
2. Upload `Synthetic_Mobile_Banking_Data.csv`  
3. Run `Mobile_Banking_Coursework2.ipynb`  
4. View charts, model results, and interpretation

---

## Author

**Muhammad Aashan**  
Coursework Project — University Submission  

---

