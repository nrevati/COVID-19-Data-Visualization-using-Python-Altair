# COVID-19-Data-Visualization-using-Python-Altair
This project utilizes Python's Altair library to create interactive visualizations of COVID-19 data, providing insights into confirmed cases, fatalities, and regional trends across the U.S. at both state and county levels.

Project Overview:

The goal of this project is to develop visualizations using the Altair library in Python. The project involves analyzing COVID-19 data across different states in the US, creating a series of visualizations that include bar charts, interactive visualizations, and choropleth maps, allowing for deeper insights into COVID-19 confirmed cases, deaths, and fatality rates at the county level.

Tools Used:

1. Python (Jupyter Notebook)
2. Altair (Visualization Library)
3. Pandas (Data Handling)
4. Anaconda (Development Environment)
5. Vega-Lite (Interaction Grammar via Altair)

   
Steps:

Data Loading and Preprocessing:

1. CSV file loaded with COVID-19 cases data using Pandas.
2. Subsetting and cleaning data to focus on relevant columns (e.g., confirmed cases, deaths).

Bar Chart Visualization:

1. Top 10 US states by confirmed cases were visualized using a bar chart.
2. Grouping by state names and displaying the sum of confirmed cases.

Interactive Visualization:

1. A scatter plot comparing confirmed cases and deaths for the top 5 states.
2. Added interactive elements (drop-down menu for state selection and zoom functionality).

Choropleth Map:

1. Created a geographical map visualizing fatality rates at the county level using a choropleth map.
2. Joined COVID-19 data with inbuilt Altair datasets using FIPS codes for geographical mapping.

Insights: 

1. Top 5 States: New York, California, Florida, Texas, and New Jersey were the most affected states in terms of confirmed cases, but they also varied in terms of fatalities, with New York having a particularly high fatality rate early in the pandemic.

2. Interactivity Matters: The interactive comparison between confirmed cases and deaths allowed us to see that the virus didn’t affect every state equally. Some states managed to keep fatalities lower despite high case counts, showing that policies and healthcare resources played a crucial role.

3. County-Level Inequities: The choropleth map highlighted how counties with fewer resources—often in rural areas—suffered disproportionately in terms of fatality rates, showcasing systemic healthcare disparities.

4. Humanizing the Data: By breaking down the numbers into visualizations, the data became more than just statistics. Each data point represented lives affected, providing policymakers with the context they needed to allocate resources more effectively.
