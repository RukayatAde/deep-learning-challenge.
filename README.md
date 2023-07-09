# deep-learning-challenge.

OVERVIEW:

The nonprofit foundation Alphabet Soup wants a tool that can help it select the applicants for funding with the best chance of success in their ventures. With your knowledge of machine learning and neural networks, you’ll use the features in the provided dataset to create a binary classifier that can predict whether applicants will be successful if funded by Alphabet Soup.

**Data Preprocessing**

What variable(s) are the target(s) for your model?
* the column IS_SUCCESSFUL was targeted from the application_df for the prediction.

What variable(s) are the features for your model?
* Below are the features used for the model
  -APPLICATION_TYPE—Alphabet Soup application type
  -AFFILIATION—Affiliated sector of industry
  -CLASSIFICATION—Government organization classification
  -USE_CASE—Use case for funding
  -ORGANIZATION—Organization type
  -STATUS—Active status
  -INCOME_AMT—Income classification
  -SPECIAL_CONSIDERATIONS—Special considerations for application
  -ASK_AMT—Funding amount requested
  
What variable(s) should be removed from the input data because they are neither targets nor features? 
* The EIN and NAME columns were dropped fromt the data because they were neither targets nor featues


**Compiling, Training, and Evaluating the Model**

How many neurons, layers, and activation functions did you select for your neural network model, and why?
* For the first neural network model, i used 20 neurons for the first layer and 15 neuron for the second layer. and i chose ReLu as the activation function because it is more faster and does not have vanishing gradient problem.

![Screenshot (7)](https://github.com/RukayatAde/deep-learning-challenge./assets/123358630/85c55eaa-7157-4bf7-a9a7-383009111aac)

  
Were you able to achieve the target model performance?
* The target model performance is 75% but i was able to achieve only 72%

![Screenshot (2)](https://github.com/RukayatAde/deep-learning-challenge./assets/123358630/2824affb-908e-4f70-a4a6-bf8dd6e31a17)

What steps did you take in your attempts to increase model performance?
* In order to increase the model performance, i added more neuron and another layer using the same ReLu activation function

![Screenshot (8)](https://github.com/RukayatAde/deep-learning-challenge./assets/123358630/d7b674a3-cdc1-40be-ac76-a0c32ad9b323)

* I got the same accuracy 72% for this optimization.

![Screenshot (4)](https://github.com/RukayatAde/deep-learning-challenge./assets/123358630/e92e0cbb-5b41-4dc6-bb3a-d5ed00baa388)

Then i decided to use another activation function Tanh, hoping to get better performance.

![Screenshot (9)](https://github.com/RukayatAde/deep-learning-challenge./assets/123358630/2e559cbf-8323-494e-86e9-1ff455107838)

* And again got the same performance which was 72%

![Screenshot (6)](https://github.com/RukayatAde/deep-learning-challenge./assets/123358630/00e28dee-3448-4999-ad29-d69808294835)


**CONCLUSION**
* I was unable to achieve the target performance for this deep learning model. So, if i want to try this in future
  i would make sure the data is properly cleaned, consider adding more neaurons and try other algorithms. 

