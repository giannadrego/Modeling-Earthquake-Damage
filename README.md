# Modeling-Earthquake-Damage

Based on aspects of building location and construction, our goal is to predict 
the level of damage to buildings caused by the 2015 Gorkha earthquake in 
Nepal. 

The target variable is damage_grade, which represents a level of damage to the 
building that was hit by the earthquake. 
There are 3 grades of the damage:
1 represents low damage
2 represents a medium amount of damage
3 represents almost complete destruction

The dataset consists of information on the buildings' structure and their legal ownership. Each row in the dataset represents a specific building in the region that was 
hit. In training data set there are 26k rows and 39 columns/features, where each building is uniquely identified by building_id.

Data Preprocessing : 
1. Check for null values and outliers
2. Feature Engineering using Random Forest Classifier
3. Normalization using Min-Max technique

Model Training and Evaluation:
1 Trained dataset using Gaussian Naive Bayes and SVM model and compare the model accuracy.
2. F1 score for metric evaluation. 
