# Supervised-Machine-Learning

# Predictiing Credit Risk

In this project I will be building a machine learning model that attempts to predict whether a loan will be approved or not.

# Background
Lending services companies allow individual investors to partially fund personal loans as well as buy and sell notes backing the loans on a secondary market. 
This data will be used to create machine learning models to classify the risk level of given loans. Specifically, comparing the Logistic Regression model and Random Forest Classifier.

# Instructions

• Retrieve the data
The data is located in the Resources folder 
(lending_data.csv).

• Import the data using Pandas.

# Consider the models
Created and compared two models on this data: a Logistic Regression, and a Random Forests Classifier. Before creating, I fit, and scored the models, making a prediction as to which model I thought will perform better.

# Fit a LogisticRegression model and RandomForestClassifier model
Creating a LogisticRegression model, fitting it to the data, and printing the model's score. Do the same for a RandomForestClassifier. 

The two questions to be asked are:

•Which model performed better? 

•How does that compare to your prediction? 

# Analysis 

# Prediction

The Logistic Regression model is more efficient and a much more simple method in regard to both linear and binary classification problems. As this is a classification model, the model obtains a high level of accuracy along with linearly separable classes.

The Random Forest Classifier(RFC) model is able to performe both regression and classificaation tasks. The RFC model is able to work with large datasets as well as with non-linear data. The RFC also provides a more accurate prediction when compared to other classification algorithms.

Therefore, I feel that the RFC model will overall perform better than the Linear Regression model as the data provided may not be able to be separated linearly.

# Conclusion

Overall the RFC training model performs better than the LR training model supporting my initial prediction.

The RFC training data score of 0.9973 is higher than the LR score of 0.9918. The testing data scores show very little difference between the two. The RFC model is 0.9923 to 4 d.p. and the LR model is 0.9926 to 4 d.p. This shows that there is no significant difference betweeen both the LR and RFC scores. This could be due to the data being linear and so there will be similar overall outcomes.

The final outcome shows the LR model is slightly better than the RFC model which does not support my prediction.
