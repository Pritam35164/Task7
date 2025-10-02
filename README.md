# Support Vector Machines (SVM)

This project is about using **Support Vector Machines (SVMs)** for classification on the Breast Cancer dataset. The goal was to understand both **linear** and **non-linear (RBF)** SVMs, tune hyperparameters, and visualize decision boundaries.

---

## What I Did

1. **Loaded the dataset** (Breast Cancer dataset in CSV format).
2. **Prepared features & labels** → Converted diagnosis (`M` = Malignant, `B` = Benign) into numeric form.
3. **Trained SVM with Linear kernel** → Found a straight-line decision boundary.
4. **Trained SVM with RBF kernel** → Allowed complex, curved boundaries for better classification.
5. **Hyperparameter tuning** → Used GridSearchCV to optimize `C` and `gamma`.
6. **Cross-validation** → Ensured the model generalizes well.
7. **Visualization** → Used PCA to reduce features to 2D and plotted decision boundaries.

---

## What I Learned

* **Support vectors** are the key points that decide the boundary.
* **C parameter** controls trade-off between margin width and classification accuracy.
* **Kernel trick** lets SVM handle non-linear data without explicitly going into higher dimensions.
* **Linear vs RBF kernel**: Linear works for simple separation, RBF handles complex cases.
* **Hyperparameter tuning** helps avoid overfitting.
* SVMs can also be extended to **regression (SVR)**.

---

## Results

* Linear SVM achieved strong accuracy, but RBF with tuning performed even better.
* Cross-validation confirmed that the chosen parameters generalize well.
* Visualizations showed how RBF kernel adapts to complex data boundaries.

---

## Tools Used

* Python (Scikit-learn, NumPy, Matplotlib, Pandas)
* Breast Cancer Dataset (CSV file)

---

## 🌟 Takeaway

SVMs are powerful because they don’t just look for *any* boundary, they look for the **best possible boundary** — the one that maximizes margin and generalizes well to new data.
# Task7
