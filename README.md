# Zircon Assessment
---

## Table of Content

- [Project Description](#Project-Description)
- [Objective](#Objective)
- [Dataset Description](#Dataset-Description)

## Project Description
---
Gemstone co ltd, which is a manufacturer of cubic zirconia, relies on this analysis to predict the price of the gemstone based on the details provided in the `Metadata` dataset so that it can distinguish between the most profitable gemstones and the least profitable gemstones to have a better share of the profits.
This dataset contains the price and other attributes of nearly 27,000 cubic zirconias (a cheap diamond alternative with many qualities identical to a diamond). The company makes different profits on different slots.
## Objective
This project aims to perform exploratory data analysis (EDA), data wrangling, and building a regression model to predict gemstone prices based on features such as carat, cut, color, and clarity.
## Dataset Description
The dataset contains data about cubic zirconia gemstone, including various features that influence its price. The task is explore, clean, and analyze the data, draw meaningful insights, and create predictive models.
## Dataset Explanation
### **Metadata**
1.  Carat : 	 Carat weight of the cubic zirconia.
2. Cut :	 Describe the cut quality of the cubic zirconia. Quality is increasing order:
    *  2.1 Fair
    *  2.2 Good
    *  2.3 Very Good
    *  2.4 Premium
    *  2.5 Ideal
3. Color :  	 Color of the cubic zirconia with D being the best and J the worst.
4. Clarity :	 cubic zirconia Clarity refers to the absence of the Inclusions and Blemishes. from Best to Worst:
    * FL: Flawless
    * IF: Internally Flawless
    * VVS1: Very, Very Slightly Included 1
    * VVS2: Very, Very Slightly Included 2
    * VS1: Very Slightly Included 1
    * VS2: Very Slightly Included 2
    * SI1: Slightly Included 1
    * SI2: Slightly Included 2
    * I1: Included 1
    * I2: Included 2
    * I3: Included 3
5. Depth : The Height of a cubic zirconia, measured from the Culet to the table, divided by its average Girdle Diameter.
6. Table : The Width of the cubic zirconia's Table expressed as a Percentage of its Average Diameter.
7. Price : The Price of the cubic zirconia.
8. Lenght(mm) :	Length of the cubic zirconia in mm.
9. Width(mm) :	Width of the cubic zirconia in mm.
10. Height(mm) : Height of the cubic zirconia in mm.


## Notebook prepration
**1- Import libraries and dataset**
## Tasks

1.	Data Cleaning:
- Handle missing values.
- Remove duplicate entries.
- Correct inconsistencies in the data.
- Detect and handle outliers.

2.	Exploratory Data Analysis (EDA):
- Generate summary statistics for the dataset.
- Visualize the distribution of each feature.
- Explore relationships between features using scatter plots, correlation matrices, etc.
- Identify any patterns or trends in the data.

3.	Data Wrangling:
- Normalize or standardize numerical features if necessary.
- Encode categorical variables.
- Create new features if beneficial for the analysis.

4.	Insights and Conclusions:
- Draw meaningful insights from the data.
- Summarize critical findings.
- Provide recommendations based on the analysis.

5.	Building a Regression Model:
- Use the cleaned and preprocessed dataset to build a regression model predicting gemstone prices.
- Split the dataset into training and testing sets.
- Train the model and evaluate its performance using:
  - Root Mean Squared Error (RMSE)
  - Mean Absolute Error (MAE)
  - R² score
- Explore how model performance changes with different features or transformations.
- Summarize findings and assess the model's effectiveness in predicting gemstone prices.

🙂

💻
|Heading1|Heading2|
|--------|--------|
|Content|Content2|
|Python|SQL|

`column_1`
