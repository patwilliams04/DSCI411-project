# DSCI441 Project- Unemployment Rate Forecasting 

## Summary
This project focuses on the prediction and interpretation of economic health indicators, with a particular interest in unemployment rates. An extensive dataset including data scraped and aggregated from Macrotrends.net is used, including market indices, prices of precious metals, and various commodities that capture energy market dynamics and inflationary trends. Exchange and interest rates are also incorporated to reflect international economic strength and policy impact. The project aims to utilize machine learning methods like non-linear regression and neural networks to model and forecast economic indicators such as unemployment, aiming to reveal the complex interrelations within the data.

## Methodology
- **Data Collection**: Aggregated a robust dataset from Macrotrends.net, covering several economic aspects... may still want to re/oversample this data for more observations
- **Data Preprocessing**: Conducted initial cleaning, ensuring consistency in frequency and addressing any missing values... removed outliers and performed standard scaler
- **Exploratory Data Analysis (EDA)**: Performed a preliminary analysis to understand distributions and identify patterns
- **Feature Engineering**: To improve predictive capabilities,I plan to engineer some additional features that capture economic cycles and trends effectively (ratios, interaction terms, etc)
- **Model Development**: Built and trained many non-linear regression models to analyze the relationships within the data.
- **Model Evaluation**: Testing to assess the accuracy and reliability of the predictive models.
- **Interpretation of Results**: We aim to provide clear interpretations of the model outcomes, translating such complex relationships into understandable insights.

## Project Replication
- **BEFORE RUNNING EACH FILE**: Must change the directory to your specific machines filepath directory
- Clone this repo to your machine.
- Delete any csv files that were created by code in this repo; ie csv files named with 'economic_data' or 'final' in the name
- Run dataGathering.ipynb, should create economic_data.csv
- Run EDA.ipynb, should create final_df.csv
- Run PreProcessing.ipynb, should createe final_economic_data.csv
- Run toyModeling.ipynb to get final model performances and evaluation metric visualizations   

## Data Source
The data for this project was sourced from [Macrotrends](https://www.macrotrends.net), a websitee with historical data on global economic indicators, stock markets, commodities, and more. The dataset spans various economic metrics, all compiled with attention to historical depth and accuracy, making it a valuable resource for economic analysis and forecasting. Web scraping and data aggregation were conducted in python. 
