# deep_learning_challenge

## Background
The nonprofit foundation Alphabet Soup wants a tool that can help it select the applicants for funding with the best chance of success in their ventures. With your knowledge of machine learning and neural networks, you’ll use the features in the provided dataset to create a binary classifier that can predict whether applicants will be successful if funded by Alphabet Soup.

From Alphabet Soup’s business team, you have received a CSV containing more than 34,000 organizations that have received funding from Alphabet Soup over the years. Within this dataset are a number of columns that capture metadata about each organization.

Using TensorFlow, I designed a neural network, or deep learning model, to create a binary classification model that can predict if an Alphabet Soup-funded organization will be successful based on the features in the dataset. Next, I compiled, trained, and evaluated my binary classification model to calculate the model’s loss and accuracy.

## Overview of the analysis: Explain the purpose of this analysis.
## Results: Using bulleted lists and images to support your answers, address the following questions:
## Data Preprocessing
1. What variable(s) are the target(s) for your model?
- The target is the Is-Successful column.
2. What variable(s) are the features for your model?
- Features list of this model are the following: name, application, type affiliation classification use_case organization income special consideration status and ask amount.
3. What variable(s) should be removed from the input data because they are neither targets nor features?
- EIN (Employee identification)
## Compiling, Training, and Evaluating the Model
1. How many neurons, layers, and activation functions did you select for your neural network model, and why?
- For this model 3 hidden layers each with many neurons because the compute seems to increate the accuracy above 75% this expensive and costly. The first activations is relu and the other layers are sigmoid it might boost accuracy using the functions. Readjusting my data that names as a get dummies can factor in with better scores.
2. Were you able to achieve the target model performance?
- Yes.
3. What steps did you take in your attempts to increase model performance?
- Required to convert the NAME into data points which has the biggest impact on improving efficiency but costly and it requires adding third layer using sigmoid activation function.

## Summary: Summarize the overall results of the deep learning model.
- Overall the accuracy above 75% we are able to correctly classify each in the test 75% of the time. And an applicant has a 80% chance of being successful if they following this:
  - Name of applicants appears more than 5 tmes type of applications following T3 T4 T5 T6 T7 T8 T10 T19 application of following classification ...
 
## Include a recommendation for how a different model could solve this classification problem, and then explain your recommendation.
- RandomForest model
