Support Vector Machines (SVM) for Binary Classification
📌 Objective

This project demonstrates how to use Support Vector Machines (SVMs) for both **linear** and **non-linear classification** tasks using the **Breast Cancer dataset** available from Scikit-learn. The project covers model training, visualization, hyperparameter tuning, and cross-validation.

🛠️ Tools & Libraries
- Python
- NumPy
- Matplotlib
- Scikit-learn

🧪 Dataset

- Name: Breast Cancer Wisconsin Diagnostic Dataset
- Source:`sklearn.datasets.load_breast_cancer()`
- Type: Binary classification (`0 = malignant`, `1 = benign`)

🔍 What This Project Covers

1. Loading and preprocessing the dataset.
2. Reducing the data to 2D using PCA (for visualization).
3. Training SVM classifiers with:
   - Linear kernel
   - RBF (non-linear) kernel
4. Visualizing decision boundaries in 2D.
5. Tuning hyperparameters (`C`, `gamma`) using GridSearchCV.
6. Evaluating performance using:
   - Cross-validation scores
   - Confusion matrix
   - Classification report

📊 Visual Output

- SVM decision boundary plots
- Best parameters from hyperparameter tuning
- Cross-validation accuracy
- Final evaluation metrics

🧾 How to Run

1. Open the Colab notebook or Python script.
2. Ensure the required libraries are installed:
