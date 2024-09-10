# A/B Testing on Marketing Campaigns

## Title
A/B Testing on Marketing Campaigns

## Problem Statement
We aim to determine which marketing campaign is the most effective in increasing sales. By comparing three different campaigns, we can identify the best strategy to maximize sales.

## Results Interpretation
- **Campaign 1 vs Campaign 2**: Campaign 1 significantly outperforms Campaign 2 with a p-value close to 0.
- **Campaign 1 vs Campaign 3**: No significant difference between Campaign 1 and Campaign 3.
- **Campaign 2 vs Campaign 3**: Campaign 3 significantly outperforms Campaign 2 with a p-value much lower than 0.05.

## Methodology
1. **Data Collection**: We collected sales data from different outlets over several weeks.
2. **Data Cleaning**: Ensured there were no missing values and checked for unique values.
3. **Exploratory Data Analysis (EDA)**: Visualized the data to understand the distribution and trends.
4. **A/B Testing**: Conducted t-tests to compare the sales performance of different campaigns.

## Steps Done
1. **Data Loading**: Loaded the dataset using pandas.
2. **Data Inspection**: Checked the first 10 rows, number of rows and columns, features, missing values, and unique values.
3. **Descriptive Statistics**: Calculated mean, standard deviation, and other statistics for the dataset.
4. **Visualizations**: Created various plots to visualize sales distribution, market sizes, and outlet ages.
5. **A/B Testing**: Performed t-tests to compare the sales performance of different campaigns.

## Dataset
The dataset contains the following columns:
- **OutletID**: Unique identifier for each outlet.
- **MarketSize**: Size of the market (Small, Medium, Large).
- **AgeofOutlets**: Age of the outlets in years.
- **Campaigns**: Campaign identifier (1, 2, 3).
- **Week**: Week number.
- **SalesInThousands**: Sales in thousands of dollars.

The dataset has 548 rows and 6 columns with no missing values. The unique values for each column are as follows:
- **OutletID**: 137 unique values
- **MarketSize**: 3 unique values (Small, Medium, Large)
- **AgeofOutlets**: 25 unique values
- **Campaigns**: 3 unique values (1, 2, 3)
- **Week**: 4 unique values
- **SalesInThousands**: 517 unique values

The dataset provides a comprehensive view of sales performance across different campaigns, market sizes, and outlet ages, allowing for a thorough analysis of marketing effectiveness.
