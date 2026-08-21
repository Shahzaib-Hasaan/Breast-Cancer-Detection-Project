# Breast Cancer Detection

Classical machine learning project: predicting breast cancer diagnosis from tumor measurements, with a full EDA-to-model comparison workflow in a single notebook.

Part of my BS Artificial Intelligence degree work.

## What's inside

`proj_cancer_detection.ipynb` walks through the complete workflow:

1. **Exploratory data analysis** on the tumor-measurement dataset (`cancer.csv`)
2. **Preprocessing** — cleaning, feature scaling, train/test split
3. **Model comparison** — several scikit-learn classifiers trained and evaluated against each other
4. **Evaluation** — accuracy scores and classification reports per model

## Results

| Model | Test accuracy |
|---|---|
| **Linear SVC** | **~0.96** |
| Ridge Classifier | ~0.65 |
| Decision Tree | ~0.65 |
| Logistic Regression (unscaled) | ~0.35 |

The gap is the lesson: feature scaling and model choice mattered far more than tuning. Linear SVC on scaled features was the clear winner.

## Run it

```bash
pip install scikit-learn pandas numpy matplotlib seaborn jupyter
jupyter notebook proj_cancer_detection.ipynb
```

---

More of my work: [shahzaibbuilds.me](https://shahzaibbuilds.me) · [LinkedIn](https://www.linkedin.com/in/shahzaib-hassan-ai-developer/)
