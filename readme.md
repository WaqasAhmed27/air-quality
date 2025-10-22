# Interactive Air Quality Data visualizer

This project is an interactive jupyter notebook for analyzing and visualizing air quality data (PM2.5 levels) from indian cities
between 2015 and 2020.

## Features
**Data cleaning:** Handles the missing PM2.5 values using forward-fill
**Overall Distribution:** A boxplot is used to show overall PM2.5 distribution for cities
**Seasonal Analysis:** A heatmap visualizes the average PM2.5 levels by month and year, revealing strong seasonal patterns

## Technologies used
* Python
* Jupyter Notebook
* Pandas (for data manipulation)
* Plotly (for interactive visualizations)
* ipywidgets (for interactive dropdown)

## Data Source
* **Dataset:** Air Quality Data in India (2015 - 2020)
* **Source:** [kaggle](https://www.kaggle.com/datasets/rohanrao/air-quality-data-in-india)
* **File:** 'city_day.csv'

## How to Run
1. Clone this repository:
    ```bash
    git clone []()
    cd air-quality
    ```

2. Install the required libraries:
    ```bash
    pip install pandas plotly ipywidgets
    ```

3. Ensure the 'city_day.csv' file is in the same directory as the notebook

4. Open and run the notebook in Jupyter Notebook or VS code, etc
