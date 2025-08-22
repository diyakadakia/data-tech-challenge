## Generate Data Branch Tech Challenge – README
#### Overview
This project analyzes international passenger traffic data for AeroConnect to identify high- and low-demand routes, uncover seasonal and regional trends, and build a model to forecast traffic for resource allocation decisions.

The challenge required:
   1. Cleaning and preparing the dataset.
   2. Performing exploratory data analysis (EDA).
   3. Building a predictive model.
   4. Evaluating the model’s accuracy.
   5. Providing recommendations for AeroConnect’s future route planning


#### Data Cleaning
I cleaned the dataset by:
   1. Converting Year and Month_num into a proper Date column.
   2. Checking for missing or inconsistent values.
   3. Creating a Route column.
   4. Sorting the dataset chronologically for modeling.

   Cleaned data link: https://drive.google.com/file/d/17vA1u8qtmHL24LFEBr2MuxxVBUZV_oqm/view?usp=sharing

#### Process
   1. Setup: Downloaded and installed all necessary Python libraries (e.g., pandas, numpy, matplotlib, scikit-learn) to support data cleaning, visualization, and modeling.
   2. EDA: Identified the most and least trafficked routes, seasonal travel patterns, and geographical concentration of international traffic.
   3. Model: Built a regression model with a third-degree polynomial trend, monthly dummy variables, and ridge regression (α = 0.1) to capture both long-term growth and seasonality.
   4. Evaluation: Assessed accuracy using MAE, RMSE, and MAPE.
   5. Recommendations: Suggested which routes AeroConnect should expand or scale back, and how to apply forecasts for planning.

