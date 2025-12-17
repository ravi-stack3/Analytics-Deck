 Google Trends Analytics Project

This project analyzes how a keyword is searched on Google across countries and over time. The goal is to create a reusable Python workflow where only the keyword changes and all analyses and visualizations update automatically.

 1. Dynamic keyword-based search

- The code is written so that a single variable (for example, keyword = "Python programming") controls the entire analysis.  
- By changing this keyword, the script fetches fresh Google Trends data, updates tables, and regenerates all plots without modifying any other part of the code.

 2. Top 15 countries analysis

- The project extracts the list of countries where the selected keyword is searched the most.  
- It identifies the top 15 countries by search interest and visualizes them using bar charts or similar plots to compare their relative popularity.

 3. World map visualization

- A world map is created to show how strongly each country searches for the keyword.  
- Countries are colored or shaded according to their search interest score, allowing a quick global comparison of keyword popularity.

 4. Time-wise interest and trend

- The script pulls time-series data for the keyword, showing how its search interest changes over days, months, or years.  
- A line plot visualizes these trends, helping to understand seasonality, spikes in interest, and long-term growth or decline.

 5. Related keywords comparison

- The project retrieves a set of related or similar keywords suggested by Google Trends.  
- These related keywords are compared on a single graph, allowing side‑by‑side visualization of their search interest over time.

 6. Tech stack and libraries

- Programming language: Python.  
- Typical libraries: pytrends (Google Trends API wrapper), pandas, matplotlib / seaborn, and a mapping library (such as plotly or geopandas) for the world map.

 7. How to use

- Clone this repository and install the required packages from requirements.txt.  
- Open the main notebook or script (for example, google_trends_analysis.ipynb or main.py).  
- Change the keyword variable to any term of interest.  
- Run all cells / execute the script to generate updated tables and visualizations
