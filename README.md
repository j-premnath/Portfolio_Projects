# Stroke Prediction

I have used the Stroke Prediction Dataset from Kaggle. Built a machine learning model that able to predict the chances of stroke based on certain features like gender, age, glucose level, BMI, smoking status, other comorbidities, etc. Replaced the NAN values by calculating the median score. Removed the Outliers from the dataset using Z score. Converted the Object type features in the dataset to int type using Label Encoder. The data is highly imbalanced for the target variable, which was addresssed using SMOTE technique.

Classification report for the SVM model:

              precision    recall  f1-score   support

           0       0.81      0.73      0.77       953
           1       0.75      0.83      0.79       953

    accuracy                           0.78      1906
   macro avg       0.78      0.78      0.78      1906
weighted avg       0.78      0.78      0.78      1906

Classification report for the Random Forest model:

              precision    recall  f1-score   support

           0       0.93      0.92      0.92       953
           1       0.92      0.93      0.92       953

    accuracy                           0.92      1906
   macro avg       0.92      0.92      0.92      1906
weighted avg       0.92      0.92      0.92      1906
