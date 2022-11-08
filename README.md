# supervised-machine-learning-challenge

## Instructions

### Retrieve the data

The data is located in the Resources folder.

* `lending_data.csv`

Import the data using Pandas.

## Consider the models

You will be creating and comparing two models on this data: a logistic regression, and a random forests classifier. Before you create, fit, and score the models, make a prediction as to which model you think will perform better. You do not need to be correct! Write down (in markdown cells in your Jupyter Notebook or in a separate document) your prediction, and provide justification for your educated guess.

## Fit a LogisticRegression model and RandomForestClassifier model

Create a LogisticRegression model, fit it to the data, and print the model's score. Do the same for a RandomForestClassifier. You may choose any starting hyperparameters you like. Which model performed better? How does that compare to your prediction? Write down your results and thoughts.

## Conclusion: 
Logistic Regression model would be my preference. Althought the Random Forest Classifier gives better test scoring, the `make_blobs` function displayed a linear set of clusters. For this reason, I would use the Logistic Regression Model over the Random Forest Classifier. All other inidicators were very close (training and testing scores). 
