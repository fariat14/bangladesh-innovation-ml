# Firm Level Innovation Analysis for Bangladesh
### Machine Learning Analysis of World Bank Enterprise Survey (WBES) Data

![Python](https://img.shields.io/badge/Python-3.10+-blue.svg)
![scikit-learn](https://img.shields.io/badge/scikit--learn-1.3+-orange.svg)
![Analytics](https://img.shields.io/badge/Focus-Data%20Analytics-green.svg)

---

## Abstract

Innovation plays a critical role in improving firm competitiveness, productivity, and long-term economic growth in emerging markets. This project investigates the firm-level drivers of innovation in Bangladesh using machine learning techniques applied to World Bank Enterprise Survey (WBES)-structured data across the 2013, 2016, and 2022 survey waves.

The analysis examines how financial access, workforce capability, technology adoption, infrastructure quality, and institutional factors relate to product and process innovation outcomes among firms.

A Random Forest classification model was used to identify the most influential predictors of innovation. The findings suggest that workforce training, R&D spending, quality certification, technology adoption, and institutional efficiency are among the strongest drivers associated with firm innovation capability.

This project demonstrates the application of machine learning methods in economic and business analytics research while highlighting how organizational and structural capabilities may influence innovation performance in emerging-market firms.

---

## Overview

This project explores the drivers of firm-level innovation in Bangladesh using machine learning techniques applied to World Bank Enterprise Survey (WBES)-structured data across multiple survey waves.

The analysis focuses on identifying the business, technological, financial, and institutional factors associated with:
- Product innovation
- Process innovation
- Combined innovation outcomes

The project follows an end-to-end analytics workflow, including:
- data preparation,
- feature engineering,
- diagnostic testing,
- machine learning modelling,
- hyperparameter tuning,
- and model evaluation.

---

## Research Questions

- Does access to finance influence innovation?
- How important are workforce training and technology adoption?
- Do infrastructure and institutional barriers reduce innovation activity?
- Which firm capabilities are most predictive of innovation outcomes?

---

## Dataset

### Survey Waves
- 2013
- 2016
- 2022

### Sample Size
- 3,382 firms

### Variable Categories

| Category | Examples |
|---|---|
| Finance Access | Bank loans, credit constraints |
| Human Capital | Worker training, skilled labor |
| ICT & Technology | Internet use, R&D spending |
| Infrastructure | Electricity obstacles, outages |
| Competition & Markets | Export activity, foreign linkages |
| Regulatory Environment | Corruption indicators, court trust |
| Firm Characteristics | Firm size, growth, age |
| Management & Ownership | Foreign degree, female leadership |

---

## Methodology

### Data Preparation
The workflow included:
- duplicate removal,
- missing value imputation,
- outlier treatment,
- feature validation,
- and wave-level standardization.

### Diagnostic Testing
Several statistical and data quality diagnostics were conducted before modelling:
- multicollinearity checks,
- heteroscedasticity tests,
- autocorrelation diagnostics,
- and class imbalance evaluation.

### Machine Learning Model
The primary algorithm used was:
- Random Forest Classifier

The model workflow included:
- hyperparameter tuning,
- class balancing,
- and stratified cross-validation.

### Evaluation Metrics
Model performance was evaluated using:
- ROC-AUC
- F1 Score
- Accuracy
- Precision
- Recall

---

## Model Performance

| Target | ROC-AUC | F1 Score | Accuracy |
|---|---|---|---|
| Product Innovation | ~0.82 | ~0.97 | ~0.94 |
| Process Innovation | ~0.81 | ~0.98 | ~0.97 |
| Combined Innovation | ~0.83 | ~0.96 | ~0.92 |

---

## Key Findings

The analysis identified the following as major predictors of firm innovation:

1. Worker training  
2. R&D spending  
3. Quality certification  
4. Technology adoption  
5. Management capability  
6. Institutional efficiency  

The findings suggest that innovation capability is closely associated with:
- workforce development,
- digital readiness,
- organizational capability,
- and reduced institutional friction.

---

## Technologies Used

| Tool | Purpose |
|---|---|
| Python | Data analysis & modelling |
| pandas | Data manipulation |
| NumPy | Numerical operations |
| scikit-learn | Machine learning |
| statsmodels | Statistical diagnostics |
| matplotlib | Visualization |
| Jupyter Notebook | Analysis workflow |

---

## Future Improvements

Potential next steps include:
- SHAP-based interpretability analysis
- XGBoost and LightGBM comparison
- Dashboard deployment using Streamlit
- Additional country-level validation

---

## Business & Policy Implications

The findings highlight the importance of:
- workforce development,
- digital transformation,
- and operational capability-building

for improving firm competitiveness and innovation capability in emerging-market firms.

---

## Author

**Faria Tabassum**  
Data Analyst | Business Analytics | Economics  

LinkedIn: https://www.linkedin.com/in/fariatabassumecon

---

## Copyright & Usage

© 2026 Faria Tabassum. All rights reserved.

This repository and its contents are provided for portfolio, educational, and research viewing purposes only.

No part of this work may be reproduced, redistributed, modified, or used commercially without explicit written permission from the author.

If referencing this work, please provide appropriate attribution and citation.
