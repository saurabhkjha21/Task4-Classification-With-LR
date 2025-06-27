# Logistic Regression Binary Classification

This project demonstrates how to build a **binary classifier** using **Logistic Regression** with **Scikit-learn**, **Pandas**, and **Matplotlib**. It walks through data preprocessing, model training, evaluation, and threshold tuning.

---

##  Objective

Build and evaluate a logistic regression model to classify instances into one of two categories (binary classification).

---

##  Tools & Libraries Used

- Python
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn

---

##  Dataset

- **Used**: Breast Cancer Dataset from `sklearn.datasets`
- Features: Various medical measurements
- Target: Malignant (0) or Benign (1)

---

##  Steps Followed

1. **Data Loading & Exploration**  
2. **Train-Test Split (80-20)**  
3. **Feature Scaling using StandardScaler**  
4. **Model Training using Logistic Regression**  
5. **Evaluation:**
   - Confusion Matrix
   - Classification Report (Precision, Recall, F1-score)
   - ROC Curve and AUC
6. **Threshold Tuning**
   - Custom threshold classification using sigmoid output
   - Visualize how threshold impacts performance

---

##  Example Evaluation Metrics

- **Accuracy**: ~95%  
- **AUC Score**: ~0.98  
- **Precision/Recall**: Tuned based on threshold

---

##  Sigmoid Function

Logistic Regression uses the sigmoid function to output a probability:

\[
\sigma(z) = \frac{1}{1 + e^{-z}}
\]

Where `z = w·x + b`, and `σ(z)` gives the probability of the positive class.

---

---

##  Author

**Saurabh Kumar Jha** 
GitHub: [@saurabhkjha](https://github.com/saurabhkjha21)  
LinkedIn: [linkedin.com/in/saurabhkjha](https://linkedin.com/in/saurabhkjha21)  
Email: saurabhkjha21@email.com

---


