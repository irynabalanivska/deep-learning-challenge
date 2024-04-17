# deep-learning-challenge
mod 21

This analysis aims to develop a binary classifier using TensorFlow-based deep learning networks to predict the success of funding applications for Alphabet Soup.

Results
Data Preprocessing
Target Variable: IS_SUCCESSFUL, indicating effective use of funds.
Feature Variables: Include APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS, INCOME_AMT, and ASK_AMT.
Variables Removed: EIN, NAME, STATUS, and SPECIAL_CONSIDERATIONS, as they lacked predictive value.

Model Development
Configuration: Utilized two hidden layers; the first with 100 neurons and the second with 40, both using ReLU activation. The output layer employed a sigmoid activation function.
Performance: The model's accuracy reached 65.75%, improving from an initial 53.78% but below the target of 75%. Efforts to enhance performance included adjusting the binning of variables and experimenting with model architecture.

Summary
The model demonstrated potential in predicting funding success, though it did not meet the 75% accuracy goal, indicating potential areas for further optimization.
