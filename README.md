# Liver-Disease-Prediction

Liver disease is one of the chronic diseases and the number of people suffering from it are increasing day by day due to a large consumption of alcohol, inhalation of harmful gases, intake of contaminated food and drugs. The early diagnosis can help provide treatment before it gets severe and even fatal. Here, machine learning algorithms can play 
an important role by helping in identifying the patients who may have a liver disease in a very efficient manner and faster rate.

This is a binary classification problem. In order to build the machine learning models, the data was pre-processed which includes treating the missing values, scaling of the data and feature engineering. The data was divided into train and test sets of ratio 70:30 and trained using various classification algorithms like Logistic Regression, Decision Tree, Naive Bayes, Ensemble Methods. Further, to finalize the model a 10-fold cross validation was performed taking into consideration the evaluation metrics as Recall because in such cases correctly predicting the person actually having the disease is more important.

The important features for this model turned out to be: Age, Alkaline Phosphate, Alamine Aminotransferase, Aspartate Aminitranferase and Total Bilirubin.

The final model selected was the Random Forest model with the above important features that resulted in recall score of 86%.
