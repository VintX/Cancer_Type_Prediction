# Cancer Type Prediction 🧬

This project uses machine learning models to predict cancer types based on biological data features.

The used dataset can be collected on here : https://www.kaggle.com/datasets/khushikyad001/cancer-patient-data-in-denmark

## 📌 Overview

We compare three classification models:
- Support Vector Machine (SVM)
- Naive Bayes
- Deep Neural Network (DNN using TensorFlow)

All models are evaluated on accuracy, precision, recall, and F1-score.

## 🗂️ Files

- `Cancer_Type_Prediction.ipynb`: Jupyter notebook containing full implementation and evaluation of models.

## ⚙️ Technologies Used

- Python
- Pandas, NumPy, scikit-learn
- TensorFlow / Keras (for DNN)
- Google Colab / Jupyter Notebook

## 🧪 Model Performance Summary

| Model       | Accuracy | Precision | Recall | F1 Score |
|-------------|----------|-----------|--------|----------|
| SVM         | 15.67%   | 7.49%     | 15.44% | 9.90%    |
| Naive Bayes | 14.83%   | 15.21%    | 14.86% | 14.84%   |
| DNN         | 15.83%   | 11.77%    | 15.90% | 9.52%    |

## ✅ Future Improvements

- Normalize and balance dataset
- Use feature selection techniques
- Add dropout and early stopping for DNN
- Try other models like Random Forest, XGBoost

## 📥 Getting Started

To run this notebook:

1. Clone the repo:
   ```bash
   git clone https://github.com/your-username/Cancer_Type_Prediction.git
