# Wine-KNN-classification.
Wine dataset has 177 data samples and 3 labels. We train the dataset using KNN model which find the Euclidian distance between the new test data sample
and all the samples oftraining data. 
Based on the distance and number of nearest neighbors selected we sort the distances with minimum values.
If majority of the sorted distance values belong to one specific class we then we put new test sample into that specific class. 
In this way we classify the whole test dataset and check the prediction of the model.
