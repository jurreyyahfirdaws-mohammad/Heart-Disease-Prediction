# Heart-Disease-Prediction
Based on a cardiovascular study of people of the Massachusetts town of Framingham, risk evaluation and estimation for potential coronary coronary artery/heart disease (CHD)
Determine whether the individual has a 10-year risk of developing coronary heart disease (CHD) is the categorization objective. Information about the patients is provided by the dataset. 15 qualities and more than 4,000 records are present.
I have made predictions for this dataset using KNN and logistic regression.

## Observations
The Model is currently more selective than sensitive in nature, as precision > recall.
In case of any disease detection, Recall is a very significant metric.
Because False Negative detections can be fatal for the life of person.
Hence our aim is to improve the recall metric (or sensitivity) of our model.
In order to make model more sensetive to the Risk:
We need to lower the threshold of our model
we have used initial threshold as 0.5
We have to carefully lower our threshold to some value, such that recall becomes significantly higher, without heavily hampering accuracy.
