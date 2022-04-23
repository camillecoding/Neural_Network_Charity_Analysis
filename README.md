# Neural_Network_Charity_Analysis
This project uses machine learning to analyze data to predict which funding applicants will outperform their grants.

## Overview ##
The client wants to create a more effective method of evaluating grant applications. They want to predict the applicant's success in achieving their outlined goals if they receive the grant and used previous performance data to build a model for future grants. I am using Tensorflow and Neural Network machine learning to evaluate these applicants. My goal is to achieve an accuracy rate above 75%.

## Results ##
### Data Preprocessing ###
* The target of my model was 'IS_SUCCESSFUL', the variable that revealed whether the grantee was successful in achieving their goal after receiving the grant.
 
* The feaures of my model were...

* The variables I removed from my input data were 'NAME' and 'EIN'. These had to be removed because they were categorical variables unrelated to my model's performance - they also were defining characteristics that could introduce bias. Removing them allows my model to be anonymous.

After removing the testing variable and building my model, my first set of results only produced a 73% accuracy rate, slightly less than my goal of 75%. 

## Summary ##
