# Predicting High-Risk Covid-19 Patients and Mortality Rates

This project analyzes COVID-19 deaths based on conditions, age groups, and the states in which people are located. It uses historical data to create a model that helps determine patients' mortality rates and whether or not they are high-risk.

### Dataset

The dataset has been included in the repository as a zip file.
It can also be found at this URL: https://catalog.data.gov/dataset/conditions-contributing-to-deaths-involving-coronavirus-disease-2019-covid-19-by-age-group

### Features

- **Data Processing and Cleaning:**
    - Clean and standardize the data
    - Remove outliers
    - Replace and handle missing values
    - Standardize formats
- **Database Optimization:**
    - Use database strategies to handle the large dataset efficiently.
    - Standardize tables for easy queries on age groups  and conditions of individuals.
- **Machine Learning Model:**
    - Train a model based on historical data on COVID-19 deaths.
    - Use predicted deaths to determine the mortality rate of patients for COVID-19.
- **Evaluation:**
    - Use MSE, R^2 score, and MAE to evaluate the model.
- **Visualization and Reporting:**
    - Generate visualizations of COVID-19 death rates based on age and condition groups.
 
### Requirements

The Following Libraries are used:

- `pandas`
- `numpy`
- `scipy.stats`
- `sqlite3`
- `matplotlib.pyplot`
- `seaborn`
- `sklearn`
- `xgboost`

### Key Functions

Model was tested by inputting the state an individual is in, their age group, and what condition they have. The model would then return their predicted deaths for COVID-19. The predicted deaths are used to determine the patient's mortality rate for COVID-19 which will then determine if they are high-risk.

## Example
To determine high-risk COVID-19 patients:
```python
test_case = [['New Jersey','65-74', 'Respiratory failure']]

Returns:
State        Age Group        Condition         Predicted Deaths
New Jersey     65-74     Respiratory failure      125.371330

To determine the Mortality Rate (%):
Age Group	    Condition	        Predicted Deaths	Total Deaths	Mortality Rate
65-74	   Respiratory failure	       125.371330	      10721.0	       1.169400
```


