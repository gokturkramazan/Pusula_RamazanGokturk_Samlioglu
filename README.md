# Pusula_RamazanGokturk_Samlioglu
Case Study

**Ramazan Göktürk Şamlıoğlu**  
**ramazansamlioglu@gmail.com**

## Project Overview
This project includes data visualization, exploratory data analysis, data preprocessing, filling in missing data, digitizing categorical data and preparing the data for modeling on a drug side effect data set within the scope of a case study.

1. Exploratory Data Analysis (EDA)
In order to understand the data set and examine the patterns in it, data analysis and visualization stages were performed. In this stage, the general structure of the data was analyzed using the Python programming language and Pandas, Numpy, Plotly libraries.

a. Analysis of Data Structure
Data Types: Variable types in the data were examined and it was determined which columns were categorical, numerical or missing.
Detection of Missing Data: Missing data rates were calculated and it was determined which columns had missing values.
b. Data Visualization
The following visualization techniques were used to better understand patterns in the data:

The following visualization techniques were used to better understand patterns in the data:

Histograms: Used to visualize the distribution of numerical variables such as age distribution, body mass index (BMI), duration of medication use.

Pie Charts: Used to visualize the distribution of categorical variables (e.g., gender, blood type).

Cross Tables: Used to understand the relationships between categorical variables.

2. Filling in Missing Data
Missing data identified during the EDA phase were filled in carefully and in a way that did not distort the data distribution:

Categorical Data: Categorical variables such as gender, blood type, chronic diseases were filled in without distorting the existing data ratios.
Numerical Data: Missing numerical data such as weight and height were completed using median or mean values.

3. Data Transformation and Coding
To make the data suitable for machine learning models:

OneHotEncoder: Categorical variables (such as province, drug name, side effect) were converted to numerical values.

LabelEncoder: BMI (Body Mass Index) categories and age groups were digitized.

4. Preparing for Modeling
After all missing data was filled and categorical data was digitized, the dataset was made ready for machine learning models. The dataset is now suitable for model training and testing stages.

## Setup
You can run the project by following these steps:
1. Install the required libraries:
   ```bash
   pip install -r requirements.txt
2. Import the dataset:
    ```bash
   side_effect_data 1.xlsx
4. Run the Project:
   ```bash
   Pusula_RamazanGokturk_Samlioglu.ipynb
   
