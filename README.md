# Titanic
Analysis of Titanic passenger data and predicting passenger survival rates using various ML models

### Data Source
[Kaggle: Titanic - Machine Learning from Disaster](https://www.kaggle.com/c/titanic)

### Exploratory Data Analysis
#### Distribution of ages by Passenger Class:
![download](https://user-images.githubusercontent.com/25490217/144762187-aafafdcd-5827-4164-b5f5-09a3bc5a5e34.png)
#### Survival Rates by Passenger Class: 
![download](https://user-images.githubusercontent.com/25490217/144762206-ac5496e0-dcfc-46d2-bbed-50dde3b2f7a2.png)

There is a very clear distinction between between passenger classes and survival where 1 = Survived and 0 = Did not Survive.
#### Normalized Survival Rates by Gender:
![download](https://user-images.githubusercontent.com/25490217/144762309-6ce85ccd-cda1-48da-8d27-cebdc962b66f.png)

There is a very clear distinction between between gender and survival where 1 = Survived and 0 = Did not Survive. Approximately 68% of females in the data survived while only 32% of males survived. 
#### Survival Rates by Class and Gender:
![download](https://user-images.githubusercontent.com/25490217/144762403-c555caa9-1660-4c04-89d4-97b6c5c2a64e.png)

Gender appears to play a large role in survival rates, while passenger calss also appears to be significant as we can see a clear distinction in survival raates between all 3 classes. 

### Machine Learning Algorithms
Three different ML algorithms were evaluated (Linear Regression, Polynomial Regression, and Decision Tree). The decision tree after pruning (maximum depth of 3 and split of 4) proved to be the mosst accurate model of the three with an 83% accurancy score and 82% cross-validated score.

### Conclusion and Next Steps
##### Feature Engineering
- Can try to predict Age based on title in name i.e. Miss -> younger etc.
- Currently only looking at assuming empty ages as the median of all ages
##### Data Selection
- Can also take a look at the point of embarkment
##### Algorithm Selection
- Explore other algorithms
