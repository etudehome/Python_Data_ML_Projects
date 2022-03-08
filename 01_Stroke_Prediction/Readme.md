## Stroke Prediction ML

In this project, I built and trained multiple machine learning algorithm to predict whether a patient is likely to get stroke. Data was obtained from kaggle: https://www.kaggle.com/fedesoriano/stroke-prediction-dataset, containing 5110 observations with 12 attributes
like gender, age, various diseases, and smoking status. I performed exploratory data analysis and data visualization on the data set. Overall relatively low correlations were found in relation to the target variable stroke.
With only approxiametly 6 % of patients with stroke , there is a strong case of imbalanced data. Therefore I used 1. different BoostGradients to adjust weights of incorrectly classified instances, 2. used SMOTE method to oversample the minority class. 

I prepared the data and splitted into training and test dataset before training. Random Forest Classifier, using sci-kit learn was evaluated as the best model. But further improvments need to be done. 
