<div align="center">

# 🦁 Confusion Matrix & Classification Metrics — Interactive Masterclass
### **Lindenwood University — Interactive Data Science & Machine Learning Masterclass**

[![Live Interactive Lab](https://img.shields.io/badge/Launch_Interactive_Lab-Live_Demo-C5B358?style=for-the-badge&logo=googlechrome&logoColor=black)](https://sagarkalauni.github.io/confusion-matrix/)
[![Course](https://img.shields.io/badge/Course-DSCI_35600-000000?style=for-the-badge&logo=academia&logoColor=C5B358)](#)
[![Author](https://img.shields.io/badge/Faculty-Sagar_Kalauni,_M.S.-1E293B?style=for-the-badge&logo=github&logoColor=white)](https://github.com/SagarKalauni)

</div>

---

## 📖 Overview

An interactive diagnostic simulation of the **Binary Confusion Matrix** and derived evaluation metrics. Students explore the interplay between **True Positives (TP), False Positives (FP / Type I Error), False Negatives (FN / Type II Error), and True Negatives (TN)**, and learn why **Accuracy Paradox** occurs on imbalanced datasets (such as rare disease screening and fraud detection).

> 🔗 **Launch the Live Interactive Application:** [**https://sagarkalauni.github.io/confusion-matrix/**](https://sagarkalauni.github.io/confusion-matrix/)

---

### 📐 Mathematical Formulation

Given true labels $Y \in \{0, 1\}$ and predicted labels $\hat{Y} \in \{0, 1\}$ at decision threshold $\tau$:

$$\text{Accuracy} = \frac{TP + TN}{TP + FP + FN + TN}, \qquad \text{Precision (PPV)} = \frac{TP}{TP + FP}$$

$$\text{Recall (Sensitivity / TPR)} = \frac{TP}{TP + FN}, \qquad \text{Specificity (TNR)} = \frac{TN}{TN + FP}$$

**Harmonic Mean ($F_1$-Score):**
$$F_1 = 2 \cdot \frac{\text{Precision} \times \text{Recall}}{\text{Precision} + \text{Recall}} = \frac{2\,TP}{2\,TP + FP + FN}$$

---

## ✨ Key Interactive Features

- **Interactive Decision Threshold ($\tau$) Slider:** Slide the classification cutoff across overlapping class distributions to watch $TP, FP, FN, TN$ counts shift in real time.
- **Live Metric Gauges:** Instant calculation of Accuracy, Precision, Recall, Specificity, False Positive Rate (FPR), and $F_1$-Score.
- **Class Imbalance Simulator:** Demonstrate why 99% accuracy can mask a 0% recall model on rare-event datasets.
- **Domain Scenario Presets:** Compare oncology screening (minimizing False Negatives) vs. spam filtering (minimizing False Positives).

---

## 🎓 Pedagogical & Course Context

- **Institution:** Lindenwood University (*College of Science, Technology, and Health*)
- **Course Curriculum:** DSCI 35600 — Machine Learning & MTH 14100 — Basic Statistics
- **Instructor & Author:** **Sagar Kalauni, M.S.** (*Full-Time Faculty in Data Science*)
- **Tech Stack:** HTML5, Tailwind CSS, **D3.js** (Dynamic Data Visualization), **MathJax** (LaTeX Mathematical Rendering), Vanilla ES6+ JavaScript (Zero-Dependency Client-Side Execution).

---

## 🚀 Running Locally

Because this visualizer is engineered as a self-contained, zero-build client-side application, you can run it immediately in any modern browser:

```bash
# Clone the repository
git clone https://github.com/SagarKalauni/confusion-matrix.git

# Navigate into the project directory
cd confusion-matrix

# Open index.html directly in your browser or serve locally:
python -m http.server 8000
```

---

## 🔗 Explore the Complete Interactive Masterclass Suite

| Module | Topic | Live Link |
| :--- | :--- | :---: |
| **Linear Regression** | Ordinary Least Squares & Residual Minimization | [Launch](https://sagarkalauni.github.io/linear-regression/) |
| **Logistic Regression** | Sigmoid Probabilities & Binary Cross-Entropy | [Launch](https://sagarkalauni.github.io/logistic-regression/) |
| **Regularization ($L_1 / L_2$)** | Lasso vs. Ridge Constraint Geometry | [Launch](https://sagarkalauni.github.io/Regularization/) |
| **K-Nearest Neighbors** | Instance-Based Learning & Distance Metrics | [Launch](https://sagarkalauni.github.io/knn/) |
| **Support Vector Machine** | Maximum-Margin Hyperplanes & Soft Margin $C$ | [Launch](https://sagarkalauni.github.io/support-vector-machine/) |
| **RBF Kernel SVM** | Non-Linear Kernel Trick & $(\gamma, C)$ Tuning | [Launch](https://sagarkalauni.github.io/rbf-kernel-svm/) |
| **Decision Tree (CART)** | Recursive Splitting, Gini & Entropy | [Launch](https://sagarkalauni.github.io/decision-tree/) |
| **Random Forest** | Bagging & Ensemble Variance Reduction | [Launch](https://sagarkalauni.github.io/random-forest/) |
| **Voting Classifier** | Hard Majority vs. Soft Probability Voting | [Launch](https://sagarkalauni.github.io/voting-classifier/) |
| **K-Means Clustering** | Lloyd's Algorithm, Voronoi & Elbow WCSS | [Launch](https://sagarkalauni.github.io/k-mean-clustering/) |
| **Confusion Matrix** | Precision, Recall, Specificity & $F_1$-Score | [Launch](https://sagarkalauni.github.io/confusion-matrix/) |
| **Confidence vs. Prediction Intervals** | Mean Response vs. Individual Uncertainty | [Launch](https://sagarkalauni.github.io/confidence-and-prediction-interval/) |
| **Bootstrapping** | Non-Parametric Resampling with Replacement | [Launch](https://sagarkalauni.github.io/bootstrap/) |
| **Q-Q Plot** | Gaussian Normality & Tail Diagnostics | [Launch](https://sagarkalauni.github.io/qq-plot/) |
| **Train-Test Split & CV** | Holdout Partitioning & $K$-Fold Cross-Validation | [Launch](https://sagarkalauni.github.io/split/) |
| **One-Hot Encoding** | Categorical Expansion & Dummy Variable Trap | [Launch](https://sagarkalauni.github.io/one-hot-encoding/) |

---

<div align="center">
  <sub>Developed with ❤️ for Data Science students by <a href="https://github.com/SagarKalauni">Sagar Kalauni</a> · <a href="https://sagarkalauni.github.io">Portfolio</a></sub>
</div>
