## Fundamental-of-Databse-Management-System

This is the dataset from kaggle Reddit_Data Amber Heard - Social Network Analysis
Only the data of 2018 is taken from the Reddit
Tools which are used are Google Colab, Python and Gephi.

# Our Network Layout
![Picture 1](https://user-images.githubusercontent.com/93224923/163781968-d25714f6-8a8d-4d85-9929-0b847cd6888c.png)
![Picture 1](https://user-images.githubusercontent.com/93224923/163782005-f136189b-4f33-4538-b5ac-d2a812aa22a0.png)

# Coloured nodes as per community class
![Picture 1](https://user-images.githubusercontent.com/93224923/163782120-1afee289-2fba-4256-91fe-9fe6163fca34.png)

# The Pink one denotes Sreddit id ( Subreddit id) and Green ones denotes pid ( Parent id) 
![Picture 1](https://user-images.githubusercontent.com/93224923/163782541-517720bc-ce21-4cdf-975d-d437bd2e5b2d.png)

# Edge weight filter which displays strong bindings
![Picture 1](https://user-images.githubusercontent.com/93224923/163782668-39989e0b-5af0-4f14-8067-98f67301d1ed.png)

# Conclusion
In our data we have about 4.71% is subreddit which means that 4.71% data is a specific to some community/post whereas the rest 95.29% data is normal texts and has a parent id. From our modularity test we got to know we have 133 communities which is a high number which means we have dense connections between the nodes within modules but sparse connections between nodes in different modules. Through our modularity class we got to know that 6-7 communities dominate with 13.22% coming from community 5 (Pink) and 13.03% coming from community 58 (Green). After that from nested filters we got to know sentiment of each text whether it was positive/negative/neutral and grouped them accordingly. According to our data p31 is of a  positive sentiment , eg “First thing that pops into my head. Every time". We also got to know that 13.85% text were negative , 25.02% positive and rest were neutral . Then we say Edge weigh filter which is highest with p2573 (Source) and P2601(Target) which is 1160 (shows the strongest connection).

