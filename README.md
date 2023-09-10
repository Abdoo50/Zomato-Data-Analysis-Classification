# Zomato-Data-Analysis-Classification
***We want to predict if the restaurant will close or no depends on the features that on the data set***
We will add a new feature using Feature Engineering and call it Target

## Context:
Restaurants from all over the world can be found here in Bengaluru. From the United States to

Japan, Russia to Antarctica, you get all types of cuisines here. Delivery, Dine-out, Pubs, Bars, Drinks, 
Buffet, Desserts, you name it and Bengaluru has it.

Bengaluru is the best place for foodies. The number of restaurants is increasing day by day. 

Currently it stands at approximately 12,000 restaurants. With such a high number of restaurants. 
This industry hasn't been saturated yet. And new restaurants are opening every day.

However, it has become difficult for them to compete with already established restaurants.
The key issues that continue to pose a challenge to them include high real estate costs, rising food costs, 
shortage of quality manpower, fragmented supply chain and over-licensing. 
This Zomato data aims at analyzing the demography of the location. 
Most importantly it will help new restaurants in deciding their theme, menus, cuisine, cost etc. 
for a particular location. 
It also aims at finding similarity between neighborhoods of Bengaluru based on food. The dataset also contains reviews 
for each of the restaurants which will help in finding overall rating for the place.

## Data Modeling
Make machine learning Model using many techniques such as **Feature selection**
also we will use many classification algorithms such as:
- Logistic Regression
- SVM
- XGBoost classifier
- Decision Tree Classification
- Random Forest Classification
- Naive Bayes Classifier

in **Model Evaluation** Section We will use:
- accuarcy score
- Classification Report
- Precision, recall, F1-score
- Confusion Matrix
Finaly we will finish with **Model Deployment**

### Cross Validation & Classification Report & Precision, Recall, F1-score

#### Use cross-validation to validate our model on the train data

Cross-validation is a technique that splits the train data into k folds and uses k-1 folds for training and 1 fold for validation

It repeats this process k times and averages the validation scores to get a more reliable estimate of the model's performance

You can use cross_val_score function from scikit-learn to perform cross-validation and get the validation scores for each fold

You can specify the number of folds using cv parameter and the scoring metric using scoring parameter

In this case, we use 5 folds and accuracy as the scoring metric
