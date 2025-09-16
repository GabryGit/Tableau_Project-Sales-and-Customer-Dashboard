# Tableau Project: Sales Performance and Customer Analytics Dashboards

You can find the dashboards published on my Tableau Public profile: 

- [[Sales Dashboard Link]](https://public.tableau.com/views/Sales_Dashboard_Project_17510126295020/SalesDash?:language=it-IT&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)
  
- [[Customer Dashboard Link]](https://public.tableau.com/app/profile/gabriele.casarin/viz/Customer_Dashboard_Project/CustomerDash)


### Table of Contents

- [Project Overview](#project-overview)
- [Data Sources](#data-sources)
- [Tools](#tools)
- [Techniques Used](#techniques-used)
- [Data Cleaning and Preparation](#data-cleaning-and-Preparation)
- [Analysis Results ](#analysis-results)
- [Links and Sources](#links-and-sources)


### Project Overview

**Sales Dashboard**
This dashboard offers a high-level overview of sales metrics and trends. Its primary purpose is to help stakeholders analyze year-over-year sales performance, identify key trends, and pinpoint areas for improvement. The visualizations are designed to present complex data in an intuitive format, allowing users to quickly spot patterns and understand the factors driving sales.

**Customer Dashboard**
The customer dashboard is focused on providing deeper insights into customer data, trends, and behaviors. It's a key tool for marketing teams and management, helping them to understand customer segments and develop strategies to improve customer satisfaction and loyalty. By visualizing customer journeys and preferences, the dashboard enables teams to tailor their efforts and enhance the overall customer experience.


### Data Sources

[[here]](https://github.com/GabryGit/Tableau_Project-Sales-and-Customer-Dashboard/tree/main/Dataset) you find the datasets used for this project. We used the below Data model Schema inside Tabelau to create the dashboards:

![DataModel-Schema](https://github.com/GabryGit/Tableau_Project-Sales-and-Customer-Dashboard/blob/main/Charts/Datamodel-Schema.png)


### Tools

- Excel - Data Cleaning (with Power Query)
- Tableau - Data Visualisation


### Techniques Used

- Tableau Data Modeling
- Filters
- Parameters
- Calculated Fields
- Actions

  
### Data Cleaning and Preparation

The original dataset was cleaned, and two separate datasets were created. The first, titled "World Happiness Report," contains all the features from the report, organized by year. The second, "Countries & Continents," maps each country to its corresponding continent, which enables analysis to be segmented by continent.

After importing into Tableau, the two datasets were connected using data blending.

You find the datasest ready to be imported in Tableau [[here]](https://github.com/GabryGit/Tableau_Project-World-Happiness-Report/tree/main/Dataset/Data%20Cleaned)


### Analysis Results 

The project features a suite of interactive visualizations:

- *Interactive Controls*: Users can filter the data by geographical region and year.
  
![controls.png](https://github.com/GabryGit/Tableau_Project-World-Happiness-Report/blob/main/Dashboard%20details/Controls.png)

- *Choropleth Map and Ranked Table*: A color-coded map displays the happiness scores of nations, with detailed tooltips revealing the values of the contributing factors for each country.
                                 Below the map, a table highlights the top and bottom 10 countries in terms of happiness.
  
![Cloropleth_map.png](https://github.com/GabryGit/Tableau_Project-World-Happiness-Report/blob/main/Dashboard%20details/Cloropleth_map.png)

- *Trend Analysis*: A bar chart illustrates the happiness score trend over the five-year period, allowing users to identify countries with significant improvements or declines.
  
![Trend.png](https://github.com/GabryGit/Tableau_Project-World-Happiness-Report/blob/main/Dashboard%20details/Trend.png)

- *Distribution Analysis*: A box plot visualizes the distribution of happiness scores, showing the median, quartiles, and any outliers.
  
![Distribution.png](https://github.com/GabryGit/Tableau_Project-World-Happiness-Report/blob/main/Dashboard%20details/Distribution.png)

- *Categorization*: A pie chart categorizes countries into three happiness levels, based on the dataset's median score.
  
![Donut.png](https://github.com/GabryGit/Tableau_Project-World-Happiness-Report/blob/main/Dashboard%20details/Donut.png)


This dashboard offers a clear and intuitive way to explore complex data, providing actionable insights for policymakers and anyone interested in understanding the dynamics of global well-being.


### Links and Sources

[[Tableau Public Dashboard Link]](https://public.tableau.com/app/profile/gabriele.casarin/viz/WorldHappinessReport_17508864371150/Dashboard1)

[[Data Analytics Master-Start2Impact University]](https://www.start2impact.it/master/data-science-analytics/)
