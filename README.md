# School Projects – Data Science & Machine Learning

This repository contains several projects completed as part of my academic curriculum.  
The goal of these projects is to apply **data analysis**, **feature engineering**, and **predictive modeling** techniques to real-world datasets.

---

## Included Projects

### Parkinson’s Disease Classification

**Description:**
Classifying patients with Parkinson’s Disease based on medical and voice-related features.

**Key Highlights:**

- Data preprocessing and normalization of medical features
- Feature selection comparison:

  - All features
  - Wrapper-based selection method
- Analysis of the **accuracy–stability trade-off** in medical diagnostics
- Model comparison:

  - K-Nearest Neighbors (KNN)
  - Support Vector Machine (SVM)
  - Random Forest
---
### Bitcoin Price Prediction (Classification)

**Description:**  
Predicting Bitcoin price trends (**UP / DOWN**) over a 30-minute horizon.

**Key Highlights:**
- Data cleaning and processing of historical **OHLCV** data  
- Feature engineering with technical indicators:
  - RSI
  - MACD
  - Moving Averages
- Model comparison:
  - Random Forest
  - XGBoost
  - LSTM

---

### SNCF Delay Forecasting (Regression)

**Description:**  
Predicting train delays across the **SNCF (French National Railway)** network.

**Key Highlights:**
- Handling complex **time-series** and **categorical** data
- Feature engineering:
  - Cyclic date encoding (sine / cosine)
  - Target Encoding for high-cardinality categorical variables
- Regression models:
  - LightGBM
  - Random Forest
  - Ridge / Lasso Regression
- Hyperparameter optimization:
  - BayesSearchCV
  - RandomizedSearchCV

---

## Technologies Used

- **Language:** Python  
- **Libraries:**  
  - Pandas
  - Pytorch
  - NumPy  
  - Scikit-learn  
  - LightGBM  
  - Category Encoders  
  - Matplotlib  
  - Seaborn
