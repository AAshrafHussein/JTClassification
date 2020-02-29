# JTClassification
This project is a Machine Learning Text Classification task. In which, I am interesed in categorizes job titles data into 4 industries;
based on the text features.

In this notebook, I perform text cleaning and data exploration. Besides, I extract the needed features using different vectorizers
such as TF-IDF. Then, perform benchmarking between different ML algorithms: Support Vector Machine (SVM), Multinomial Naive Bayes (MNP)
and Logistic Regression. 

Results came as follows:

SVM Accuracy Score equals 0.911970190964136
SVM F1 Score equals 0.9295973628443608

LR Accuracy Score equals 0.8812296227293899
LR F1 Score equals 0.9158607350096711

MNB Accuracy Score equals 0.8872845831392641
MNB F1 Score equals 0.911785799665312

Finally, I deploy the model as a RESTful API using Flask.
