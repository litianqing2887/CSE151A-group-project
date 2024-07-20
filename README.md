# CSE151A-group-project
## Group Members
Frank Li, til027@ucsd.edu  
Po-Cheng Lai, p1lai@ucsd.edu  
Yixuan Li, yil177@ucsd.edu  
Zhaogu Sun, zhsun@ucsd.edu  

## Data Description
Estimation of Obesity Levels Based On Eating Habits and Physical Condition. (2019). UCI Machine Learning Repository. https://doi.org/10.24432/C5H31Z.  
There are 2111 instances with 16 features. There are no missing values. 
|Variable Name                 |Role    |Type         |Description                    |
|------------------------------|--------|-------------|-------------------------------|
|Gender                        |Feature |Catagorical  |                               |
|Age                           |Feature |Continuous   |                               |
|Height                        |Feature |Continuous   |                               |
|Weight                        |Feature |Continuous   |                               |
|family_history_with_overweight|Feature |Binary       |Has a family member suffered or suffers from overweight?|
|FAVC|Feature |Binary       |Do you eat high caloric food frequently?|
|FCVC|Feature |Integer      |Do you usually eat vegetables in your meals?	|
|NCP |Feature |Continuous   |How many main meals do you have daily?|
|CAEC|Feature |Categorical  |Do you eat any food between meals?|
|SMOKE|Feature |Binary       |Do you smoke?|
|CH2O|Feature |Continuous   |How much water do you drink daily?|
|SCC|Feature |Binary       |Do you monitor the calories you eat daily?|
|FAF|Feature |Continuous     |How often do you have physical activity?|
|TUE|Feature |Integer     |How much time do you use technological devices such as cell phone, videogames, television, computer and others?|
|CALC|Feature |Categorical   |How often do you drink alcohol?|
|MTRANS|Feature |Categorical |Which transportation do you usually use?|
|NObeyesdad|Target |Categorical|Obesity level|  

## Preprocessing Methods
First, we checked the statistical values, including mean and std.  
Then, we encoded non-numerical features into numerical values. 
We also did some feature expansions on the categorical data which converted each level into separate columns and encoded them using binary.
Finally, we picked up some features and drew some graphs to see the correlations between features.  
[Milestone 2 Jupyter Notebook](Group_Project_MileStone_2.ipynb)

## First Model
### Evaluation
We normalized and standardized the data.  
We wanted to do a classification, predicting the obesity level of a person based on their physical conditions and lifestyles. Therefore, the first model we tried was the logistic regression. We split the data into train and test sets with a ratio of 9:1 and trained the model.  
The training accuracy is 0.759 and the testing accuracy is 0.717. It indicates that our model is still underfitting. And our model is not accurate enough.  
### Conclusion
In our first model, we used logistic regression, and the accuracy we got was not as ideal as we expected, but we successfully predicted around 70% of our testing and training data. We want to find a better way to deal with our categorical data since our categorical data have multiple levels that cannot just be represented by binary.  
### Next Model
Since the accuracy of our model is not as ideal as expected, we are thinking of using neural network as our next machine learning model. The reason why we want to choose neural network is that the perceptrons can perform non-linear transformations. By doing so, we can increase the complexity of our model which may help us improve our accuracy.  
[Milestone 3 Jupyter Notebook](Group_Project_MileStone_3.ipynb)



