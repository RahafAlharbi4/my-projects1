# Rapid Machine Learning Modelling for Predicting Environmental Sustainability Indicators (Water Potability)

## Overview
This project explores the use of **rapid machine learning modeling** to predict water potability based on physical and chemical water-quality indicators.

The goal is to support environmental sustainability through data-driven classification of potable vs. non-potable water using machine learning techniques.

---

## Objective
To compare and evaluate machine learning models for water potability prediction and identify the most accurate and reliable algorithm.

---

## Dataset
- Source: Kaggle (Water Quality Dataset)
- Initial records: 3276
- Final records after preprocessing: 3996 (after balancing)

### Features:
- pH  
- Hardness  
- Solids  
- Chloramines  
- Sulfate  
- Conductivity  
- Organic Carbon  
- Turbidity  

---

## Data Preprocessing
- Missing values replaced using mean imputation  
- Duplicate records removed  
- Dataset balanced using AI-based synthetic generation techniques  

---

## Machine Learning Models Used
- Decision Tree  
- Random Forest  
- Gradient Boosted Trees (GBOOST)

---

## Methodology
The project was implemented using **RapidMiner**, applying:
- Split validation (70/30)
- 10-fold Cross Validation
- Auto Model comparison
- Correlation analysis
- Feature selection (Select Attributes)

---

## Feature Selection Results
Most important features:
- pH  
- Solids  
- Chloramines  
- Conductivity  

---

## Results

### Model Performance (Cross Validation)
- Decision Tree: Lowest accuracy, unstable performance  
- Random Forest: Improved stability and generalization  
- Gradient Boosted Trees: **Best performance (72.05% accuracy)**  

---

## Key Findings
- Ensemble models outperform single Decision Tree models  
- GBOOST is the most accurate and stable model  
- Water quality prediction is influenced by multiple interacting features  
- Dataset imbalance significantly affects model performance  

---

## Conclusion
This study demonstrates that machine learning, particularly **Gradient Boosted Trees**, can effectively support environmental sustainability by predicting water potability.

The results highlight the importance of:
- Data preprocessing  
- Feature selection  
- Ensemble learning techniques  

---

## Tools Used
- RapidMiner Studio  
- Machine Learning (Auto Model + Manual Modeling)  
- Cross Validation  
- Correlation Analysis  

---

## Files Included
- Research Paper (PDF)  
- RapidMiner process files  
- Dataset (processed version)  
- Visual results (graphs and model outputs)  

---

## ⚠️ Note
Some visual outputs and RapidMiner files may require downloading to view properly.
