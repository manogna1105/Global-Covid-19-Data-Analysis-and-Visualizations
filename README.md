# Covid-19 Analysis and Visualization using Plotly Express
In this article, we will discuss Analyse Covid-19 data and will visualize it using Plotly Express in Python. This article deals with creating dozens of bar charts, line graphs, bubble charts, scatter plots. The graph that will be made in this project will be of excellent quality. Envisioning COVID-19 will primarily be using Plotly Express for this project. The analysis and visualization enable people to understand complex scenarios and make predictions about the future from the current situation.

This analysis summarizes the modeling, simulation, and analytics work around the COVID-19 outbreak around the world from the perspective of data science and visual analytics. It examines the impact of best practices and preventive measures in various sectors and enables outbreaks to be managed with available health resources.

Tools and Technologies Used in the Project: Google Colab(Runtime type – GPU).

Requirements to Build the Project: 

* Basic knowledge of Python
  
* Basic understanding of graphs and charts
  
* Data visualization
  
* Pandas
  
* Numpy
  
* Matplotlib
  
* Plotly Express
  
* Choropleth
  
* Wordcloud

 # Stepwise Implementation
 
 **Step 1: Importing Necessary Libraries**

The task is simple, once the installation of all the required libraries is successful, they need to be imported to the working space, since they will provide the additional support for analysis and visualization.

 **Step 2: Importing the Datasets**
 
-> Importing three datasets into this project

* **covid–** This dataset contains Country/Region, Continent,  Population, TotalCases, NewCases, TotalDeaths, NewDeaths,  TotalRecovered, NewRecovered, ActiveCases, Serious, Critical, Tot Cases/1M pop, Deaths/1M pop, TotalTests, Tests/1M pop, WHO Region, iso_alpha.
  
* **covid_grouped–** This dataset contains Date(from 20-01-22 to 20-07-27), Country/Region, Confirmed, Deaths, Recovered, Active, New cases, New deaths, New recovered, WHO Region, iso_alpha.
  
* **coviddeath–** This dataset contains real-world examples of a number of Covid-19 deaths and the reasons behind the deaths.

->To import datasets to the working space pandas read_csv() method can be used.

Syntax:
read_csv(path)

**Step 3: Dataset cleaning**

-> Data cleaning is the process of altering, modifying a recordset, correcting erroneous records from the database and identifying incomplete, incorrect, or irrelevant parts of the data, and then removing dirty data.

**Step 4: Bar graphs- Comparisons between COVID infected countries in terms of total cases, total deaths, total recovered & total tests**

-> Using one line of code, we will create amazing graphs using Plotly Express. Visualization can be done easily by moving the cursor in any plot, we can get label presence point directly by using the cursor. 
We can visualize and analyze the dataset with each aspect using the relation between the columns.

**Step 5: Data Visualization through Bubble Charts-Continent Wise**

-> Let’s create a scatter plot and take a look at the continent’s statistics, firstly look at the total number of cases by continent and take hover data as ‘Country/Region’, ‘Continent’.

**Step 6: Data Visualization through Bubble Charts-Country Wise**

-> Let’s take a look at the country-wise data visualization, first look at the continent with respect to the total number of deaths by the top 50 countries only and color the total number of deaths and take the hover data as ‘Country/Region’, ‘Continent’.

**Step 7: Advanced Data Visualization- Bar graphs for All top infected Countries**

-> In this task, we will explore covid-19 data using bar graphs and charts and use dataset2 as it has date column.

**Step 8: Countries Specific COVID Data Visualization: (United States)**

-> In this specific task, we will analyze data of the USA country.

Example: Refining dataset to get only USA data

**Step 9: Visualization of Data in terms of Maps**

-> We can use choropleth to visualize the data in terms of maps, with maps usually being the predominant way of visualizing the data. Since COVID-19 is a global phenomenon and so we look through and fix them in terms of wall maps. Ortho-graphics, rectangular and natural earth projection to visualize the data With dataset2 for the purpose as it has Dates column. It will look at the growth of Covid-19 (from Jan to July 2020) as in how the virus reached across the world.

Choropleth is an amazing representation of data on a map. Choropleth maps provide an easy way to visualize how a measurement varies across a geographic areal-Life

Project Application in Real choropleth map displays divided geographical areas or regions that are colored, shaded or patterned in relation to a data variable.

**Step 10: Visualize text using Word Cloud**

-> Visualize the causes of death due to covid-19, as covid-19 affects people in different ways, hence creating a word cloud to visualize the leading cause of covid-19 deaths. 

To visualize the text the steps need to be followed are-

* Used to convert data elements of an array into list.

* Convert the string to one single string.
  
* Convert the string into word cloud

**Dataset3:** This dataset contains real world examples of number of Covid-19 deaths and the reasons behind the deaths.
