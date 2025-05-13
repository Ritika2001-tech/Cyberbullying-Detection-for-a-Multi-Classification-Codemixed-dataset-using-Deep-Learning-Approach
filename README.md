# Cyberbullying-Detection-for-a-Multi-Classification-Codemixed-dataset-using-Machine-Learning-Approach
# Introduction 
This project focuses on detecting cyberbullying in multiclass code-mixed Hinglish (a mix of hindi and english) datasets using machine learning techniques.
## Key Contribution
### 1. Development of the MC-Hinglish 1.0 Dataset
- **Dataset Features**: Multi-class annotations for seven categories: 
  - **Not Cyberbullying**
  - **Age**
  - **Gender**
  - **Religion**
  - **Mockery**
  - **Abusive**
  - **Offensive**

---
## Experimental Results

### Machine Learning (ML) Models
Multiple ML models were evaluated on the **MC-Hinglish 1.0** dataset to establish a baseline. Key results are summarized below:

| **Model**              | **Train Accuracy** | **Test Accuracy** | **Precision** | **Recall** | **F1-Score** |
|------------------------|--------------------|-------------------|---------------|------------|--------------|
| Logistic Regression    | 0.5532            | 0.5298           | 0.5097        | 0.5112     | 0.5298       |
| Random Forest          | 0.9999            | 0.5571           | 0.5895        | 0.5217     | 0.5571       |
| XGBoost                | 0.9999            | 0.5740           | 0.5608        | 0.5615     | 0.5740       |
| Naive Bayes (Gaussian) | 0.4746            | 0.4626           | 0.4716        | 0.4364     | 0.4626       |
| Naive Bayes (Multinomial) | 0.3372         | 0.3463           | 0.1141        | 0.2412     | 0.3463       |
| SVM                    | 0.7798            | 0.5877           | 0.5820        | 0.5670     | 0.5877       |
| Voting Classifier      | 0.9158            | 0.5713           | 0.5735        | 0.5497     | 0.5713       |


