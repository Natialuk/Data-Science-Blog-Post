# Data Science Blog Post
## Why and why now? 
I'm working in Learning and Talent Development department in a large software company. During the last few months I'm participating in Data Science and Machine Learning nanodegree program via Udacity learning platform Which ignited my curiosity and pushed me to create this project.
Being part of an HR department, employee' attrition is a subject that is always under the spotlight. Especially, nowadays that recruiting talents becomes a real challenge. I thought to myself, wouldn't it be great if we could anticipate the employee attrition in advance, or establish working processes that can reduce or even prevent attrition? Using Machine Learning and data that I extracted from Kaggle, I tried to meet this challenge and create an algorithm that can predict attrition. 


### Libraries used:
1. pandas
2. numpy
3. matplotlib.pyplot
4. seaborn
5. sklearn SimpleImputer
6. sklearn train_test_split
7. sklearn SVC
8. sklearn RandomForestClassifier
9. sklearn accuracy_score, precision_score, recall_score, f1_score
10. sklearn GridSearchCV
11. pprint
12. sklearn StandardScaler
13. sklearn classification_report
14. %matplotlib inline

###  Files in the repository:
1. HR Analytics Case Study_Kaggle.ipynb - a jupiter notebook file with the project code
2. Kaggle's data set uploaded by Vijay Choudhary

### Results summary
#### result num 1:
In the question about the correlation between employee' learning investment and attrition, it is hard to determine unequivocally that it has a direct impact, but we can see some positive effect, and conducting 4–6 learning activities per year might reduce attrition. 
#### result num 2:
I tried to check what are the parameters with the highest impact on attrition. Using Support Vector Machine classifier I managed to predict attrition with an accuracy score of 84% and extracted the features with the highest impact on the model results. We can see that education and job roles has a high impact on attrition. 
#### result num 3:
Using Random Forests Model I managed to make a prediction with almost 98% accuracy. To make sure that I don't have overfitting I used GridSearchCV(cv = 5). 

## Acknowledgements:
1. Udacity - for giving me this project as part of Data Science nanodegree 
2. Kaggle - for the data and the problem statement
