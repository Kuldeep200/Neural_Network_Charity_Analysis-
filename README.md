# Neural_Network_Charity_Analysis-
Beks has come a long way since her first day at that boot camp five years ago—and since earlier this week, when she started learning about neural networks! Now, she is finally ready to put her skills to work to help the foundation predict where to make investments.

With your knowledge of machine learning and neural networks, you’ll use the features in the provided dataset to help Beks create a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup.

From Alphabet Soup’s business team, Beks received a CSV containing more than 34,000 organizations that have received funding from Alphabet Soup over the years. Within this dataset are a number of columns that capture metadata about each organization, such as the following:

EIN and NAME—Identification columns
APPLICATION_TYPE—Alphabet Soup application type
AFFILIATION—Affiliated sector of industry
CLASSIFICATION—Government organization classification
USE_CASE—Use case for funding
ORGANIZATION—Organization type
STATUS—Active status
INCOME_AMT—Income classification
SPECIAL_CONSIDERATIONS—Special consideration for application
ASK_AMT—Funding amount requested
IS_SUCCESSFUL—Was the money used effectivel

Results: Using bulleted lists and images to support your answers, address the following questions.

Data Preprocessing

##What variable(s) are considered the target(s) for your model?

These predictions will be based on the 'IS_SUCCESSFUL' column in the provided data.

What variable(s) are considered to be the features for your model?

AFFILIATION
APPLICATION_TYPE
ASK_AMT
CLASSIFICATION
INCOME_AMT
ORGANIZATION
SPECIAL_CONSIDERATIONS
STATUS
USE_CASE

What variable(s) are neither targets nor features, and should be removed from the input data?

The columns for "NAME" and "EIN" have no direct effect on the success/falure rate, and have been excluded from processing.

Compiling, Training, and Evaluating the Model

How many neurons, layers, and activation functions did you select for your neural network model, and why?

Initial preparation for the Sequential Neural Network specified 43 input features, into three processing layers that began with 80 neurons and decreased to 30.


Were you able to achieve the target model performance?

The target performance of 80% accuracy was not met (72.75%).


What steps did you take to try and increase model performance?

i tried to add more layers and neurons, but the accurcy for three results was still 72`%

Summary: Summarize the overall results of the deep learning model. Include a recommendation for how a different model could solve this classification problem, and explain your recommendation.

I would  recommend non-sequential hyperparameter models as a way to improve accuracy. We have minimized loss by using these tuned models, despite not increasing success rate to 75%
