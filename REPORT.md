### Alphabet Soup is a nonprofit foundation that wants to make informed decisions when selecting applicants to fund. They want to maximize the chances of success for the projects they support. To help them with this, we will use machine learning and neural networks to build a tool that can predict whether an applicant will be successful if funded by Alphabet Soup.

#### We have a dataset that contains information about previous applicants and their outcomes. Using this data, we will train a model to recognize patterns and make predictions. The model will analyze various factors and characteristics of the applicants to determine the likelihood of their success.

#### By using this tool, Alphabet Soup will be able to evaluate new applicants and make more informed funding decisions. It aims to increase the number of successful projects and make a positive impact on the community.

#### What variable(s) are the target(s) for your model?
- The IS_SUCCESSFUL is the target variable for the model
#### What variable(s) are the features for your model?
- The other column headings that were not dropped for not having pertinent information are the features for the model
#### What variable(s) should be removed from the input data because they are neither targets nor features?
- The variables that were removed were EIN and name neither had an impact on the outcome and were not proper for privacy reasons


### Compiling, Training, and Evaluating the Model

#### How many neurons, layers, and activation functions did you select for your neural network model, and why
- The model consists of three dense layers 
- Layers 1 - 32 units ReLu activation
- Layer 2 - 16 units ReLu activation
- Layer 3 - 1 unit  Sigmoid activation
- This combination produced the best accuracy vs loss ratio
#### Were you able to achieve the target model performance?
- Unfotunately target model performance was not achieved
- loss: 0.5554 - accuracy: 0.7232
#### What steps did you take in your attempts to increase model performance?
- different activation (tanh,sigmoid)
- alternate optimizer RMSprop
- alternate loss method hinge

### Summary

 The model achieved a reasonable accuracy, there is room for improvement. To further improve the model's performance, additional steps can be taken, such as gathering more data, preprocessing the data more effectively, and training the model on different sections of the data. These actions can potentially enhance the model's ability to generalize and make more accurate predictions. Continuous exploration and experimentation are key to refining the model and achieving better results.