<h1 align="center"> COVID-19 DATA ANALYSIS & DASHBOARD SYSTEM </h1>

<h2>PROJECT OVERVIEW</h2>

The COVID-19 Data Analysis & Dashboard System is a data analytics project that analyzes global COVID-19 statistics using a country-wise dataset. The dataset contains important pandemic indicators such as confirmed cases, deaths, recoveries, and active cases.

The goal of this project is to perform Exploratory Data Analysis (EDA) to understand pandemic trends, identify high-risk countries, and visualize relationships between different COVID-19 variables.

The project also includes an interactive dashboard that allows users to explore country-wise COVID-19 statistics dynamically using graphs and visualizations.

<hr>

<h2>PROBLEM STATEMENT</h2>

The COVID-19 pandemic generated massive amounts of global health data across countries. Governments, healthcare organizations, and research institutions continuously publish statistics related to confirmed cases, deaths, recoveries, and active cases.

However, analyzing such large datasets manually is difficult and time-consuming. Therefore, an automated system is required to clean, analyze, and visualize COVID-19 data efficiently to better understand pandemic trends and patterns.

<hr>

<h2>DATASET DESCRIPTION</h2>

The dataset contains country-wise COVID-19 statistics with the following columns:

<b><i>

| COLUMN    | DESCRIPTION                         |
|----------|-------------------------------------|
| Country  | Name of the country                 |
| Confirmed| Total confirmed COVID-19 cases      |
| Deaths   | Total number of deaths              |
| Recovered| Total recovered COVID-19 cases      |
| Active   | Currently active COVID-19 cases     |

</i></b>

<hr>

<h2>PROJECT OBJECTIVES</h2>

The main objectives of this project are:

<ul>

<li>Load and analyze the COVID-19 dataset</li>
<li>Perform data cleaning and preprocessing</li>
<li>Check missing values and remove duplicates</li>
<li>Perform statistical analysis</li>
<li>Identify high-risk countries</li>
<li>Analyze relationships between pandemic variables</li>
<li>Perform correlation analysis</li>
<li>Visualize data using charts and graphs</li>
<li>Develop an interactive dashboard</li>
<li>Generate insights from COVID-19 data</li>

</ul>

<hr>

<h2>DATA CLEANING STEPS</h2>

The following data cleaning operations were performed:

<ul>

<li>Selected required columns from the dataset</li>
<li>Renamed columns for better readability</li>
<li>Checked missing values using <b>isnull()</b></li>
<li>Removed duplicate records</li>
<li>Verified dataset structure using <b>info()</b></li>
<li>Generated statistical summary using <b>describe()</b></li>

</ul>

<hr>

<h2>COUNTRY RISK ANALYSIS</h2>

Countries are categorized based on the number of confirmed cases.

<b><i>

| RISK LEVEL | CONDITION                                   |
|-----------|-----------------------------------------------|
| High Risk | Countries with very high confirmed cases      |
| Medium Risk | Countries with moderate confirmed cases     |
| Low Risk  | Countries with fewer confirmed cases          |

</i></b>

<hr>

<h2>DATA ANALYSIS PERFORMED</h2>

The following analyses were conducted:

<ul>

<h5>Descriptive Statistics</h5>
<li>Mean</li>
<li>Median</li>
<li>Minimum</li>
<li>Maximum</li>
<li>Standard Deviation</li>

<h5>Global Case Analysis</h5>
<li>Total confirmed cases</li>
<li>Total deaths</li>
<li>Total recovered cases</li>
<li>Total active cases</li>

<h5>Country-Based Analysis</h5>
<li>Top countries by confirmed cases</li>
<li>Countries with highest deaths</li>
<li>Countries with highest recoveries</li>

<h5>Relationship Analysis</h5>
<li>Confirmed vs deaths</li>
<li>Confirmed vs recovered</li>
<li>Confirmed vs active</li>

<h5>Correlation Analysis</h5>
<li>Correlation heatmap between variables</li>

</ul>

<hr>

<h2>DATA VISUALIZATION</h2>

The project includes several visualizations:

<b><i>

| CHART | PURPOSE | GRAPH UNDERSTANDING / KEY POINTS |
|------|---------|----------------------------------|
| Bar Chart | Top countries by confirmed cases | Identifies high-risk countries |
| Pie Chart | Global case distribution | Displays percentage of cases |
| Scatter Plot | Confirmed vs deaths | Shows infection-death relationship |
| Scatter Plot | Confirmed vs recovered | Shows recovery patterns |
| Heatmap | Correlation matrix | Shows relationships between variables |

</i></b>

<hr>

<h2>BAR CHART</h2>



<hr>

<h2>PIE CHART</h2>

Image

<hr>

<h2>SCATTER PLOT</h2>

Image

<hr>

<h2>HEATMAP</h2>

Image

<hr>

<h2>DASHBOARD</h2>

Image

<hr>

<h2>TECHNOLOGIES USED</h2>

<ul>

<li>Python</li>
<li>Pandas</li>
<li>NumPy</li>
<li>Matplotlib</li>
<li>Seaborn</li>
<li>Plotly</li>
<li>Dash / JupyterDash</li>
<li>Google Colab</li>

</ul>

<hr>

<h2>EXPECTED OUTCOME</h2>

The analysis helps to:

<ul>

<li>Understand global COVID-19 trends</li>
<li>Identify high-risk countries</li>
<li>Study relationships between pandemic variables</li>
<li>Improve data interpretation using visualization</li>
<li>Support data-driven insights and decision making</li>

</ul>

<hr>

<h2>CONCLUSION</h2>

This project demonstrates how pandemic data can be analyzed using Python and data science techniques. By applying data cleaning, statistical analysis, visualization, and dashboard development, meaningful insights can be obtained from COVID-19 datasets.

The interactive dashboard further enhances the system by allowing users to explore country-wise COVID-19 statistics easily.

This project highlights the importance of data analytics in understanding global health crises and supporting informed decision-making.

<hr>
