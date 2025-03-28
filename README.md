# Aviation-Data-Project

## 1 Overview

This project aims to analyze aviation accident data to identify trends, risk factors, and safety insights. The analysis involves data cleaning, exploratory data analysis (EDA), visualization, and saving the processed data for future use.

## 2 Project Workflow

1. **Data Cleaning**:
   - Addressing missing values
   - Removing unnecessary columns
   - Converting date formats for consistency
2. **Exploratory Data Analysis (EDA)**:
   - Generating summary statistics using `.describe()`
   - Identifying key patterns in the dataset
3. **Data Visualization**:
   - Implementing bar charts, line graphs, scatter plots, and pie charts
   - Analyzing accidents based on aircraft type, model, country, year, and weather conditions
4. **Exporting Cleaned Data**:
   - Saving the processed dataset as a CSV file for further analysis
5. **Insights & Conclusion**:
   - Summarizing major findings and trends from the analysis

## 3 Dataset Description

The dataset contains aviation accident records with details including:

- Date, location, and country of the accident
- Aircraft make, model, and type
- Number of fatalities and injuries
- Weather conditions at the time of the incident
- Phase of flight during the accident

## 4 Key Findings

- Trends in aviation accidents over the years
- Aircraft manufacturers with the highest accident rates
- Countries with the most fatal injuries
- Influence of weather conditions on accidents

## 5 Installation & Requirements

Here i ensured that I have the necessary Python libraries installed:

```python
import pandas as pd for data manipulation
import numpy as np for numerical operations
import matplotlib.pyplot as plt for Data visualization purposes
import seaborn as sns for statistical data visualization purposes ```
```

## 6 Running the Project
1. Load the dataset into a Pandas DataFrame.
2. Perform data cleaning and transformations.
3. Generate visualizations to uncover insights.
4. Save the cleaned dataset using:
   ```python
   aviation_clean.to_csv("cleaned_aviation_data.csv", index=False)
   ```
## Now we have a clean dataset with no missing data and no duplicates which enhances better analysis
# Aviation-Data-Project

## 1 Overview

This project aims to analyze aviation accident data to identify trends, risk factors, and safety insights. The analysis involves data cleaning, exploratory data analysis (EDA), visualization, and saving the processed data for future use.

## 2 Project Workflow

1. **Data Cleaning**:
   - Addressing missing values
   - Removing unnecessary columns
   - Converting date formats for consistency
2. **Exploratory Data Analysis (EDA)**:
   - Generating summary statistics using `.describe()`
   - Identifying key patterns in the dataset
3. **Data Visualization**:
   - Implementing bar charts, line graphs, scatter plots, and pie charts
   - Analyzing accidents based on aircraft type, model, country, year, and weather conditions
4. **Exporting Cleaned Data**:
   - Saving the processed dataset as a CSV file for further analysis
5. **Insights & Conclusion**:
   - Summarizing major findings and trends from the analysis

## 3 Dataset Description

The dataset contains aviation accident records with details including:

- Date, location, and country of the accident
- Aircraft make, model, and type
- Number of fatalities and injuries
- Weather conditions at the time of the incident
- Phase of flight during the accident

## 4 Key Findings

- Trends in aviation accidents over the years
- Aircraft manufacturers with the highest accident rates
- Countries with the most fatal injuries
- Influence of weather conditions on accidents

## 5 Installation & Requirements

Here i ensured that I have the necessary Python libraries installed:

```python
import pandas as pd for data manipulation
import numpy as np for numerical operations
import matplotlib.pyplot as plt for Data visualization purposes
import seaborn as sns for statistical data visualization purposes ```
```

## 6 Running the Project
1. Load the dataset into a Pandas DataFrame.
2. Perform data cleaning and transformations.
3. Generate visualizations to uncover insights.
4. Save the cleaned dataset using:
   ```python
   aviation_clean.to_csv("cleaned_aviation_data.csv", index=False)
   ```
## Now we have a clean dataset with no missing data and no duplicates which enhances better analysis
