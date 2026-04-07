<b><h1 align="center">COVID-19 DATA ANALYSIS & DASHBOARD SYSTEM (KAGGLE DATASET)</h1>

<hr>

<h2>PROJECT OVERVIEW</h2>

<p>
The <b>COVID-19 Data Analysis & Dashboard System</b> is a data analytics project that studies the global spread of COVID-19 using a real-world dataset obtained from Kaggle.
</p>

<p>
This project analyzes important pandemic indicators such as <b>confirmed cases, deaths, recoveries, and active cases</b> across different countries. Using <b>Exploratory Data Analysis (EDA)</b>, the system identifies trends, patterns, and relationships within the dataset.
</p>

<p>
An <b>interactive dashboard</b> is also developed using <b>Plotly Dash</b> to visualize COVID-19 statistics and allow users to explore country-wise data dynamically.
</p>

<hr>

<h2>PROBLEM STATEMENT</h2>

<p>
The COVID-19 pandemic generated massive volumes of global health data including confirmed cases, deaths, recoveries, and active cases.
</p>

<p>
Organizations such as the <b>World Health Organization (WHO)</b> and research institutions like <b>Johns Hopkins University</b> regularly publish pandemic datasets. However, manually analyzing such large datasets is complex and time-consuming.
</p>

<p>
Therefore, there is a need for an automated system that can analyze pandemic data efficiently and provide meaningful insights through visualizations and dashboards.
</p>

<hr>

<h2>DATASET DESCRIPTION</h2>

<table border="1" cellpadding="8" cellspacing="0">
<tr>
<th>COLUMN NAME</th>
<th>DESCRIPTION</th>
</tr>

<tr>
<td>Country/Region</td>
<td>Name of the country</td>
</tr>

<tr>
<td>Confirmed</td>
<td>Total confirmed COVID-19 cases</td>
</tr>

<tr>
<td>Deaths</td>
<td>Total number of deaths</td>
</tr>

<tr>
<td>Recovered</td>
<td>Total recovered cases</td>
</tr>

<tr>
<td>Active</td>
<td>Current active cases</td>
</tr>

</table>

<br>

<b>Dataset Source:</b> Kaggle <br>
<b>Dataset Link:</b> https://www.kaggle.com/datasets/imdevskp/corona-virus-report

<hr>

<h2>PROJECT OBJECTIVES</h2>

<ul>

<li>Load and analyze the COVID-19 dataset</li>
<li>Perform data cleaning and preprocessing</li>
<li>Check missing values and remove duplicate records</li>
<li>Calculate descriptive statistics</li>
<li>Analyze country-wise COVID-19 cases</li>
<li>Identify the most affected countries</li>
<li>Study relationships between confirmed, deaths, recovered, and active cases</li>
<li>Visualize data using charts and graphs</li>
<li>Build an interactive dashboard using Plotly Dash</li>
<li>Generate insights from data visualization</li>

</ul>

<hr>

<h2>DATA CLEANING STEPS</h2>

<ul>

<li>Selected only required columns from the dataset</li>
<li>Removed duplicate records</li>
<li>Checked missing values using <b>isnull()</b></li>
<li>Converted numerical columns into proper data types</li>
<li>Verified dataset consistency</li>

</ul>

<hr>

<h2>DATA ANALYSIS PERFORMED</h2>

<h4>Country Based Analysis</h4>

<ul>
<li>Top 10 countries with highest confirmed cases</li>
<li>Country-wise comparison of deaths</li>
</ul>

<h4>Relationship Analysis</h4>

<ul>
<li>Confirmed vs Deaths</li>
<li>Confirmed vs Recovered</li>
<li>Confirmed vs Active</li>
</ul>

<h4>Correlation Analysis</h4>

<ul>
<li>Correlation matrix between numerical variables</li>
</ul>

<h4>Dashboard Analysis</h4>

<ul>
<li>Interactive country dropdown selection</li>
<li>Dynamic charts updating based on selected country</li>
</ul>

<hr>

<h2>DATA VISUALIZATION</h2>

<table border="1" cellpadding="8" cellspacing="0">

<tr>
<th>CHART</th>
<th>PURPOSE</th>
<th>GRAPH UNDERSTANDING</th>
</tr>

<tr>
<td>Bar Chart</td>
<td>Top affected countries</td>
<td>Shows countries with highest confirmed cases</td>
</tr>

<tr>
<td>Pie Chart</td>
<td>Case distribution</td>
<td>Displays percentage of confirmed, deaths, recovered, and active cases</td>
</tr>

<tr>
<td>Scatter Plot</td>
<td>Confirmed vs Deaths</td>
<td>Shows relationship between cases and fatalities</td>
</tr>

<tr>
<td>Scatter Plot</td>
<td>Confirmed vs Recovered</td>
<td>Shows recovery trends</td>
</tr>

