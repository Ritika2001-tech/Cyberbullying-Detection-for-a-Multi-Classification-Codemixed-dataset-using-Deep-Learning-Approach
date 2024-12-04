# Cyberbullying-Detection-for-a-Multi-Classification-Codemixed-dataset-using-Deep-Learning-Approach
# Introduction 
This project focuses on detecting cyberbullying in multiclass code-mixed Hinglish (a mix of hindi and english) datasets using deep learning techniques. The approach demonstrated superior performance compared to traditional machine learning methods
## Key Contribution
### 1. Development of the MC-Hinglish 2.0 Dataset
- **Dataset Size**: 18,314 annotated comments.
- **Data Split**: 
  - Training: 14,652
  - Validation: 1,831
  - Testing: 1,831
- **Dataset Features**: Multi-class annotations for seven categories: 
  - **Not Cyberbullying**
  - **Age**
  - **Gender**
  - **Religion**
  - **Mockery**
  - **Abusive**
  - **Offensive**

### 2. Enhanced Cyberbullying Detection Model
- Developed an **advanced deep learning model** specifically designed to handle the complexities of **code-mixed Hinglish**.
- Focused on improving the **accuracy** and **robustness** of multi-class cyberbullying detection.

### 3. Evaluation and Analysis
- Comprehensive analysis of **machine learning (ML)** and **deep learning (DL)** models.
- **Metrics**: Accuracy (Train & Test), Precision, Recall, and F1-Score.

---
## Experimental Results

### Machine Learning (ML) Models
Multiple ML models were evaluated on the **MC-Hinglish 2.0** dataset to establish a baseline. Key results are summarized below:

| **Model**              | **Train Accuracy** | **Test Accuracy** | **Precision** | **Recall** | **F1-Score** |
|------------------------|--------------------|-------------------|---------------|------------|--------------|
| Logistic Regression    | 0.5532            | 0.5298           | 0.5097        | 0.5112     | 0.5298       |
| Random Forest          | 0.9999            | 0.5571           | 0.5895        | 0.5217     | 0.5571       |
| XGBoost                | 0.9999            | 0.5740           | 0.5608        | 0.5615     | 0.5740       |
| Naive Bayes (Gaussian) | 0.4746            | 0.4626           | 0.4716        | 0.4364     | 0.4626       |
| Naive Bayes (Multinomial) | 0.3372         | 0.3463           | 0.1141        | 0.2412     | 0.3463       |
| SVM                    | 0.7798            | 0.5877           | 0.5820        | 0.5670     | 0.5877       |
| Voting Classifier      | 0.9158            | 0.5713           | 0.5735        | 0.5497     | 0.5713       |

### Deep Learning (DL) Models
Deep learning models outperformed ML models by leveraging the **contextual and sequential** nature of the data.

| **Model**     | **Train Accuracy** | **Test Accuracy** | **Precision** | **Recall** | **F1-Score** |
|---------------|--------------------|-------------------|---------------|------------|--------------|
| LSTM          | 0.9494            | 0.5734           | 0.5737        | 0.5802     | 0.5735       |
| BERT          | 0.9880            | 0.7586           | 0.7602        | 0.7586     | 0.7532       |
| mBERT         | 0.9960            | 0.7586           | 0.7584        | 0.7586     | 0.7554       |
| Hing Llama    | 0.9373            | 0.7324           | 0.6652        | 0.6582     | 0.7324   
---
## Key Features
1. **Advanced DL Models:**  Implemented state-of-the-art deep learning models, including LSTM, BERT, and mBERT, to handle the linguistic complexities of Hinglish.
2. **Hing Llama:**
   - Hing Llama model, based on the Llama 3.1 8B Instruct architecture, was fine-tuned using the Unsloth framework with a LoRA adapter to adapt it for code-mixed cyberbullying detection.
3. **Extensive Evaluation:** Compared traditional machine learning approaches with advanced deep learning techniques, emphasizing the superiority of DL models for code-mixed datasets.
4. **Custom Hinglish Dataset:** Introduced the MC-Hinglish 2.0 dataset, specifically curated for multi-class cyberbullying detection tasks in a code-mixed Hinglish context.
