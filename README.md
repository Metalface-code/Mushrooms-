# Mushrooms-

# In this dataset the goal is to find which mushrooms were safe for consumption in grocery stores and for possible medical use. 

## There were 8,124 samples in the data
## classified by a total of 23 features
## Data was found at https://www.kaggle.com/datasets/uciml/mushroom-classification
## According to Kaggle.com, this dataset includes descriptions of hypothetical samples corresponding to 23 species of gilled mushrooms in the Agaricus and Lepiota Family Mushroom drawn from The Audubon Society Field Guide to North American Mushrooms (1981). Each species is identified as definitely edible, definitely poisonous, or of unknown edibility and not recommended. This latter class was combined with the poisonous one. The Guide clearly states that there is no simple rule for determining the edibility of a mushroom; no rule like "leaflets three, let it be'' for Poisonous Oak and Ivy. 



# Here is 3 reasons I loved working with this data
### 1. This is actually a fairly simple dataset to work with because it starts off clean with no duplicates or missing values
### 2. Everything was an object so this was really fun given the flexibility of the data
### 3. The subject matter was very interesting and could be used to truly help in different areas of business and science

# I used the following models to test how well we could classify the safe and not so safe mushrooms
### 1. I used K nearest kneigbors or KNN for short due to the simplicity and good accuracy for the most part
### 2. I also compared it to a Random forest classifier to see if it was anymore or less accurate
### 3. I also test the pipelins with and without PCA to see if data loos for speed made a difference in accuracy

# Visualizations
![image](https://user-images.githubusercontent.com/105470937/192131532-94287028-cd41-46b6-a943-3e186b4380ed.png)

![image](https://user-images.githubusercontent.com/105470937/192001520-bbbc31b9-1511-4368-ba0d-24da66d8b5e9.png)
## As seen above the model was very accurate in giving the perfect ratio of true values for the ratio of poisonous mushrooms and edible mushrooms 

# In the end I found that 
###  1. Due to the type of data in this classification and how simple it is the PCA didnt make much of a difference since the size of the dataset is not super huge the time it took to run was also not much different
### 2. The model I stuck with was the KNN model sped up by the PCA since it increased effeciency by 40% and since the data did not change much with PCA it is more logical to use the faster model. 
### 3. This model of this data set would seem to be a good fit in production if you were looking to study types of mushrooms that are consumable for grocery stores and even medical purposes if you wanted to start with a safe ingredient for medicnes.
