# Heart Disease and Stroke Prevention

## Overview
This project focuses on analyzing a heart disease and stroke prevention dataset to predict and detect the presence of heart disease and associated risk factors using machine-learning techniques. The dataset is sourced from the National Cardiovascular Disease Surveillance System and is available on Kaggle. It provides a comprehensive picture of the public health burden of cardiovascular diseases (CVDs) and associated risk factors in the United States.

## Problem Definition
The primary objective is to study the heart disease dataset and develop models to predict and detect the presence of heart disease and associated risk factors. This will help in understanding the key indicators and contributing factors to CVDs, ultimately aiding in prevention and early detection.

## Dataset Information
The dataset includes over 85,800 records and 29 attributes, organized by location (national, regional, state, and selected sites) and indicators related to CVDs and risk factors.

- **Source:** [Kaggle - Heart Disease and Stroke Prevention](https://www.kaggle.com/mazharkarimi/heart-disease-and-stroke-prevention)
- **Attributes:**
  - Year
  - LocationAbbr: Location abbreviation
  - LocationDesc: Location description
  - DataSource: Abbreviation of data source
  - PriorityArea1: Priority Area (Million Hearts® or None)
  - PriorityArea2: Priority Area (ABCS or None)
  - PriorityArea3: Priority Area (Healthy People 2020 or None)
  - PriorityArea4: Priority Area (AHA 2020 Goals: Cardiovascular Health Metrics or None)
  - Category: Category description
  - Topic: Topic description
  - Indicator: Indicator description
  - Data_Value_Type: Data Value Type (mean, rate, percentage)
  - Data_Value_Unit: Data Value Unit (%, rate per 100,000, etc.)
  - Data_Value: Data value (point estimate)
  - Data_Value_Alt: Equal to data value, but formatting is numeric
  - Data_Value_Footnote_Symbol: Symbol used to flag footnotes
  - Data_Value_Footnote: Footnote description
  - Confidence_Limit_Low: 95% confidence interval lower bound
  - Confidence_Limit_High: 95% confidence interval upper bound
  - Break_Out_Category: Break out category description
  - Break_Out: Break out group description
  - CategoryId: Category lookup value
  - TopicId: Topic lookup value
  - IndicatorID: Indicator lookup value
  - Data_Value_TypeID: Data value type lookup value
  - BreakOutCategoryId: Break out category lookup value
  - BreakOutId: Break out group lookup value
  - LocationID: Location lookup value
  - GeoLocation

## Project Workflow
1. **Data Loading:** Load the dataset into a pandas DataFrame.
2. **Exploratory Data Analysis (EDA):** 
   - Analyze the structure and distribution of the data.
   - Check for missing values and handle them appropriately.
3. **Text Preprocessing:** 
   - Clean and preprocess the data.
4. **Feature Extraction:** Extract meaningful features for model building.
5. **Model Development:** Build machine learning models to predict heart disease and stroke risks.
   - Evaluate models using appropriate metrics.
6. **Evaluation:** Assess model performance and refine as needed.
7. **Deployment:** Develop a system to automate predictions for new data.

