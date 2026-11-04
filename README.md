# 📘 The Complete Machine Learning Handbook

**A structured, practical reference for understanding classical Machine Learning — from the fundamentals to end-to-end projects.**

**54 chapters · 52 exercises with solutions · 4 case studies · Python examples · No deep learning**

> **The idea behind this project:** While learning Machine Learning, I wanted one place to understand *what models do, why they work, when to choose them, and how to use them in complete ML pipelines*. I came up with the idea for this handbook and developed the learning resources with AI assistance. My goal is to make complex concepts easier to revisit, connect, and practice.

## 📥 Download the resources

| Resource | What's inside | Download |
|---|---|---|
| **Complete Machine Learning Handbook** | 65-page reference book covering algorithms, mathematics, practical code, evaluation, and workflows | **[⬇️ Download Handbook (PDF)](https://raw.githubusercontent.com/mohammed-mehdi-saibat/ML-Handbook/main/ml_book/Machine_Learning_Handbook.pdf)** |
| **Machine Learning Quick Reference** | 5-page companion with key formulas, metrics, comparisons, and Python snippets | **[⬇️ Download Quick Reference (PDF)](https://raw.githubusercontent.com/mohammed-mehdi-saibat/ML-Handbook/main/ml_book/Machine_Learning_Quick_Reference.pdf)** |

**Note:** If GitHub shows **“Unable to render code block”** when previewing a PDF, use the **Download** links above. The PDFs can be opened locally in any standard PDF reader.

## 🧭 What's covered?

| Part | Topics |
|---|---|
| **I. Foundations** | Learning paradigms, essential mathematics, datasets, the ML lifecycle, bias–variance, overfitting and data leakage |
| **II. Data Understanding & Preparation** | NumPy, Pandas, EDA, missing data, outliers, feature engineering, encoding, scaling, class imbalance and train/test splitting |
| **III. Regression** | Linear and polynomial regression, regularization, KNN, trees, forests, SVR, boosting and regression metrics |
| **IV. Classification** | Logistic regression, Naive Bayes, KNN, decision trees, random forests, SVM, boosting and classification metrics |
| **V. Unsupervised Learning** | K-Means, DBSCAN, hierarchical clustering, Gaussian mixtures, PCA, t-SNE, UMAP and anomaly detection |
| **VI. Professional ML Workflows** | Scikit-learn pipelines, cross-validation, tuning, explainability, model persistence, MLflow, deployment and monitoring |
| **VII. Review & Practice** | Model-selection comparisons, technical questions, code-review challenges, exercises and worked solutions |

### 📊 The practical ML workflow

```text
Define the problem
       ↓
Collect and understand data
       ↓
Explore data (EDA) and design a validation strategy
       ↓
Split the data appropriately
       ↓
Fit preprocessing on training data only
       ↓
Build a reproducible pipeline
       ↓
Train → Cross-validate → Tune
       ↓
Evaluate → Interpret → Final test
       ↓
Save → Deploy → Monitor
```

*Preprocessing steps that learn from data should be fitted only on training folds. This prevents data leakage and gives more trustworthy evaluation results.*

## 🧪 Practice included

The handbook includes **52 exercises with worked solutions** and **four applied case studies**:

- **Price Prediction:** regression and error analysis.
- **Customer Churn:** classification, imbalance and threshold selection.
- **Customer Segmentation:** clustering and dimensionality reduction.
- **Anomaly Monitoring:** detecting unusual patterns.

## ⚡ How to use the two PDFs

1. **Learn a topic** in the full handbook, starting with the fundamentals and progressing toward model building.
2. **Reproduce the examples** in Python and explain what each step accomplishes.
3. **Attempt the exercises** before reading the solutions.
4. **Use the Quick Reference** whenever you need a formula, metric, model comparison or code reminder.

## 📁 Repository structure

```text
ML-Handbook/
├── README.md
└── ml_book/
    ├── Machine_Learning_Handbook.pdf
    └── Machine_Learning_Quick_Reference.pdf
```

## 🛠️ Tools and libraries discussed

`Python` · `NumPy` · `Pandas` · `Matplotlib` · `Seaborn` · `scikit-learn` · `XGBoost` · `LightGBM` · `CatBoost` · `Joblib` · `MLflow` · `FastAPI` · `Streamlit`

## 💬 Feedback and contributions

Corrections, suggestions, and improvements are welcome. If you notice a mistake, an unclear explanation, or an outdated API, please [open an issue](https://github.com/mohammed-mehdi-saibat/ML-Handbook/issues).

## 📝 Notes and credits

- **Scope:** This is a reference to *classical* Machine Learning. Deep learning is intentionally excluded; reinforcement learning is introduced conceptually.
- **Creation:** The concept and learning goals came from me. AI tools assisted with drafting, organizing, and developing the material. Readers are encouraged to verify examples and consult official documentation.
- **Educational use:** Examples are for learning and should be validated before real-world deployment.
- **License:** No open-source license is declared unless a `LICENSE` file is added to this repository.

---

**Understand the fundamentals. Build the pipeline. Evaluate the results. Keep learning.**
