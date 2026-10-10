# Data Science & Machine Learning Portfolio

A curated collection of machine learning algorithms built from scratch, statistical experiments, and competitive data science notebooks across Jupyter, Colab, and Kaggle.

---

## 📚 Notebook Directory

| Category | Experiment / Topic | Tech Stack | Quick Launch |
| :--- | :--- | :--- | :--- |
| **Math & Scratch** | Linear Regression via Gradient Descent | NumPy, Matplotlib | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/jatinsharma25/Data-science-learnings/blob/main/01-scratch-implementations/linear_regression.ipynb) |
| **Classical ML** | Tree Ensembles (Random Forest vs XGBoost) | Scikit-Learn, XGBoost | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/jatinsharma25/Data-science-learnings/blob/main/02-classical-ml/tree_ensembles.ipynb) |
| **Competitions** | Advanced Feature Engineering (Tabular) | LightGBM, Pandas | [![Kaggle](https://kaggle.com/static/images/open-in-kaggle.svg)](https://www.kaggle.com/) |

---

## 🛠 Local Setup

Clone the repository and install dependencies locally:

```bash
git clone [https://github.com/jatinsharma25/Data-science-learnings.git](https://github.com/jatinsharma25/Data-science-learnings.git)
cd Data-science-learnings
python -m venv venv

# Activate virtual environment
source venv/bin/activate       # macOS / Linux
# venv\Scripts\activate       # Windows PowerShell

pip install -r requirements.txt
jupyter lab
