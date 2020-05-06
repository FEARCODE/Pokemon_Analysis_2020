# Pokemon_Analysis_2020
ABSTRACT
•	The dataset contains records of various pokemons of various leagues and keeps a track all the details of each pokemon including their stats like hp, attack, defence etc. It also displays various types of pokemon with their various names in other language.
•	This project cleans the data to remove outliers. The pre-processed data is then analysed for strong association rule for the various types of pokemons by apriori and fpgrowth algorithm. The cleaned data is then classified using ID3 classifier to classify the various legendary and non legendary pokemons based upon their hp and total points and is classified into a new column is powerful. The decision tree is also depicted visually through graphviz and pydotplus.
•	The cleaned data is then clustered for pokemons of various stats. It uses Kmeans with binned stats to cluster pokemons with common stats.
•	The conclusion for frequent item sets were 15 item sets each of various types with both the algorithms. In classification , the decision tree is obtained for various stats of pokemon according to their powerfulness and a is_powerful specifies if the pokemon is strong or not by meeting certain requirements. It was noted pokemons with high hp and total points were mostly powerful. In clustering, 5 clusters technique gave the most accurate clusters of pokemons which contained pokemon of similar type. Various stats of pokemons with their clusters are also shown with relabel.





INTRODUCTION
Due to increase in the competition in the way of Ash’s journey to become the pokemon master with a generous path, the type of pokemons he chooses and to catch certain pokemons becomes essential. In this situation, training your weak points also becomes crucial in determining the outcome of the match.
This analysis aims to provide the anime creators and characters developers for animes to recognize the strong and weak points of each pokemon and help ash to claim its victorious path. In the world of cartoon lovers, this analysis will help the creators to analyse the results and make the cartoon more interesting. 
 PROBLEM STATEMENT:-  It becomes hard for pokemon lovers to see Ash lose because of the pokemon he chooses. The amount of support he gets from his pokemons often makes him take wrong decisions.
 OBJECTIVE:- The objective is to segregate the types of pokemons based upon their strength , hp , total points, attack , defence etc. In the view of the above problem the objective is clear to find out strong pokemons that ash can choose during his battle.

SOURCE
The dataset is taken from Kaggle with its updated most recent version: -
https://www.kaggle.com/mariotormo/complete-pokemon-dataset-updated-090420
