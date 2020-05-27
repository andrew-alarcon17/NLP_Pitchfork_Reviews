# NLP_Pitchfork_Reviews

## Goal
As someone who reads Pitchfork reviews very often, I wanted to see how sepcific language in these written reviews reflects whether or not an album is considered good or bad. To do this, I constructed a bag of words model in order to classify these albums.

## Steps Taken

* We define an ablum being good as having a score of anything above 6.5, and bad with anything lower than 6.5.

* The scores column is then converted to binary (1 is good, 0 is bad) in order to make classificaiton simpler.

* The dataset was converted from a csv to a tsv in order to create a bag of words model.

* After the bag of words model is created, several classification techniques were ran on the data to see which would be best in predicting if a record was good or bad based on the written reviews.

<img src="https://github.com/andrew-alarcon17/NLP_Pitchfork_Reviews/blob/master/Pitchfork_NLP_Vis/Random%20Forest.png" width="500">

Here we see the performance of a Random Forest Classifier, with an accuracy of 85%.

