# Neural Network Charity Analysis

## Analysis Overview
To create a binary classifier to predict whether or not applicants will be successful if they were to receive money for Alphabet Soup.

## Data processing - 1st attempt
The charity_data.csv contains more then 34,000 organizations that have received funding from Alphabet Soup over the years. Listed are the columns in the data set:
-  EIN and  - NAME—Identification columns
- APPLICATION_TYPE—Alphabet Soup application type
- AFFILIATION—Affiliated sector of industry
- CLASSIFICATION—Government organization classification
- USE_CASE—Use case for funding
- ORGANIZATION—Organization type
- STATUS—Active status
- INCOME_AMT—Income classification
- SPECIAL_CONSIDERATIONS—Special consideration for application
- ASK_AMT—Funding amount requested
- IS_SUCCESSFUL—Was the money used effectively

#### What variable(s) are considered the target(s) for your model?
IS_SUCCESSFUL 

#### What variable(s) are considered to be the features for your model?
APPLICATION_TYPE',
 'AFFILIATION',
 'CLASSIFICATION',
 'USE_CASE',
 'ORGANIZATION',
 'INCOME_AMT',
 'SPECIAL_CONSIDERATIONS'

#### What variable(s) are neither targets nor features, and should be removed from the input data?
"EIN", "NAME"
