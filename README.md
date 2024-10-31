# Titanic-Survival-Analysis

This project aims to analyze the Titanic dataset to predict passenger survival based on various features. Using machine learning techniques, we will explore the factors that contributed to survival and build a predictive model.


## Datasets
- **train.csv**: Contains data on Titanic passengers, including features such as:
  - `PassengerId`: Unique ID for each passenger
  - `Pclass`: Ticket class (1st, 2nd, or 3rd)
  - `Name`: Passenger name
  - `Sex`: Gender of the passenger
  - `Age`: Age in years
  - `SibSp`: Number of siblings/spouses aboard
  - `Parch`: Number of parents/children aboard
  - `Ticket`: Ticket number
  - `Fare`: Ticket fare
  - `Cabin`: Cabin number
  - `Embarked`: Port of embarkation (C = Cherbourg; Q = Queenstown; S = Southampton)
  - `Survived`: Survival status (0 = No, 1 = Yes)

- **test.csv**: Similar to the training set, but does not include the `Survived` column.

## Getting Started

### Prerequisites
Make sure you have Python 3.x installed along with the required libraries. You can install the necessary packages using the following command:

```bash
pip install -r requirements.txt
