# ETL and Data Visualization with Python and Power BI: Videogames and World Bank

This repository contains datasets related to World Bank indicators and data about the videogame industry. The datasets are stored in different files and can be used for data cleaning and data visualization tasks.

## World Bank Indicators

The World Bank datasets include a variety of indicators related to different countries and years. These indicators cover various aspects such as population, GDP, unemployment and more. 

## Videogame Industry Data

The videogame industry datasets contain information about videogame sales, release dates, platforms, genres, and other relevant attributes. 

To perform data cleaning and analysis on the World Bank and videogame datasets, I used Python and some libraries like [Pandas](https://pandas.pydata.org/) for data manipulation and cleaning. 

To analyze and visualize these datasets [Power BI](https://powerbi.microsoft.com/) was used. Power BI provides a user-friendly interface for data exploration, visualization, and creating interactive dashboards. Power BI can be used for data cleansing but it's not recommended.

## Repository Structure

The repository is structured as follows:

- [`raw_data/`](raw_data/): Contains the datasets in CSV format.
- [`processed_data/`](processed_data/): Contains the transformed and manipulated datasets in CSV format.
- [`notebooks/`](notebooks/): Includes Python notebooks for data cleaning, analysis, and visualization tasks using Pandas, Seaborn, Numpy and Matplotlib.
- [`visualizations/`](visualizations/): Includes Power BI and Python reports for data visualization and exploration.

## Examples

Here are some examples of visualizations created using the datasets:

![Correlation between GDP and Population](https://raw.githubusercontent.com/cristhianc001/videogame-data-analysis/main/visualizations/gdp-population-scatterplot.png)  
*Visualization of World Bank indicators using Seaborn*


![Videogame Sales Analysis](power_bi_reports/videogame_sales_analysis.png)
*Image: Analysis of videogame sales using Power BI*



