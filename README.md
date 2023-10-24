# deep-learning-challenge
## Overview of the analysis: 
### To develop a predictive model that can determine the success or effectiveness of organizations funded by AlphabetSoup Charity. By using machine learning techniques, we aim to create a binary classification model that can identify whether an organization will make effective use of funding.

## Results: Using bulleted lists and images to support your answers, address the following questions:
### Data Preprocessing
#### What variable(s) are the target(s) for your model?
A single target variable for classification problem. In this case, it might be y_train and y_test as they have shapes (27439,) and (6860,), respectively.

#### What variable(s) are the features for your model?
50 feature variables in the dataset, which are used to make predictions. These are likely represented by X_train and X_test.

#### What variable(s) should be removed from the input data because they are neither targets nor features?
It's not clear which variables should be removed without more information about dataset and problem. The decision to remove specific variables should be based on domain knowledge, feature engineering, and data analysis.

### Compiling, Training, and Evaluating the Model
How many neurons, layers, and activation functions did you select for your neural network model, and why?
dense (Dense): The first hidden layer with 8 neurons.
dense_1 (Dense): The second hidden layer with 5 neurons.
dense_2 (Dense): The third layer, which is the output layer with 1 neuron for binary classification.
Were you able to achieve the target model performance?
The target model performance in terms of accuracy was 75%. The actual accuracy achieved by the model was 72,6%. the target accuracy was not met, the possible reasons for this and areas for improvement can be discussed.
What steps did you take in your attempts to increase model performance?
still no find the method to increase model performance
Summary: Summarise the overall results of the deep learning model. Include a recommendation for how a different model could solve this classification problem, and then explain your recommendation.
