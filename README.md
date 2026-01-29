# Sampling Assignment – Credit Card Dataset

## Problem Statement
The objective of this assignment is to handle a highly imbalanced credit card dataset using different sampling techniques and to study their impact on the accuracy of various machine learning models.

---

## Dataset
The dataset used is a credit card dataset containing fraudulent and non-fraudulent transactions with severe class imbalance.

Source:
Creditcard_data.csv

---

## Tasks Performed
1. Loaded and analyzed an imbalanced dataset  
2. Converted the dataset into a balanced class dataset  
3. Created multiple samples from the balanced dataset  
4. Applied five different sampling techniques  
5. Trained five different machine learning models  
6. Compared accuracy results to identify the best sampling technique for each model  

---

## Sampling Techniques Used
- Sampling1: No additional sampling  
- Sampling2: Random Over Sampling  
- Sampling3: Random Under Sampling  
- Sampling4: SMOTE  
- Sampling5: SMOTETomek  

---

## Machine Learning Models
- M1: Logistic Regression  
- M2: Decision Tree  
- M3: Random Forest  
- M4: Naive Bayes  
- M5: Support Vector Machine  

---

## Evaluation Metric
- Accuracy

---

## Results Summary
Random Under Sampling (Sampling3) achieved the highest accuracy for most models including Logistic Regression, Decision Tree, Random Forest, and Support Vector Machine.  
Naive Bayes performed best without additional sampling.

---

## Tools and Libraries
- Python  
- Google Colab  
- Scikit-learn  
- Imbalanced-learn  
- Pandas  
- NumPy  

---

## Conclusion
The experiment demonstrates that sampling techniques significantly influence model performance when dealing with imbalanced datasets. Random Under Sampling proved to be the most effective technique for this dataset.

---

## Repository Structure
