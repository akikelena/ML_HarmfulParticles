# AnalysisLinRegClssf_HarmfulParticles
Machine learning project for the purpose of pattern recognition course. 

The database which is used for the purpose of this project contains 52584 samples, where each of them is described with 17 features.

This project includes following steps:
1. Data analysis
- number of features and samples
- what represents one sample of database
- cathegorical and numerical features
- missing data - how much, where it occurs and how to solve it
- (un)logical data
- deeper feature analysis - statistical quantities, distributions
- detailed analysis of feature related to the concentraction of harmful particles PM_US Post
- visualisation of dependence of the PM2.5 change on other features
- analysis of correlations of other features

2. Creation of a linear regression model
- split data into 3 sets - training/validation/testing
! validation not finished !
- try different hypotheses
- try different regularization types
- choose the best linear regression model

3. Creation of a kNN classifier that sorts samples into categories based on the target feature
- assign labels to the samples from database - safe, unsafe, dangerous
- split data into 2 sets - training/testing
- cross-validation with 10 subsets
- determine the optimal parameters
- make confusion matrix obtained by accumulation matrix from each of 10 cross-validation iteerations, using optimal parameters
- train the classifier with the finally selected paramteres
- test it on a separate test set
- calculate success measures for classifier, as well as performance measures for each class - accuracy, sensitivity, specificity, precision, F measure


