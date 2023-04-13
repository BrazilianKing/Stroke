# Stroke

## Predicting the chances of an individual having a stroke
Edmar Dos Santos

### Context
According to the World Health Organization stroke is the 2nd leading cause of death. Strokes are responsible for approximately 11% of total deaths. This dataset is used to predict whether a patient is likely to get stroke based on the input parameters like gender, age, various diseases, and smoking status. Each row in the data provides relavant information about the patient.

## Data: 
https://www.kaggle.com/datasets/fedesoriano/stroke-prediction-dataset

### For this dataset, there were 5110 rows and 12 columns.

# Methods
### To prepare this data, the data was cleaned, and the following processes were performed:
We sliced, flitered, searched for duplicates and dropped any coloumns that we felt were not import for this particual project.

# Visual 1 Title
![smoking status](https://user-images.githubusercontent.com/123523010/231825089-4ab970bf-c78c-46e3-a73d-16fab6d1d954.png)

### Here in this data we are comparing the

# Visual 2 Title
![work type p2p4](https://user-images.githubusercontent.com/123523010/231826712-322b7938-6059-491f-8571-f9fc1073c0d9.png)

### Based upon this 

# Results of Models
## The Decision Tree Model was chosen for this set of data
## Decision Tree Model Test Scores
### R^2(R-Squared Score): 0.162

### This score can be interpreted as saying that our model can account for about 16% of the variation in y_test using the features in X_test.

### RMSE(Root Mean Squared Error) : 1091.27

### This means the number is slightly higher because their were some test that had higher variance from the predictions. It impacts the total dollar amount because they are further away.
### These two metrics can help us predict new sales data within $1,100.

# Recommendations
### I would recommend checking the other models to see if we can find any improvments in our data.

# Next Steps
### I would say that more data needs to be include and to run more models with the new data being included.

# For futher questions: 
### Please email Edmar Dos Santos at edmardossantos85@gmail.com
