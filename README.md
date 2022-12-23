# Python-Bitcoin-Analysis

## Purpose
#### Predictive Procedures in Python. 
We use regression and machine learning techniques such as random forests, clustering, and classification to forecast bitcoin. The main goal is to provide crytpocurrency traders additional information to determine stop-loss levels and optimal points of entry. On-chain metrics are a new phenomea in the world of finance and it is solely a cryptocurrency trait. These new metrics have not been thoroughly analyzed by many. This leads to our second goal which is to determine what metrics are the most useful for traders to observe and what metrics are useless.

### Contributers: 
Brian Scott,
Anthony Galka,
Erin Blair,
Maddie Coffey,
Sam Ian

### Exploratory Analysis
#### Link:
##### Key Findings:

### Clustering
#### Link: https://github.com/Brian-Scott25/Python-Bitcoin-Analysis/blob/main/ProjectClusteringStandardization.ipynb
##### Key Findings: 
The accuracy, precison, and recall scores for the clustered models did not improve. We concluded clustering was not necessary for this data. This is not surprising considering the best sillhouette score we were able to get was .36.

### Regression
#### Link:
##### Key Findings:

### Classification
#### Link: https://github.com/Brian-Scott25/Python-Bitcoin-Analysis/blob/main/Classification.ipynb
##### Key Findings: After using Niave Bayes and Decision Tree Classifiers we were able to determine the best model was for the 2 category decision tree model with a depth of 3. The test set accuracy was 62.7%. However, in the time period of our dataset, Bitcoin increased 51% of the time. Considering we are trying to predict something that has a 50/50 chance of increasing or decreasing, an accuracy in the 60s is signfcant. 


