# Neural Network Charity Analysis
This project uses machine learning to analyze data to predict which funding applicants will outperform their grants.

## Overview ##
The client wants to create a more effective method of evaluating grant applications. They want to predict the applicant's success in achieving their outlined goals if they receive the grant and used previous performance data to build a model for future grants. I am using Tensorflow and Neural Network machine learning to evaluate these applicants. My goal is to achieve an accuracy rate above 75%.

## Results ##
### Data Preprocessing ###
* The target of my model was 'IS_SUCCESSFUL', the variable that revealed whether the grantee was successful in achieving their goal after receiving the grant.
 
* The feaures of my model were...

* The variables I removed from my input data were 'NAME' and 'EIN'. These had to be removed because they were categorical variables unrelated to my model's performance - they also were defining characteristics that could introduce bias. Removing them allows my model to be anonymous.

### Compiling, Training, and Evaluating the Model ###
* I built my model using 6 neurons and 6 layers. My input function was Tanh and the output was Sigmoid.

* I did not achieve my target model performance. After removing the testing variable and building my model, my first set of results only produced a 72.5% accuracy rate, slightly less than my goal of 75%.
<img width="702" alt="Screen Shot 2022-04-23 at 11 15 24 AM" src="https://user-images.githubusercontent.com/95657458/164912165-fb73bc03-929b-463f-98e3-1b9a58aa6972.png">

*

 

## Summary ##
