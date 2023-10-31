# Starbucks Capstone Challenge

## Introduction
The Starbucks Capstone Challenge involves analyzing simulated data mimicking customer behavior on the Starbucks rewards mobile app. The goal is to determine which demographic groups respond best to which types of offers.

## Technical Information
Libraries used:
- Pandas
- Numpy
- Matplotlib
- Seaborn
- json
- math
- Sklearn
    - AdaBoost Classifier
    - train_test_split
    - DecisionTreeClassifier
    - Gaussian NB
    - RandomForestClassifier
    - accuracy_score
    - GridSearchCV

## Installation 
Libraries were previously installed. An update had to be made to the Seaborn library using: pip install seaborn --upgrade

## Data Exploration and Analysis
### Portfolio Dataset:
- Reviewed the structure and data types of the dataset.
- Checked for missing values.
- Generated statistical summaries.

### Profile Dataset:
Key insights from the profile dataset include:
- The dataset has a higher number of males compared to females, with a smaller representation of other genders.
- Most users are aged between 30-70 years, with some erroneous data showing an age of 118.
- The majority of users earn between $50,000 and $80,000.
- Membership saw a steady increase from 2013 to 2017, with a decline in 2018.

### Transcript Dataset:
The transcript dataset is also explored in detail, with specific focus given to unique individuals in the dataset and any potential missing values.

## Data Cleaning and Preprocessing:
- The dataset columns were renamed for clarity.
- Missing values were addressed.
- Feature engineering was performed, especially for the transcript dataset.

## Data Visualization and Exploration
From the visual explorations:

#### Portfolio Dataset:
- There are three types of offers: BOGO (buy-one-get-one-free), discount, and informational. BOGO and discount offers are more prevalent.
- Most offers last between 5 to 10 days.
- The "difficulty" level, representing the amount a user needs to spend to avail an offer, varies, with many offers requiring a spend of 0-10 units (likely currency).

#### Profile Dataset:
- There is a higher number of transactions by males, but the rate of offer completion, compared to the number of offers viewed, seems higher for females.
- Income and Age:
Users with higher incomes appear more likely to complete offers.
The overall income distribution remains consistent across all event types.

## Modeling and Evaluation
Creating predictive models:
- Feature engineering and data preparation for modeling.
- Creation of models using algorithms like AdaBoost.
- Hyperparameter tuning using GridSearchCV.
- Evaluation of model performance.

## Reference and Acknowledgements
The datasets used in this project were provided by Udacity.

### Other References
https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.DataFrame.replace.html
https://pandas.pydata.org/pandas-docs/version/0.23.4/generated/pandas.merge.html
https://stackoverflow.com/questions/37600711/pandas-split-column-into-multiple-columns-by-comma
https://stackoverflow.com/questions/64815227/attributeerror-module-seaborn-has-no-attribute-histplot

Read blogpost [here](https://medium.com/@ifyobi21/an-analysis-of-the-starbucks-mobile-app-rewards-f36f95b0707e)
