# Heart-Failure-Prediction-System
Heart Failure Prediction System using Naïve Bayes Algorithm, Using Pandas, NumPy, and Sklearn libraries.
We start by importing the dataset and splitting it into train and test data modules, count_values() calculates the number of zeros and ones in our label and is later used for conditional probabilities. conditional_probabilities_binary() calculates the probability from the y_train data  for the binary data types. Later we use conditional_probabilities_numerical() to calculate the probability of numerical features. Lastly we use the classifer() to train our model and to check its accuracy.
Results:
We have designed our model in such a way that it uses Naïve Bayes classifier and predicts weather the person with given input values has a risk of heart failure. We have plotted the confusion matrix of our model.  The results of confussion matrix shows that an accuracy of 69% is acheived.
  
