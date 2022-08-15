# Credit_Risk_Analysis

## 1. Overview of the analysis: 
The objective is to predict risks from clients using different machine learning models. We will analyse the performance of such models to end with a recommendation as to how they should be used to predict risk.
It´s important to mention that Credit Risk is an inherently unbalance classification problem as good loans outnumbered risky loans, so models used need to take into consideration the nature of this data.

## 2. Results:
We had 6 algorithms:
### i.  Naive Random Oversampling
The balance accuracy was: 62.5%
For high risks, the scores were:
* Precision: 0.01
* Recall: 0.60
* F1 score: 0.02

![Algorithm1](https://github.com/karen-trena/Credit_Risk_Analysis/blob/main/Picture1.png)

### ii.  SMOTE Oversampling
The balance accuracy was: 65.1%
For high risks, the scores were:
* Precision: 0.01
* Recall: 0.64
* F1 score: 0.02

![Algorithm2](https://github.com/karen-trena/Credit_Risk_Analysis/blob/main/Picture2.png)

### iii.  Undesampling with Cluster Centroids algorithm
The balance accuracy was: 65.1%
For high risks, the scores were:
* Precision: 0.01
* Recall: 0.59
* F1 score: 0.01

![Algorithm3](https://github.com/karen-trena/Credit_Risk_Analysis/blob/main/Picture3.png)

### iv.  Combination (over and under) sampling
The balance accuracy was: 63.8%
For high risks, the scores were:
* Precision: 0.01
* Recall: 0.70
* F1 score: 0.02

![Algorithm4](https://github.com/karen-trena/Credit_Risk_Analysis/blob/main/Picture4.png)

### v.  Ensemble Balanced Random Forest Classifier
The balance accuracy was: 99.6%
For high risks, the scores were:
* Precision: 0.73
* Recall: 0.34
* F1 score: 0.47

![Algorithm5](https://github.com/karen-trena/Credit_Risk_Analysis/blob/main/Picture5.png)

### vi.  Easy Ensemble Ada Boost Classifier
The balance accuracy was: 92.5%
For high risks, the scores were:
* Precision: 0.07
* Recall: 0.91
* F1 score: 0.14

![Algorithm6](https://github.com/karen-trena/Credit_Risk_Analysis/blob/main/Picture6.png)

## 3. Summary:  
For this type of models, it is more important the precision than the recall. The only model with a descent precision was "Ensemble Balance Random Forest Classifier"; needless to say that it´s is more important the numbers regarding High Risk as this is where the sample is lacking of real data as they always tend to be much less that data from Low Risk. It´s is also important to mention that the accuracy of the model was really good, as it reached 99.6%.