<tr>
<td>Scatter Plot</td>
<td>Confirmed vs Active</td>
<td>Indicates current pandemic severity</td>
</tr>

<tr>
<td>Heatmap</td>
<td>Correlation analysis</td>
<td>Shows relationships between variables</td>
</tr>

<tr>
<td>Line Chart</td>
<td>Trend analysis</td>
<td>Displays case growth patterns</td>
</tr>

</table>

<hr>

<h2>BAR CHART – TOP AFFECTED COUNTRIES</h2>

<!-- INSERT BAR CHART IMAGE HERE -->

<img width="811" height="391" alt="image" src="https://github.com/user-attachments/assets/cc36b7b2-6c97-4891-a772-7306b4e974c6" />


<hr>

<h2>BAR CHART – DEATHS</h2>

<img width="809" height="392" alt="image" src="https://github.com/user-attachments/assets/56cf6ac3-80ab-45bd-9018-42585ecec324" />

<hr>

<h2>PIE CHART – CASE DISTRIBUTION</h2>

<!-- INSERT PIE CHART IMAGE HERE -->
<img width="808" height="389" alt="image" src="https://github.com/user-attachments/assets/417ac0a9-1d8c-433b-82b2-039fe7ee2311" />


<hr>

<h2>SCATTER PLOT – CONFIRMED VS DEATHS</h2>

<!-- INSERT SCATTER PLOT IMAGE HERE -->

<img width="810" height="395" alt="image" src="https://github.com/user-attachments/assets/b59b601b-8633-45f7-8669-deb6b69317c9" />


<hr>

<h2>SCATTER PLOT – CONFIRMED VS RECOVERED</h2>

<!-- INSERT SCATTER PLOT IMAGE HERE -->

<img width="808" height="385" alt="image" src="https://github.com/user-attachments/assets/8baa145e-fe73-489f-856c-0cd27fc8a07b" />

<hr>

<h2>SCATTER PLOT – CONFIRMED VS ACTIVE</h2>

<!-- INSERT SCATTER PLOT IMAGE HERE -->

<img width="805" height="394" alt="image" src="https://github.com/user-attachments/assets/af909358-2995-4567-ab46-f711f37290b3" />

<hr>

<h2>HEATMAP – CORRELATION MATRIX</h2>

<!-- INSERT HEATMAP IMAGE HERE -->

<img width="812" height="390" alt="image" src="https://github.com/user-attachments/assets/53e0cb71-bf5c-4d6b-bca5-0e0ad497be2d" />

<hr>

<h2>DASHBOARD INTERFACE</h2>

<!-- INSERT DASHBOARD SCREENSHOT HERE -->

<img width="1745" height="384" alt="image" src="https://github.com/user-attachments/assets/8e26be86-439c-4c71-b200-4f44e29f00f9" />

<hr>

<img width="1738" height="405" alt="image" src="https://github.com/user-attachments/assets/f9e8f3fb-6ff0-4831-a91a-84b7ee921fb2" />

<hr>

<img width="1743" height="360" alt="image" src="https://github.com/user-attachments/assets/9c26b1d0-bdb5-483b-83f6-68a62e8ca988" />

<hr>

<img width="1744" height="344" alt="image" src="https://github.com/user-attachments/assets/c88e832a-c9ad-4e48-81b4-392949f8b680" />

<hr>

<img width="1739" height="367" alt="image" src="https://github.com/user-attachments/assets/b3bfea72-6dc4-47e9-a8a3-7b7c1547a4d4" />

<hr>

<img width="1741" height="349" alt="image" src="https://github.com/user-attachments/assets/1463b88c-d9ff-4aee-af25-48966798915c" />

<hr>

<h2>TECHNOLOGIES USED</h2>

<ul>

<li>Python</li>
<li>Pandas</li>
<li>NumPy</li>
<li>Matplotlib</li>
<li>Seaborn</li>
<li>Plotly</li>
<li>Dash</li>
<li>Jupyter Notebook / Google Colab</li>

</ul>

<hr>

<h2>EXPECTED OUTCOME</h2>

<ul>

<li>Understand global COVID-19 trends</li>
<li>Identify countries with high infection rates</li>
<li>Analyze relationships between pandemic variables</li>
<li>Visualize data clearly using graphs</li>
<li>Support data-driven insights and decision making</li>

</ul>

<hr>

<h2>CONCLUSION</h2>

<p>
This project demonstrates how pandemic data can be analyzed using <b>Python</b> and modern <b>data visualization techniques</b>.
</p>

<p>
By applying <b>Exploratory Data Analysis (EDA)</b> and building an <b>interactive dashboard</b>, the system converts raw COVID-19 data into meaningful insights that help understand pandemic trends and patterns.
</p>

<hr> </b>
