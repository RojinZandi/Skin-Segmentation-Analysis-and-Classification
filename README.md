# Skin-Segmentation-Analysis-and-Classification

The goal of this course project is to apply some of classification methods that we learned in EE257-Machine Learning course. For full information please read the attached project report.

**Data:** The Skin Segmentation dataset can be found here : https://archive.ics.uci.edu/ml/datasets/skin+segmentation

Before training classification models, we did data visualization and cleaning (Part **B** and **C**)
and related works are cited in part **D**

**Feature Extraction:** We applied Recursive Feature Elimination, Lasso and Ridge Regression,... (Part **E**)


**Model Development:** The models we used are: Logistic Regression, LDA, QDA, KNN, Decision Tree, Random Forest (Part **F**)
The classifcation metrics (Accuracy, Precision, Recall, F1-Score, Confusion Matrix) are provided. 

**Fine-Tuning:** To tune the hyperparameters of our models, K-fold cross validation with K=5 has been done on
the models. The tuned parameters for each model are:

Logistic Regression: Number of iterations

LDA/QDA: Tol

KNN: Number of Neighbors (K)

Decision Tree and Random Forest: Maximum depth of the tree


**Conclusion**

1. The skin segmentation dataset is unbiased

2. The features (Blue, Red, Green) are highly correlated and it is suggested to not eliminate
any of the features.

3. Non-linear models perform better than linear models.

4. QDA has high performance so the data must be normal. (Gaussian Distribution)

5. Before fine-tuning, KNN with K=5 has the best score among other models.

6. Random Forest has the most improvement by fine-tuning. (max depth)

7. After fine-tuning, KNN with K=21 has the best score among other models.
