# Project Idea: A Wine Recommender System in Java
Engine that recommends best wine/food/cheese parings

### MCIT 591 Spring 2019 - Final Project

### Submitted on: March 31st 2019

### Teammates: Eunice Hameyie, Paul De Sanctis, Viktoriya Bondarenko



## Description:
Unless you are a connoisseur, most people struggle to pair the correct wine with their food or cheese. In this project, we build the recommender agent we wished existed. 
### Minimum Viable Product (MVP)
The user enters the meal or cheese she is about to partake of, as well as her location (zip code). The recommender outputs the best wine to pair her meal/cheese with, with a short explanation. The system also outputs the second best and cheaper wine to pair her food, as well as the worst wine she should not pair it with. 

The recommender system then answers general statistics about its datasets:
What is the highest rated wine?
What is the lowest rated wine?
Which country makes the best wine?
Which country has the worst wine?
Which grapes make the best wine?
### Additional Feature
Depending on time, we will implement a recommendation of wine tasting events within 25 miles of the user’s location. 

## Work Breakdown (preliminary):
#### Identify base wine dataset - Eunice
Using kaggle https://www.kaggle.com/sudhirnl7/wine-recommender/data 
#### Import dataset and write descriptive stats code: 
Rank wine in dataset from highest to lowest rated - Paul
Rank wine from cheapest to most expensive - Paul
Rank countries with most popular wines - Paul
Rank grapes for most rated wines - Viktoriya
Rank grapes for most expensive wines - Viktoriya
#### Identify dataset on wine and cheese pairings - Viktoriya
If API or dataset not readily available for download, create a database of wine and cheese pairings based on info from https://vinepair.com/wine-blog/an-illustrated-guide-to-pairing-wine-and-cheese/ and https://www.winemag.com/2015/03/26/wine-and-cheese/ 
#### Identify dataset on wine and meal pairings -Paul
If API or dataset not readily available for download, create a database of wine and cheese pairings based on info from http://sedimentality.com/drinking-wine/list-of-wine-and-food-pairings/ and https://www.foodandwine.com/slideshows/15-rules-great-wine-and-food-pairings#7 or https://winefolly.com/tutorial/getting-started-with-food-and-wine-pairing/
#### Identify database of wine festivals or tasting events per geographical locations - Eunice
Maybe a Google API or yelp? https://www.yelp.com/nearme/wine-tasting
#### Build the recommendation engine/predictor
#### Actual recommendation in Java:
Implement content based filter - Paul
Implement collaborative filter - Eunice
Try out Weka for advanced stats/machine learning - Eunice
#### Implement test use cases to test and validate all use cases run properly
Confirm user can only enter predefined food categories  Viktoriya
Confirm user enters valid location,; if not that system returns “Zip code cannot be located, please re-enter” - Viktoriya
Confirm correct statistics are displayed answering questions in the description - Eunice
Confirm correct wine pairings are recommended - Viktoriya
