# Diamond Price Analysis and Prediction

This R script performs analysis and prediction of diamond prices using linear regression models. It includes data exploration, visualization, model building, evaluation, and prediction.

## Overview

The script performs the following tasks:

1. **Data Exploration:** Loads the diamonds dataset from the `tidyverse` package, explores data distributions, and examines relationships between variables.

2. **Data Visualization:** Visualizes relationships between diamond attributes (carat, cut, color, clarity) and price using scatter plots, box plots, histograms, and other visualization techniques.

3. **Linear Regression Modeling:** Builds linear regression models to predict diamond prices based on various features, including carat, cut, depth, and table.

4. **Model Evaluation:** Evaluates the performance of the regression models using metrics such as mean absolute error (MAE) and root mean squared error (RMSE).

5. **Prediction:** Makes predictions on new data using the trained regression models and visualizes the predicted vs. actual diamond prices.

## Libraries Used

The script utilizes the following R packages:

- `tidyverse`: For data manipulation and visualization.
- `skimr`: For summary statistics and visualization of data distributions.
- `plot3D`: For 3D scatter plots.
- `QuantPsyc`: For calculating beta coefficients in linear regression models.
- `yarrr`: For generating box plots and scatter plots.

## Usage

To use the script:

1. Install the required packages by running the following commands in R:

   ```r
   install.packages("tidyverse")
   install.packages("skimr")
   install.packages("plot3D")
   install.packages("QuantPsyc")
   install.packages("yarrr")
 
