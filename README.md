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

I tried an optimizing my parameters to discover whether I could achieve my target performance. I created a model that tested several parameters to find the highest performers. Even with optimized parameters, I still only achieved 73% accuracy. 
<img width="465" alt="Screen Shot 2022-04-23 at 12 43 27 PM" src="https://user-images.githubusercontent.com/95657458/164915335-cad902cb-b2dd-4adb-b1a8-6f55dd0392b6.png">
<img width="723" alt="Screen Shot 2022-04-23 at 12 43 41 PM" src="https://user-images.githubusercontent.com/95657458/164915361-07489708-5afc-4e64-a630-ee41e6c540cf.png">

 
## Summary ##
