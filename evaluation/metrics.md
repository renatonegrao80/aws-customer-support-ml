# Model Evaluation Metrics

This project uses a basic classification model to categorize customer support messages.
Below are the main evaluation metrics used to validate performance.

## 📈 Accuracy
How often the model is correct.

\[
Accuracy = \frac{TP + TN}{TP + TN + FP + FN}
\]

Useful when classes are balanced.

---

## 🎯 Precision
How many predicted positives are actually correct.

\[
Precision = \frac{TP}{TP + FP}
\]

Useful when the cost of false positives is high.

---

## 🔁 Recall
How many actual positives were detected.

\[
Recall = \frac{TP}{TP + FN}
\]

Useful when missing a positive case is risky.

---

## ⚖️ F1 Score
Balance between precision and recall.

\[
F1 = 2 \times \frac{Precision \times Recall}{Precision + Recall}
\]

---

## 🟣 AUC-ROC
Measures how well model separates classes.

- 0.5 = random
- 1.0 = perfect separation

---

## 📌 Summary Table

| Metric     | Purpose                        | When to use                     |
|------------|--------------------------------|---------------------------------|
| Accuracy   | Overall correctness            | Balanced datasets               |
| Precision  | Correct positive predictions   | False positives are expensive   |
| Recall     | Detect true positives          | False negatives are expensive   |
| F1 Score   | Precision-Recall balance       | Mixed importance                |
| AUC-ROC    | Class separability             | Imbalanced classes              |

---

This document explains common evaluation metrics used in Machine Learning classification problems.
