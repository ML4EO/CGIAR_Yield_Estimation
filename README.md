# CGIAR_Yield_Estimation
Maize yields prediction in East African farms particularly Rwanda using satellite imagery data and machine learning models

#### Tasks performed 
1. Downloading and Loading the dataset of the zip files from Zindi or add them to the Google drive using the following links:

##### Test data: 
https://drive.google.com/file/d/1yTEgzn8JJn0mZmJ7NDUbwAB1WSzwRScB/view?usp=sharing

##### Training data: 
https://drive.google.com/file/d/1-0UNiBpvfdRq8rgUC3Kb22YPWP_YnoKj/view?usp=sharing

Use the smaller files from Zindi (Train.csv, SampleSubmission.csv and bandnames.txt) uploaded by using the files tab.

2. Sampling from the images

There are some hard-coded band indexes in the examples above that won't have made sense - how did we know which bands were which? There are 30 bands for each month.

3. Fitting a model
The goal is to find a set of parameters that minimize the difference between the predicted output and the actual output for the training data.
