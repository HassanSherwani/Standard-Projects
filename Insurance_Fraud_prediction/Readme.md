# Insurance Fraud Prediction

Claim provisions are crucial for the financial stability of insurance companies. However; the mutant and erratic behavior of insurance affecting variables are, it is not advisable to use a large database while predicting insurance claims. The insurance industry is believing in data analytics to adopt the changing technologies to provide better facilities to their customers.
In this projecty, age-based, lifestyle-based and BMI-based insurance claims are made. We approached to the claimed accuracy through various models such as Logistic classification, Naïve Bayes, Decision Tree, K-Nearest Neighbor, Support Vector machine, and Random Forest. We put an effort to maximize the accuracy score by using hyper parameter tunning technique as well. Finally, results are evaluated on accuracy, precision, recall and f1 score metrices. We found that Random Forest provided an accuracy of 97%. We also analyzed feature importance function and found that BMI, having children, alcoholism are the most significant features for our model.

### Keywords:
 Insurance claim, MLOps., machine learning, model training, hyper-parameter tunning. 

# Data Description:
- age: age of the policyholder
- sex: gender of policy holder (female=0, male=1)
- BMI: Body mass index, providing an understanding of body, weights that are relatively high or low relative to height, objective index of body weight (kg / m ^ 2) using the ratio of height to weight, ideally 18.5 to 25
- children: number of children/dependents of the policyholder
- alcohol: alcoholism state of policyholder (non-alcoholic=0; alcoholic=1)
- region: the residential area of policyholder in the US (northeast=0, northwest=1, southeast=2, southwest=3)
- charges: individual medical costs billed by health insurance
- insuranceclaim – The labelled output from the above features, 1 for valid insurance claim / 0 for fraud.

