# Diabetes Prediction using Decision Tree Regressor

This project uses the diabetes dataset from **scikit-learn** to build and evaluate a **Decision Tree Regressor** model for predicting disease progression. The notebook `diabetes_prediction_using_decision_tree.ipynb` demonstrates an end-to-end workflow: from data loading and train-test splitting to model training, hyperparameter tuning with **GridSearchCV**, evaluation, and visualization.

---

##  Project Structure

decision_tree_projects/
├── diabetes_prediction_using_decision_tree.ipynb
├── decision_tree_classifier.ipynb
└── README.md


- **`diabetes_prediction_using_decision_tree.ipynb`**  
  - Loads the diabetes dataset.
  - Splits into training & testing sets.
  - Trains a **Decision Tree Regressor**.
  - Uses **GridSearchCV** to tune parameters like `max_depth`, `min_samples_split`, etc.
  - Evaluates model performance using metrics such as MSE and R².
  - Visualizes the tree structure and feature importance.

- **`decision_tree_classifier.ipynb`**  
  - Contains an example of decision tree **classification** (different dataset or target).

---

##  Dependencies

- Python 3.7+
- `numpy`
- `pandas`
- `scikit-learn`
- `matplotlib`

Install any missing dependencies with:

```bash
pip install numpy pandas scikit-learn matplotlib
