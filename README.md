# Heart-Attack-Prediction-Model

**Machine learning model to predict heart attack risk** — a reproducible project that trains a classifier on the included `heart.csv` dataset and achieves ~**91%** accuracy (as reported in the notebook).

---

## 🔍 Project overview

This repo contains a Jupyter notebook (`HeartAttack_prediction_Project_Epics.ipynb`) and the dataset (`heart.csv`). The notebook demonstrates an end-to-end workflow:

- Data loading & exploration
- Cleaning and preprocessing
- Feature selection / engineering
- Training several classifiers (e.g., Logistic Regression, Random Forest, etc.)
- Model evaluation (accuracy, confusion matrix, ROC/AUC)
- Saving/training best model and (optionally) using it for single predictions

---

## 📁 Repository structure

├── HeartAttack_prediction_Project_Epics.ipynb # Jupyter notebook with full analysis & model training
├── heart.csv # Dataset (features + target)
└── README.md # (this file)


---

## 🧾 Dataset

`heart.csv` contains patient features and a target column indicating presence/absence of heart disease. (If you used the UCI Cleveland heart disease dataset or a different source, keep a note of that here and include column descriptions.)

**Recommended:** Add a `DATASET.md` later describing each column (age, sex, chest pain type, resting BP, cholesterol, etc.) for clarity.

---

## 🔧 Requirements & Installation

Recommended: create a virtual environment.

```bash
# clone the repo
git clone https://github.com/arpitaapatel/Heart-Attack-Prediction-Model.git
cd Heart-Attack-Prediction-Model

# create & activate venv (Linux/Mac)
python3 -m venv venv
source venv/bin/activate

# or on Windows (PowerShell)
python -m venv venv
.\venv\Scripts\Activate.ps1

# install required packages
pip install -r requirements.txt
