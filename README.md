# Ensembles-LogReg-ClassTree-LDA-QDA-KNN-SVM-NB
Ensemble with seven models: Logistic Regression, Classification Trees, LDA, QDA, KNN, SVM, and Naive Bayes using R and python.

Step for doing the process:
1. Use the Train data set to build Logistic Regression, Classification Trees, LDA, QDA, K-Nearest Neighbors, SVMs, and Naïve Bayes to predict the Readmitted Variable.
2. Build ensemble across all 7 models that has been built thus far for predicting the "Readmitted" variable.
The ensemble model simply takes the predictions of "Readmitted" for each observation from the 7 models that has already been
built. It then applies the "Majority rule". To illustrate, if the predictions from Logistic Regression, Classification Trees, LDA, QDA, KNN, SVM, and NB are Yes, Yes, Yes, No, Yes, No, No respectively for an observation, resulting in 4 predictions of Yes and 3 prediction of No, then the Ensemble model would yield a prediction of Yes, since majority of the models predict "Yes" (4 > 3). 
3. Predict all observations in Training and Test using the Ensemble model.
