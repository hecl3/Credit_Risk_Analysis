# Credit_Risk_Analysis

**Overview:**

For this analysis we took the data from clients looking at loans, cleaned it, and determined how well an algorithm could see if they are a good candidate for financial assistance or not.

**Results:**

* Naive Random Oversampling
              * Naive Random had a balanced accuracy score of about 66.2% and average recall score of 60%
* SMOTE Oversampling
              * SMOTE Oversampling had a balanced accuracy score of 65.6% and average recall score of 70%
* Undersampling
              * Undersampling had a balanced accuracy score of 54.4% and average recall score of 40%
* Combination (Over and Under) Sampling
              * Combination had a balanced accuracy of 63.9% and average recall of 59%
* Balanced Random Forest Classifier
              * Balanced Random Forest had a balanced accuracy of 78.8% and average recall of 87%
* Easy Ensemble AdaBoost Classifier
              * Easy Ensemble AdaBoost had a balanced accuracy of 93.1% and average recall of 94%


**Summary:**

We tested six different types of machine learning to see which would best accomodate our data type. The Resampling types were the least effective for this dataset, only reaching a balanced accuracy score of 65.6% at it's highest and average recall of 70%, lowest being 54.4% with low average recall score of 40%. The Ensemble types were much more effective, the lowest being the Balanced Random Forest model that had an accuracy score of 78.8% and average recall of 87%.

The clear winner though is the Easy Ensemble AdaBoost Classifier, which had a balanced accuracy score of 93.1% and average recall rate of 94%, making it the best suited by far to use for this type of data.
