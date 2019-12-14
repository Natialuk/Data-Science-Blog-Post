# Data Science Blog Post
### CRISP-DM:
Replacing employees is a large investment. A company must spend significant time and money to search for the best talent through advertising, recruitment agencies, screening, interviewing, and hiring. According to studies done by the Center for American Progress, the cost of employee attrition varies based on the role of the employee and their salary/wage level. In the study, the CAP found the following:

For low-paying jobs i.e. earning less than 30,000 USD per year, the average cost of replacement was found to be 16% of annual salary. For example, it would cost 3,328 USD to replace an employee earning 10/hour.
For positions that earn between 30,000 USD and 50,000 USD per year, the cost of replacement was found to be 20% of annual salary.
For executives earning high salaries, the cost of replacement was found to be 213% of annual salary. (Boushey & Glynn, 2012). For example, an executive who earns 100,000 USD would cost 213,000 USD to replace.
In order to reduce employee attrition, companies are conducting multiple activities such as training, internal mobility, salary revision etc.

The challenge is predicting attrition before it happens. In this study, I'll try to investigate attrition triggers and create a model that will predict attrition.

I'll try to answer 3 questions:

Is conducting more training activities can reduce employee attrition?
What are the main factors in employee attrition?
Is it possible to predict employee attrition?
XYZ (a company of about 4000 employees) published a case study on Kaggle describing a problem where the company suffers from 15% attrition per year which has a high impact on the company. I'll use it to do my invatigation.


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
2. Employees_data.csv - Kaggle's data set uploaded by Vijay Choudhary

### Results summary
#### result num 1:
In the question about the correlation between employee' learning investment and attrition, it is hard to determine unequivocally that it has a direct impact, but we can see some positive effect, and conducting 4–6 learning activities per year might reduce attrition. 
#### result num 2:
I tried to check what are the parameters with the highest impact on attrition. Using Support Vector Machine classifier I managed to predict attrition with an accuracy score of 84% and extracted the features with the highest impact on the model results. We can see that education and job roles has a high impact on attrition. 
#### result num 3:
Using Random Forests Model I managed to make a prediction with almost 98% accuracy. To make sure that I don't have overfitting I used GridSearchCV(cv = 5). 

## Acknowledgements:
1. Udacity - for giving me this project as part of Data Science nanodegree and for  many code references  
2. Kaggle - for the data and the problem statement (uploaded by Vijay Choudhary)
3. Stackoverflow - for many problem solving cases (from installing packages to code instructions)
4. Medium - for the blog post platform
