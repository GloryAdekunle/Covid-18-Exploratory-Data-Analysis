# Covid'19 Exploratory Data Analysis
## Project Overview
  The project is about the recent pandemic we had in 2020, that claimed alot of lives in almost every countries and continient. Using Just Python for the analysis to answer every essential questions.

## Data Source 
 Covid'19: The data use for this analysis was the record made available for us all on Kaggle. The data contain some quite data about the covid pandemic. The data comprises of regions, total case, total death recorded, etc.

 ## TOOLS
 - Python
 - Pandas
 - Matplotlib
 - Seaborn

## Data Cleaning/Preparation
The following tased was performed on the data:
- Data importing and inspections
  ``` python
      # Importing necessary libraries
      import numpy as np
      import pandas as pd
      import matplotlib.pyplot as plt
      import warnings
      warnings.filterwarnings('ignore')

      #importing the dataset
      df = pd.read_excel("Covid'19.xlsx")
      df

  ```
- Handling the duplicate values
- Handling the null values
  ``` python
      #checking the null values
      df.isnull().sum()

  ```

## Exploratory Data Analysis
  The EDA involves exploring the data to answer these questions:
 1. What is the total number of COVID-19 cases and deaths globally?
 2. Which countries had the highest number of total cases and deaths?
 3. Which continent had the highest and lowest death percentage?
 4. What is the average death percentage across countries?
 5. Is there a correlation between the population size and the total number of cases or deaths in a country?
 6.  Which countries managed to keep their death percentage low despite a high number of cases?
 7.  Based on the death percentage, which countries should be considered for further analysis regarding their healthcare response?

## Data Analysis
For the analysis, Matplotlib came in handy, in handling all the visualisation as well as pandas for manipulations of data.

1. What is the total number of COVID-19 cases and deaths globally?
   
