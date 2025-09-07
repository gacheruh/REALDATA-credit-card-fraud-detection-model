# Credit Card Fraud Detection Project
This project involved building a machine learning system to identify fraudulent credit card transactions using the [Credit Card Fraud Detection](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)  kaggle dataset.

  * **Key Challenge:** The dataset was highly imbalanced, with only 0.17% of transactions being fraudulent.

  * **Solution:** Used **SMOTE** to synthetically generate fraudulent examples, creating a balanced dataset for the models to learn from effectively.

  * **Models Trained:** Two models were trained and evaluated:

    1. **Logistic Regression:** Excelled at finding fraud (high recall) but generated too many false alarms (very low precision), making it impractical.

    2. **Random Forest:** Proved to be the superior model. It effectively balanced the need to find fraud (83% recall) with the need to minimize false alerts (87% precision), achieving a high F1-score of 0.85.

**Result:** The final **Random Forest** model is highly effective and reliable, capable of detecting the vast majority of real fraud while ensuring legitimate transactions are rarely disrupted.
