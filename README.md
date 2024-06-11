# Credit Card Fraud Detection Project

This project aims to detect fraudulent credit card transactions using machine learning algorithms. The dataset consists of simulated credit card transactions from 1st Jan 2019 to 31st Dec 2020, covering transactions from 1000 customers across 800 merchants.

## Objective

The primary objective of this project is to develop a model that can accurately identify fraudulent transactions, thereby helping financial institutions mitigate losses due to fraud.

## Dataset

The dataset contains information about credit card transactions, including transaction amount, merchant details, customer demographics, and a label indicating whether the transaction is fraudulent or legitimate.

## Approach

Three machine learning algorithms were tested for this project:
- Logistic Regression
- Decision Tree
- Random Forest

The models were evaluated based on various metrics including accuracy, precision, recall, F1-score, and ROC AUC.

## Results

### Logistic Regression:
- High accuracy, low precision, and recall.
- Not ideal for imbalanced datasets like fraud detection.

![logistic regression](https://github.com/anurashikvk/Afame-Technologies/assets/134492695/c3c4d8d5-af28-4937-8cdf-c852cd24a963)


### Decision Tree:
- Balanced precision and recall.
- Highest F1-score and ROC AUC among the three models.
- Recommended choice for this project.

![decision tree](https://github.com/anurashikvk/Afame-Technologies/assets/134492695/1fa16109-c725-4a75-a927-fb9e0f3c2e69)


### Random Forest:
- Highest precision, but low recall.
- May miss a significant number of actual fraud cases.

![random forest](https://github.com/anurashikvk/Afame-Technologies/assets/134492695/9a19a4b9-313e-4b16-b501-9c5f0b24fbe9)


## Conclusion

Based on the evaluation metrics, the **Decision Tree** model is recommended for this project due to its balanced performance in detecting fraud while minimizing false positives.

---

Feel free to reach out if you have any questions or suggestions!






