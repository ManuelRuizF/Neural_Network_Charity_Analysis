# Neural Network Charity Analysis
## Overview of the analysis
The purpose of this analysis is to use deep-learning neural networks with the TensorFlow so we can analyze and classify the success of charitable donations.
We use the following methods for the analysis:

- Preprocessing the data for the neural network model.
- Compile, train and evaluate the model.
- Optimize the model.
## Results

### Data Preprocessing
- What variable(s) are considered the target(s) for your model?  
**The column IS_SUCCESSFUL is considered as the target for our deep learning neural network.**
- What variable(s) are considered to be the features for your model?  
**The following columns APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS, INCOME_AMT, SPECIAL_CONSIDERATIONS, ASK_AMT.**  
- What variable(s) are neither targets nor features, and shuld be removed from the input data?  
**EIN and NAME** 

### Compiling, Training, and Evaluating the Model
How many neurons, layers, and activation functions did you select for your neural network model, and why?
- **80 and 30 neurons**
- **2 hidden layers**
Were you able to achieve the target model performance?
**No, almost. We reached a 74% a accuracy** 
What steps did you take to try and increase model performance?
- **add more layers**
- **add more neurons**
Summary: Summarize the overall results of the deep learning model. Include a recommendation for how a different model could solve this classification problem, and explain your recommendation.
