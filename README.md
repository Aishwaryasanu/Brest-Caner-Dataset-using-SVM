# Brest-Caner-Dataset-using-SVM
# Support Vector Machines (SVM) for Classification

Objective
This project demonstrates the application of **Support Vector Machines (SVM)** for binary classification tasks. Both **linear** and **non-linear kernels** are explored, along with hyperparameter tuning, cross-validation, and decision boundary visualization.

Project Overview
1. Support Vector Machines Basics
   * Find the optimal hyperplane that maximizes the margin between classes.
   * **C (Regularization):** Controls the balance between wide margins and correct classification.
   * **Kernel Trick:** Enables SVM to handle non-linear data by mapping inputs into higher dimensions.
   * **Gamma (RBF/Polynomial kernels):** Defines the influence of individual points on the decision boundary.

2. Data Preparation
   * Input features are standardized for stability.
   * Target labels are encoded into binary format.

3. Model Training
   * Train SVM with different kernels:
     * Linear Kernel
     * Radial Basis Function (RBF) Kernel
     * Polynomial Kernel

4. Model Evaluation
   * Metrics: Accuracy, Precision, Recall, F1-score.
   * Confusion Matrix for misclassification analysis.
   * Cross-validation for robust performance estimation.

5. Hyperparameter Tuning
   * Use GridSearchCV to optimize `C`, `gamma`, and kernel parameters.

6. Visualization
   * Compare model metrics across kernels.
   * Plot confusion matrices.
   * Visualize decision boundaries in reduced 2D feature space using PCA.

Key Insights
* Linear kernels provide a simple, interpretable baseline.
* RBF kernels adapt well to complex, non-linear decision boundaries
* Polynomial kernels can capture curved relationships but may risk overfitting.
* Hyperparameter tuning significantly improves generalization.
* Visualization of decision boundaries helps understand model behavior in feature space.

Conclusion
Support Vector Machines are robust classifiers capable of handling both linearly separable and non-linear data. By selecting appropriate kernels and tuning parameters, SVMs can achieve strong generalization performance. This workflow provides a complete framework for applying SVMs to any binary classification problem.
