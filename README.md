# Predicting Healthcare Expenditures: A Regression Analysis Approach

**Course:** ADSC2020 – Regression for Applied Data  
**University:** Thompson Rivers University  
**Semester:** Winter 2024  

**Submitted To:** Prof. Sean Hellingman  
**Submitted By:**  
- Akansha Bhargavi (T00736533)  
- Solomon Maccarthy (T00734513)  
- Viswateja Adothi (T00736529)  

---

## Project Overview

This project applies regression analysis techniques to predict individual healthcare expenditures using demographic, behavioral, and health-related data. The aim is to understand key factors influencing insurance charges and build predictive models to assist stakeholders in healthcare cost management.

---

## Dataset Description

The dataset contains the following key variables:  
- **Age**  
- **Sex**  
- **BMI (Body Mass Index)**  
- **Number of Children**  
- **Smoker Status**  
- **Region**  
- **Charges** (Target variable)

*Dataset source:* [Kaggle Insurance Dataset](https://www.kaggle.com/datasets/mirichoi0218/insurance)

---

## Methodology

1. **Exploratory Data Analysis (EDA)**: Visualizations and descriptive statistics to understand variable distributions and relationships.  
2. **Variable Selection & Multicollinearity Check**: Correlation and VIF analysis to select predictors.  
3. **Modeling**:  
   - Simple Linear Regression  
   - Multiple Linear Regression (including interaction terms)  
   - Generalized Linear Models (GLMs) with inverse Gaussian family to handle assumption violations.  
4. **Model Diagnostics**: Checking assumptions (linearity, normality, homoscedasticity), residuals analysis, Cook’s distance for outliers.  
5. **Prediction & Evaluation**: Performance measured via R², RMSE, and MAE.

---

## Key Findings

- Significant predictors include smoking status, BMI, and age.  
- GLMs effectively addressed violations of linear regression assumptions.  
- The final model explains approximately 75% of the variability in insurance charges.  
- Model diagnostics and transformations were essential for improving model validity.

---

## Project Structure

```
├── data/                # Dataset files  
├── scripts/             # R scripts for EDA, modeling, diagnostics  
├── report/              # Project report (PDF/DOCX)  
├── presentation/        # Presentation slides (PPT/PDF)  
└── README.md            # This documentation file  
```

---

## How to Run

1. Clone the repository.  
2. Open RStudio and set the working directory to the project folder.  
3. Install necessary packages (see `scripts/packages.R` if provided).  
4. Run scripts in order: EDA → Modeling → Diagnostics → Prediction.

---

## Authors

- Akansha Bhargavi  
- Solomon Maccarthy  
- Viswateja Adothi  

---

## References

- Kaggle Insurance Dataset: https://www.kaggle.com/datasets/mirichoi0218/insurance  
- R Documentation and statistical references as cited in the report.
