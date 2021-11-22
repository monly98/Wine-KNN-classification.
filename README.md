# Wine-KNN-classification.
# inspection of dataset
Wine dataset has 177 data samples and 3 labels. 
# Feature engineering
Featuring engineering is the most important part of machine learning. In order for a model to perform well it requiers a good quality data 
wichh is free of null values, duplicates, noise outliers etc. Otherwise it will follow "GIGO" garbage in and garbage out.
# Feature scaling
After cleaning of data we scale the data with normalization and standadrization techniques to fit the data into a standard scale.
# KNN classifier
We train the dataset using KNN model which find the Euclidian distance between the new test data sample
and all the samples of training data. 
Based on the distance and number of nearest neighbors selected, we sort the distances with minimum values.
If majority of the sorted distance values belong to one specific class we then we put new test sample into that specific class. 
In this way we classify the whole test dataset and check the prediction of the model.
# model validation 
In this part we look into the model prediction that is how accurate it is to the unknown data by finding its accuracy.
