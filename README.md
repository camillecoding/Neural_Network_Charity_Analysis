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
* I built my model using 6 neurons and 6 layers. I used two activation functions, ReLu and Tanh and my output was Sigmoid.

* I did not achieve my target model performance. After removing the testing variable and building my model, my first set of results only produced a 72.5% accuracy rate, slightly less than my goal of 75%.
<img width="690" alt="Screen Shot 2022-04-23 at 11 30 01 AM" src="https://user-images.githubusercontent.com/95657458/164912705-8afb0119-065b-4ed8-af88-9b8f3872c3cd.png">

* I tested several combinations of neurons, layers, and activation functions to achieve my performance. After starting with too few neuron/layer combinations and achieving ~50% accuracy, I increased these to 6 each. I also tested different combinations of activation functions. Although using ReLu for both activation functions in my input layer achieved the same results as the combination of ReLu and Tanh, I decided to stick with two separate activation functions in the end.
<img width="672" alt="Screen Shot 2022-04-23 at 11 34 06 AM" src="https://user-images.githubusercontent.com/95657458/164912821-053b0183-1fc9-4029-a630-f9ae0affb1d8.png">

 
## Summary ##
