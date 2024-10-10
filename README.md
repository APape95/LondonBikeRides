London Bike Rides Data Analysis
This project involves analyzing the London Bike Sharing dataset, which contains information on bike-sharing activities in London. The data is used to gain insights into bike usage patterns, weather effects, and time-based trends, among others. The project is structured to facilitate data analysis and prepare visualizations using Tableau.

Key Steps:
Data Acquisition:

Downloaded the "London Bike Sharing Dataset" from Kaggle using the Kaggle API.
Extracted the dataset using Python's zipfile module.
Data Preparation:

Loaded the dataset into a Pandas DataFrame for manipulation and analysis.
Performed data cleaning, including handling missing values and formatting date-time fields for time-based analysis.
Added new features to enrich the analysis, such as hour, day of the week, and seasonal indicators.
Exploratory Data Analysis (EDA):

Conducted initial data exploration to understand the distribution of data, key statistics, and trends.
Visualized relationships between bike usage and external factors such as temperature, humidity, and weather conditions.
Investigated time-based patterns, including daily and monthly usage trends.
Data Export for Visualization:

Prepared a final DataFrame containing cleaned and aggregated data, tailored for further visualizations in Tableau.
Exported the cleaned data to an Excel file named london_bikes_final.xlsx, with the sheet name Data.
Tableau Integration:

The exported Excel file is intended to be used in Tableau for creating interactive visualizations to present insights derived from the dataset.
Technologies Used:
Python: Data analysis and preparation using libraries like pandas, zipfile, and kaggle.
Jupyter Notebook: Code execution and documentation.
Kaggle API: Automated download of datasets.
Excel: Data export for use in Tableau.
Tableau: For creating interactive visualizations based on the analysis.
