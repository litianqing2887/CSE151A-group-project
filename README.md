# CSE151A-group-project
## Group Members
Frank Li, til027@ucsd.edu  
Po-Cheng Lai, p1lai@ucsd.edu  
Yixuan Li, yil177@ucsd.edu  
Zhaogu Sun, zhsun@ucsd.edu  
## Data Description
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
## Preprocessing Method
First, we checked the statistical values, including mean and std. Besides, we encoded non-numerical features into numerical values. Finally, we normalized and standardized the data and drew some graphs to see the correlations between features.  
[Jupyter Notebook](https://colab.research.google.com/drive/1bwOXfLWkiFjfF43SzX0UnQkWO8P_tlpO?usp=sharing)
