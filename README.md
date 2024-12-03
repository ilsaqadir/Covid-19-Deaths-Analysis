# Covid-19-Deaths-Analysis
This project analyzes COVID-19 deaths based on conditions, age groups, and the states in which people are located. It uses historical data to create a model that helps determine patients' mortality rates and whether or not they are high-risk.

### Dataset

The dataset has been included in the repository.
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
    - Train a model based on historical COVID-19 death rates.
    - Create a classification model to find high-risk patients.
- **Evaluation:**
    - Use MSE, R^2, and MAE to evaluate the model.
- **Visualization and Reporting:**
    - Generate visualizations of predicted death rates based on age groups and condition groups.
 
### Requirements

The Following Libraries are used:

- `pandas`
- `numpy`
- `scipy.stats`
- `sqlite3`
- `matplotlib.pyplot`
- `seaborn`
- `sklearn`

### Key Functions

Test the model by inputting the state an individual is in, their age group, and what condition they have. The model would then return their predicted deaths for COVID-19. Then it uses the predicted deaths to determine the patient's mortality rate for COVID-19.


