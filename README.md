# Mushroom study-

# Data summary-

## There were 8,124 samples in the data
## Classified by a total of 23 features
## This data was found at https://www.kaggle.com/datasets/uciml/mushroom-classification
## According to Kaggle.com, this dataset includes descriptions of hypothetical samples corresponding to 23 species of gilled mushrooms in the Agaricus and Lepiota Family Mushroom drawn from The Audubon Society Field Guide to North American Mushrooms (1981). Each species is identified as definitely edible, definitely poisonous, or of unknown edibility and not recommended. This latter class was combined with the poisonous one. The Guide clearly states that there is no simple rule for determining the edibility of a mushroom; no rule like "leaflets three, let it be'' for Poisonous Oak and Ivy.

# Problem- 

## Which mushrooms were safe for consumption in grocery stores and for possible medical use?
 

# The goal was to find which mushrooms were safe for consumption for posible use in medical studies 

## I created the following models to test how well we could classify the safe and not so safe mushrooms,
### 1. K nearest kneigbors or KNN for short due to the simplicity and good accuracy 
### 2. Random forest classifier to see if it was anymore or less accurate
### 3. Tested the pipelins with and without PCA to see if we could add value to the model through faster processing

# Visuals

![image](https://user-images.githubusercontent.com/105470937/192131532-94287028-cd41-46b6-a943-3e186b4380ed.png)
### This is showing our comparrison of how many mushrooms we found to be safe for consumption

![image](https://user-images.githubusercontent.com/105470937/192001520-bbbc31b9-1511-4368-ba0d-24da66d8b5e9.png)
### As seen above the model was very accurate in giving the perfect ratio of which mushrooms were safe and which were poisonous

Conclution and Reccomendation
# In the end I found that, 
### The model I tested was very accurate in finding which mushrooms were safe and usful for medical trails with humans 
### Random Forrest and KNN were used and compared to see which was more accurate but also more effecient for cost effectiveness 
### The KNN model was the best when used with PCA since it made the model 40 % more effecient without sacrificing accuracy
