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
![work type   bmi](https://user-images.githubusercontent.com/123523010/231905784-0b964038-c01c-4cd0-a73f-e396ef3c6b61.png)

### Those patients who are in the work force have a much higher BMI than those who are not. Those who are self employed seem to have the highest BMI of them all which I believed would have been the exact opposite.

# Visual 2 Title
![smoking status   stroke](https://user-images.githubusercontent.com/123523010/231906078-733e479a-b525-4625-8b84-1317166c7153.png)

### Based upon this graph it shows that the patients who formerly smoked are more than likely to have a stroke. Even a higher chance than those who are currently smoking.

# Results of Random Forest Classifier
## The RandomForest Model was chosen for this set of data with GS as well.
## RF Model Test Score
### Accuracy: 0.94

### This score can be interpreted as saying that our model can account for a 94% accuracy on predicting if someone will have a stroke or not.


### Both KNN & RF models gave us 94% accuarcy. But based on my experience RandomForest tends to yeild better results. So as more data is collected I will contiue to lean more on the RandomForest model.

# Recommendations
### I would recomened getting more data and removing any data that is considered 'unknown'.


# For futher questions: 
### Please email Edmar Dos Santos at edmardossantos85@gmail.com
