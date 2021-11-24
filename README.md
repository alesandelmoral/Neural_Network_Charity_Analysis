# Neural_Network_Charity_Analysis

## Overview of the analysis: 
The purpose of this challenge is to create a classifier that could predict whether the founding from the company will make successful applicants.

## Results
#### Data Preprocessing
**Target variable**
- "IS_SUCCESSFUL" is selected as the target variable.

**Feature variables**
- All variables in the first part are considered the features for the model and "IS_SUCCESSFUL" will be droped since it will be used as the target variable.

**Removed variables**
- The variables EIN and NAME will be dropped from the data since they don't have an impact in the model. This is for the first part.
- For the optimization trial part, "ORGANIZATION" and "SPECIAL_CONSIDERATIONS" were removed in order to test the model since the graphs showed a big variance.

![04](https://github.com/LennethNova/Neural_Network_Charity_Analysis/blob/main/images/04.PNG)

#### Compiling, Training, and Evaluating the Model
**Neurons, layers, and activation functions**
- In the first model, there were two hidden layers, with 80 neurons the first and 30 neurons the second with the activation functions *relu* for the layers and *sigmoid* for the output.

![01](https://github.com/LennethNova/Neural_Network_Charity_Analysis/blob/main/images/01.PNG)

![02](https://github.com/LennethNova/Neural_Network_Charity_Analysis/blob/main/images/02.PNG)

- **FOR THE OPTIMIZATON**
- For the attempt one, the testing was without the organization and special consideration variables.
- For attempt two, a new hidden layer was added and the epoch lowered.
- For the atempt three, the activation value for the first hidden layer was change to tanh in order to test the outcomes.

**Model performance**
- For now, with this attempts it was not possible to achieve the target performance of 85%.

- The steps that were taken in order to try to achieve a better performance was basically incrementing neurons, changing activation, increasing or decreasing epoch, in order to test if those would improve the model in each attempt.

## Summary: 
Since the dataset might need more data or cleaning, the accuracy of the model before the optimization was at about 72% in accuracy and had a loss of 56%. Unfortunately, removing some data, playing with the layers, activation, epoch and other attributes was not enough to improve the model, and it ended in 52% of accuracy and 70% loss. There were some other approaches that could work if there was enough time to complete the task, and will be tasted at a later time. Those approaches could be by using random forests in order to test the data for possible better results and also more testing on the actual model using different layers, neurons, activations, process, etc.

![03](https://github.com/LennethNova/Neural_Network_Charity_Analysis/blob/main/images/03.PNG)

![05](https://github.com/LennethNova/Neural_Network_Charity_Analysis/blob/main/images/05.PNG)

![06](https://github.com/LennethNova/Neural_Network_Charity_Analysis/blob/main/images/06.PNG)

![07](https://github.com/LennethNova/Neural_Network_Charity_Analysis/blob/main/images/07.PNG)

![08](https://github.com/LennethNova/Neural_Network_Charity_Analysis/blob/main/images/08.PNG)

![09](https://github.com/LennethNova/Neural_Network_Charity_Analysis/blob/main/images/09.PNG)

![10](https://github.com/LennethNova/Neural_Network_Charity_Analysis/blob/main/images/10.PNG)
