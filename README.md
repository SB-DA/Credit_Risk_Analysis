> # Credit Risk Analysis
Modeling and evaluating credit risk using Machine Learning models built in Python.

> ## Overview
Using the credit card credit dataset from LendingClub, a peer-to-peer lending service company, we oversampled the data using **RandomOverSampler** and **SMOTE** algorithms, and undersampled the data using **ClusterCentroids**. Our next approach involved using the **SMOTEENN** algorithm to combine over- and under-sampling. To predict credit risk, we compared two new machine learning models, **BalancedRandomForestClassifier** and **EasyEnsembleClassifier**. Based on these results, we evaluated the performance of the models and made a written recommendation about whether they should be used to predict credit risk.

> ## Results
### Naive Random Oversampling

![image](https://user-images.githubusercontent.com/78935551/123554164-c48d1a00-d74c-11eb-8e3f-6215935874b0.png)

- The Balanced Accuracy Score is **66%**
- Precision high risk score is only **1%** and low risk score is **100%**
- Recall score for hight risk is at **66%** and low risk at **67%**

### SMOTE Oversampling

![image](https://user-images.githubusercontent.com/78935551/123555099-8f36fb00-d751-11eb-91b1-4d62eb32d457.png)

- The Balanced Accuracy Score is again **66%**
- Precision high risk score is only **1%** and low risk score is **100%**
- Recall score for hight risk is at **62%** and low risk at **64%**

### Undersampling Cluster Centroids Algorithm

![image](https://user-images.githubusercontent.com/78935551/123555252-9e6a7880-d752-11eb-80bc-41a3cc347311.png)

- The Balanced Accuracy Score is at **63%**
- Precision high risk score is only **1%** and low risk score is **100%**
- Recall score for hight risk is at **61%** and low risk at **65%**

### SMOTEENN Model

![image](https://user-images.githubusercontent.com/78935551/123555317-05882d00-d753-11eb-996e-12e189085879.png)

- The Balanced Accuracy Score is at **52%**
- Precision high risk score is **1%** and low risk score is **100%**
- Recall score for hight risk is at **70%** and low risk at **57%**

### Balanced Random Forest Classifier

![image](https://user-images.githubusercontent.com/78935551/123555344-336d7180-d753-11eb-9912-317c69d90240.png)

- The Balanced Accuracy Score is at **82%**
- Precision high risk score is **4%** and low risk score is **100%**
- Recall score for hight risk is at **72%** and low risk at **91%**

### Easy Ensemble AdaBoost Classifier

![image](https://user-images.githubusercontent.com/78935551/123555657-0a4de080-d755-11eb-93e6-e282d8adc440.png)

- The Balanced Accuracy Score is at **91%**
- Precision high risk score is **7%** and low risk score is **100%**
- Recall score for hight risk is at **90%** and low risk at **94%**


> ## Summary









