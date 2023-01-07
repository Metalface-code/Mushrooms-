# Mushroom Medical Study-

## Data Summary-

### There were 8,124 samples in the data
### Classified by a total of 23 features
### This data was found at https://www.kaggle.com/datasets/uciml/mushroom-classification
### According to Kaggle.com, this dataset includes descriptions of hypothetical samples corresponding to 23 species of gilled mushrooms in the Agaricus and Lepiota Family Mushroom drawn from The Audubon Society Field Guide to North American Mushrooms (1981). Each species is identified as definitely edible, definitely poisonous, or of unknown edibility and not recommended. This latter class was combined with the poisonous one. The Guide clearly states that there is no simple rule for determining the edibility of a mushroom; no rule like "leaflets three, let it be'' for Poisonous Oak and Ivy.

# Problem- 

## Which mushrooms were safe for humans in medical use?

## Keys to follow

Attribute Information: (classes: edible=e, poisonous=p)

cap-shape: bell=b,conical=c,convex=x,flat=f, knobbed=k,sunken=s

cap-surface: fibrous=f,grooves=g,scaly=y,smooth=s

cap-color: brown=n,buff=b,cinnamon=c,gray=g,green=r,pink=p,purple=u,red=e,white=w,yellow=y

bruises: bruises=t,no=f

odor: almond=a,anise=l,creosote=c,fishy=y,foul=f,musty=m,none=n,pungent=p,spicy=s

gill-attachment: attached=a,descending=d,free=f,notched=n

gill-spacing: close=c,crowded=w,distant=d

gill-size: broad=b,narrow=n

gill-color: black=k,brown=n,buff=b,chocolate=h,gray=g, green=r,orange=o,pink=p,purple=u,red=e,white=w,yellow=y

stalk-shape: enlarging=e,tapering=t

stalk-root: bulbous=b,club=c,cup=u,equal=e,rhizomorphs=z,rooted=r,missing=?

stalk-surface-above-ring: fibrous=f,scaly=y,silky=k,smooth=s

stalk-surface-below-ring: fibrous=f,scaly=y,silky=k,smooth=s

stalk-color-above-ring: brown=n,buff=b,cinnamon=c,gray=g,orange=o,pink=p,red=e,white=w,yellow=y

stalk-color-below-ring: brown=n,buff=b,cinnamon=c,gray=g,orange=o,pink=p,red=e,white=w,yellow=y

veil-type: partial=p,universal=u

veil-color: brown=n,orange=o,white=w,yellow=y

ring-number: none=n,one=o,two=t

ring-type: cobwebby=c,evanescent=e,flaring=f,large=l,none=n,pendant=p,sheathing=s,zone=z

spore-print-color: black=k,brown=n,buff=b,chocolate=h,green=r,orange=o,purple=u,white=w,yellow=y

population: abundant=a,clustered=c,numerous=n,scattered=s,several=v,solitary=y

habitat: grasses=g,leaves=l,meadows=m,paths=p,urban=u,waste=w,woods=d
 

# The goal was to find which mushrooms were safe for consumption for posible use in medical studies 

# The Process 

### I created the following models to test how well we could classify the safe and not so safe mushrooms,
### 1. K nearest neigbors or KNN for short due to the simplicity and good accuracy 
### 2. Random forest classifier to see if it was anymore or less accurate
### 3. Tested the pipelines with and without PCA to see if we could add value to the model through faster processing

# Visuals

![image](https://user-images.githubusercontent.com/105470937/192131532-94287028-cd41-46b6-a943-3e186b4380ed.png)
### This is showing our comparrison of how many mushrooms we found to be safe for consumption

![image](https://user-images.githubusercontent.com/105470937/192001520-bbbc31b9-1511-4368-ba0d-24da66d8b5e9.png)
### As seen above the model was very accurate in giving the perfect ratio of which mushrooms were safe and which were poisonous

![image](https://user-images.githubusercontent.com/105470937/193191688-cd9172e7-82a1-4940-9d2d-ec89252b72a2.png)
### We also found that strong smells meant the mushrooms were unsafe for consumption

# Conclution and Reccomendation
## In the end I found that, 
### The model I tested was very accurate in finding which mushrooms were safe and useful for medical trails with humans
## The mushrooms with strong oders and no rings were poisonous. We can take strong odors as natures sign to stay away from unsafe handling of consumption 
of those mushrooms.
### Random Forrest and KNN were used and compared to see which was more accurate but also more efficient
### The KNN model was the best when used with PCA since it made the model 40 % more efficient without sacrificing accuracy
