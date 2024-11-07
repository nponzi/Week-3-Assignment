##Data Set## 
The Breast Cancer dataset from scikit-learn is what was used for this project

##Model that was used##
I used a RandomForestClassifier due to its ability to handle very large datasets with a high accuracy

##Steps##
1. First I loaded the dataset into the workbook with scikit's built in functions
2. Then I analyzed the raw data to help understand the key statistics
3. Next I preprocessed the data using scikit's StandardScaler in order to transform the data to have a mean of 0 and standard deviation of 1, this will allow all features to contribute equally to the model's performance
4. I then split the data into a training set and test set
5. Next I built the RandomForestClassifier model
6. Lastly I trained the model and evaluated it


##Results##
The results showed that there was a 96.49% accuracy in the model's performance. This is a strong indicator that our model is performing well.
When looking at the confusion matrix it appears that our model has a high precision, high recall, and high F1 scores. This means our model is very accurate with only a few misclassifications. 
