# 🍄 Mushroom Classification (Logistic Regression, Decision Tree & Gradient Boosting)
This project classifies mushrooms as edible (0) or poisonous (1) using three machine learning models: Logistic Regression, Decision Tree, and Gradient Boosting. 
We explore both default and tuned versions to improve model performance and interpretability.

## 📊 Dataset
This project uses the Mushroom Dataset from Kaggle.

- 0 → Edible
- 1 → Poisonous


## 🚀 Project Workflow
- Data Exploration & Visualization
- Inspected class distribution
- Visualized boxplots for each feature by class
- Identified trends in gill_color, stem_color, etc.
- Train-Test Split
- Used train_test_split(test_size=0.25) to split data
- Modeling & Evaluation

🔹 Logistic Regression (Baseline)

- Model: LogisticRegression()
- Accuracy: 0.62
- Struggled to capture complex non-linear patterns

🔹 Decision Tree Classifier

- Model: DecisionTreeClassifier()
- Accuracy: 0.98
- High performance due to decision boundaries fitting categorical structure

🔹 Gradient Boosting Classifier (Default)

- Model: GradientBoostingClassifier()
- Accuracy: 0.88
- More robust than Logistic Regression

🔹 Gradient Boosting (Tuned)

- Accuracy: 0.90
- Tuned to improve minority class prediction
- Visualized feature importances

## 🧾 Results Summary

| Model                            | Accuracy | Precision (1) | Recall (1) | F1-Score (1) |
|----------------------------------|----------|---------------|------------|--------------|
| Logistic Regression              | 0.62     | 0.65          | 0.67       | 0.66         |
| Decision Tree                    | 0.98     | 0.98          | 0.98       | 0.98         |
| Gradient Boosting                | 0.88     | 0.90          | 0.89       | 0.89         |
| Gradient Boosting (Custom Tuned) | 0.90     | 0.93          | 0.90       | 0.91         |

## ⚙️ Installation

1. Clone the repo:

```bash
git clone https://github.com/yourusername/mushroom_classification_gradient_boosting.git
cd mushroom_classification_gradient_boosting
```
2. **Install dependencies:**:   
```commandline
pip install -r requirements.txt
```

📂 Files in This Repo

- mushroom_classification.ipynb: Jupyter notebook with full analysis, training, evaluation, and visualizations
- requirements.txt: All required Python libraries (pandas, imblearn, scikit-learn, matplotlib, seaborn)

👨‍💻 Author

Yoseph Negash

📧 yosephn22@gmail.com

📅 2025




