# Wine_Quality_Prediction

The dataset describes the amount of various chemicals present in wine and their effect on it's quality. 

  Input variables (based on physicochemical tests):\
1 - fixed acidity\
2 - volatile acidity\
3 - citric acid\
4 - residual sugar\
5 - chlorides\
6 - free sulfur dioxide\
7 - total sulfur dioxide\
8 - density\
9 - pH\
10 - sulphates\
11 - alcohol\
Output variable:\
12 - quality (score between 0 and 6)

The output variable is coverted to categorical, for quality more than & equal to 6->1,for quality less than 7->0 & and is solved as a classification problem.

Machine Learning Models used:

1. Logistic Regression
2. Decision Tree Classifier with gini & entropy criteria
3. Random Forest
4. Ada Boost

Used cross validation technique GridSearchCV to improve the performance.
