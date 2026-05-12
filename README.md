# naive-bayes-mushroom-classification
A machine learning project using Naive Bayes classification on the Mushroom Dataset with custom implementation and sklearn comparison.
# Naive Bayes Mushroom Classification

## 📌 Project Overview

This project applies the Naive Bayes classification algorithm to the Mushroom Dataset.  
The goal is to classify mushrooms as edible or poisonous using categorical features.

The project includes a custom Naive Bayes implementation and a comparison with the sklearn Naive Bayes model.

---

## 🎯 Objective

The main objectives of this project are:

- Implement Naive Bayes from scratch
- Apply Laplace smoothing
- Use log-probabilities to prevent numerical underflow
- Train and test the model using an 80/20 train-test split
- Compare the custom implementation with sklearn
- Evaluate model performance using accuracy, precision, recall, F1 score, and confusion matrix

---

## 🧠 Algorithm Used

- Naive Bayes Classifier
- Custom Naive Bayes Implementation
- sklearn Naive Bayes Model

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Jupyter Notebook

---

## 📊 Model Performance

### Custom Naive Bayes Implementation

| Metric | Score |
|---|---|
| Accuracy | 1.00 |
| Precision | 1.00 |
| Recall | 1.00 |
| F1 Score | 1.00 |

### sklearn Naive Bayes Model

| Metric | Score |
|---|---|
| Accuracy | 1.00 |
| Precision | 1.00 |
| Recall | 1.00 |
| F1 Score | 1.00 |

Both implementations produced identical predictions on the test set.

---

## 📈 Training Size Experiment

| Training Size | Test Accuracy |
|---|---|
| 20% | 0.50 |
| 40% | 1.00 |
| 60% | 1.00 |
| 80% | 1.00 |
| 100% | 1.00 |

The results show that performance improves quickly as training data increases.  
From 40% onward, the model achieved 100% test accuracy.

---

## 📁 Project Files

| File | Description |
|---|---|
| `Naive_Bayes_Classification_Report.docx` | Final project report |
| `naive_bayes_mushroom_classification.ipynb` | Main notebook/code file |
| `dataset.csv` | Mushroom dataset, if included |

---

## ✅ Key Learning

Through this project, I learned:

- How Naive Bayes classification works
- How Laplace smoothing improves probability estimation
- Why log-probabilities are useful in classification
- How to evaluate classification models
- How to compare a custom ML model with sklearn implementation

---

## 🚀 Conclusion

The Naive Bayes classifier performed very well on the Mushroom Dataset.  
Both the custom implementation and sklearn model achieved identical results, showing that the dataset features clearly separate edible and poisonous mushrooms.
