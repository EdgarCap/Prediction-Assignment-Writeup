# Prediction-Assignment-Writeup

Using devices such as Jawbone Up, Nike FuelBand, and Fitbit it is now possible to collect a large amount of data about personal activity relatively inexpensively. These type of devices are part of the quantified self movement - a group of enthusiasts who take measurements about themselves regularly to improve their health, to find patterns in their behavior, or because they are tech geeks. One thing that people regularly do is quantify how much of a particular activity they do, but they rarely quantify how well they do it.
In this project, we will use data from accelerometers on the belt, forearm, arm, and dumbell of 6 participants. They were asked to perform barbell lifts correctly and incorrectly in 5 different ways.
The data consists of a Training data and a Test data (to be used to validate the selected model).
The goal of your project is to predict the manner in which they did the exercise. This is the “classe” variable in the training set. You may use any of the other variables to predict with.

## Prediction of the exercice

The variable "classe" in the training dataset have this value:

* "A" the exercice is done according to specification 

* "B" the exercice is done throwing the elbows to the front

* "C" the exercice is done lifting the dumbbell only halfway

* "D" the exercice is done lowering the dumbbell only halfway 

* "E"  the exercice is done throwing the hips to the front 

## Data 
The training data for this project are available here: 

https://d396qusza40orc.cloudfront.net/predmachlearn/pml-training.csv

The test data are available here:

https://d396qusza40orc.cloudfront.net/predmachlearn/pml-testing.csv

Note: The dataset used in this project is a courtesy of “Ugulino, W.; Cardador, D.; Vega, K.; Velloso, E.; Milidiu, R.; Fuks, H. Wearable Computing: Accelerometers’ Data Classification of Body Postures and Movements”  (http://web.archive.org/web/20161224072740/http:/groupware.les.inf.puc-rio.br/har )

Original paper:

http://web.archive.org/web/20170519033209/http://groupware.les.inf.puc-rio.br/public/papers/2013.Velloso.QAR-WLE.pdf

Full dataset:

http://web.archive.org/web/20161224072740/http://groupware.les.inf.puc-rio.br/static/WLE/WearableComputing_weight_lifting_exercises_biceps_curl_variations.csv


