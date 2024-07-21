London Subregion Data Analysis

This repository contains the coursework for Data Science and Big Data Analytics, focusing on the analysis of socio-economic and demographic factors impacting median house prices in various subregions across Greater London. The analysis utilizes data from the 2011 census, including records for 983 subregions.

Project Overview

Objective
The primary goal of this project is to understand the impact of various socio-economic and demographic variables on median house prices. By constructing a regression model, we aim to identify critical drivers of house prices, providing valuable insights for policymakers and city planners to design better policies.

Data Source
The dataset used in this analysis is derived from the 2011 census, containing variables such as:

Population density
Percentage of people aged between 15-64 years
Percentage of lone-parent households
Various other socio-economic and demographic factors
Analysis Steps
Loading the Data: The data is loaded from an Excel file and prepared for analysis.
Exploratory Data Analysis (EDA): Performing a correlation matrix to understand relationships between variables.
Regression Modeling: Building and evaluating a regression model to predict median house prices based on selected variables.
Result Interpretation: Interpreting the results to identify key factors influencing house prices.
Technologies and Libraries Used
R and R Markdown
Libraries: readxl, dplyr, ggplot2, broom, car, lmtest, MASS, corrplot
Usage

Clone the repository and run the R Markdown file to replicate the analysis. Ensure all necessary libraries are installed.

bash
Kodu kopyala
git clone https://github.com/yourusername/LondonSubregionDataAnalysis.git
Open the LondonSubregionDataAnalysis.Rmd file in RStudio and knit the document to generate the analysis report.

Contributing

Contributions are welcome! Please fork the repository and submit a pull request with your changes.

License

This project is licensed under the MIT License.
