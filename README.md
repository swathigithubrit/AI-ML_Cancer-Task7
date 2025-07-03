# AI-ML_Cancer-Task7
This project demonstrates how to use Support Vector Machines (SVM) for binary classification on the Breast Cancer dataset. The notebook walks through data loading, preprocessing, training with linear and RBF kernels, hyperparameter tuning, and evaluation

Breast Cancer Classification using Support Vector Machines (SVM)

🎯 Objective

* Use SVMs for linear and non-linear classification tasks
* Learn margin maximization, kernel trick, hyperparameter tuning
* Practice model evaluation and visualization

Tools & Libraries

* Python
* scikit-learn
* pandas
* numpy
* matplotlib
* seaborn

Dataset

* Breast Cancer dataset (CSV file)
* Typical target column: malignant/benign (converted to 0/1)
* Features: various medical measurements

✅ In the notebook, we:

* Load the CSV
* Explore and clean data
* Encode categorical labels
* Scale features for SVM


🗂️ Project Steps

1️⃣ Import and explore the dataset
2️⃣ Handle missing values
3️⃣ Encode target labels
4️⃣ Train/test split
5️⃣ Feature scaling
6️⃣ Train SVM with **linear kernel**
7️⃣ Train SVM with **RBF (non-linear) kernel**
8️⃣ Evaluate models using:

* Accuracy
* Confusion matrix
* Classification report
  9️⃣ Hyperparameter tuning with GridSearchCV
  10️⃣ Cross-validation to check generalization

Key Concepts Demonstrated

✅ Margin maximization
✅ Kernel trick for non-linear separation
✅ Hyperparameter tuning (C, gamma)
✅ Cross-validation for performance estimation
✅ Data scaling for SVM sensitivity

📊Results

* Linear Kernel: good accuracy with a straight-line decision boundary
* RBF Kernel: improved flexibility, higher accuracy after tuning
* GridSearchCV: finds best C and gamma
* Cross-validation: verifies generalization and avoids overfitting
