# Heart-Attack-Prediction-Model

**Machine learning model to predict heart attack risk** — a reproducible project that trains a classifier on the included `heart.csv` dataset and achieves ~**91%** accuracy 
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


📈 Model & Results

The notebook reports ~91% accuracy for the selected model on the chosen test split (see the notebook for detailed confusion matrix, ROC/AUC, and class-wise metrics).

For production use or research: perform more robust validation (k-fold CV, repeated splits), hyperparameter tuning, class imbalance handling, and consider model calibration.
