# Credit-Fraud-Project
A small project using a range of machine learning models to classify fraudulent transactions from a Kaggle dataset. I used four machine learning models from the scikit-learn python library and evaluted there performence based on there precision and recall. These models were Logestic Regression,Random Forrest, Support vector machines and Multi-layer perceptron.

Logistic Regression: With the highest precision but the second lowest recall this model is best for makng sure the possible fraudulant data picked, is a true postive result. This maybe be due to this being the effect "over fitting" model of the bunch. It is able to identify common anomolies very well but not new, unseen ones, as shown by the low recall. This may not work well for predicting future events as Credit fraud is constantly changing.

Random Forest: Performed the worst in both aspects making it the worst performing model. Like Logistic regression, its efficient in identifiying the fraudulent transactions of the training set but due to random tree's being based on binary questions, it has trouble identifying new cases.

SVM: Best for recall but worst for precision. This may be due to it not taking into account all the data points, only the support vectors, so larger outliers may not be taken into account as with logistic regression leading to decreased precision. This also explains the recall as the model is able to take into account a more general range of data points and anomalies.

MLP: Able to learn trends in the data leadning to results the exact same as SVM. This does however depend on the fit of the model as overfitting would increase the precision but decrease the recall but this can be adjusted when fitting the model.




