## Project Overview
  The project is about the recent pandemic we had in 2020, that claimed alot of lives in almost every countries and continient. Using Just Python for the analysis to answer every essential questions.

## Data Source 
 Covid'19: The data use for this analysis was the record made available for us all on Kaggle. The data contain some quite data about the covid pandemic. The data comprises of regions, total case, total death recorded, etc.
<img width="1478" height="637" alt="Data set" src="https://github.com/user-attachments/assets/579c924a-c9dd-4e93-9ccf-53e889642bf8" />



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
   
<img width="953" height="230" alt="Q1" src="https://github.com/user-attachments/assets/c4d1f72c-e1b6-4ee7-8a24-41d3d97db3a2" />
2.  Which countries had the highest number of total cases and deaths?

<img width="1111" height="680" alt="Tatal death by Country" src="https://github.com/user-attachments/assets/ec69fc20-7a2f-4354-b68c-7ec63fb0464b" />
<img width="1190" height="698" alt="Total case by country" src="https://github.com/user-attachments/assets/fedc3736-e09e-496a-bb78-f862283e3fe5" />

3. Which continent had the highest and lowest death percentage?
<img width="1007" height="623" alt="Continent by death percentage" src="https://github.com/user-attachments/assets/727060e3-2045-4581-ab9e-0d95b156f3d8" />

4. What is the average death percentage across countries?
   <img width="1551" height="190" alt="Average death percentage" src="https://github.com/user-attachments/assets/dff6f8a3-7255-43c4-a30b-dd755aba394b" />

5. Is there a correlation between the population size and the total number of cases or deaths in a country?
   <img width="1637" height="375" alt="correlation" src="https://github.com/user-attachments/assets/564cc7b4-53e1-43e2-9675-97675d9409db" />
6. Which countries managed to keep their death percentage low despite a high number of cases?
<img width="1638" height="484" alt="low death percentage" src="https://github.com/user-attachments/assets/38df0372-917c-48af-8d80-0c7be3eeb34b" />

7.  Based on the death percentage, which countries should be considered for further analysis regarding their healthcare response?
<img width="1660" height="437" alt="Death Percentage by country" src="https://github.com/user-attachments/assets/a2ce6399-f7d3-4d05-b0a1-138b7ecec7d6" />

   
