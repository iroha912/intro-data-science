# Data Science Portfolio
## Final Project Ideas

### Idea 1: Gender Inequality in Engineering & Tech
This project explores gender inequality in STEM fields by analyzing data related to employment and education.
* Is the proportion of females and males similar in education compared to employment in STEM fields?
* Which engineering fields have the highest and lowest female representation?

### Idea 2: Technology Access & Social Inequality
This project explores how access to technology differs across regions and how it impacts social and economic outcomes.
* Do regions with higher technology access have better quality of life?
* Is there a relationship between technology access and income or opportunity?

### Idea 3: Urban Infrastructure & Quality of Life
This project investigates how access to infrastructure (such as parks, transportation, or public services) affects quality of life in cities.
* Do cities with better infrastructure have higher quality of life?
* Does population size influence access to infrastructure?

## Week 10 Update
I will be completing this project on my own. 

My general topic is global technology access and inequality, focusing on how internet access varies across countries and how it relates to social and economic outcomes. I am also interested in exploring a possible connection to gender inequality if relevant data is available.

For my data sources, I plan to use the World Bank API as my primary dataset, since it provides data on internet usage, GDP per capita, and education across countries and years. One limitation is that some data may be missing for certain countries or time periods. I am also considering using additional datasets, such as United Nations data or other public APIs that include gender-related indicators.

Through my analysis, I hope to explore the following questions:
* How does technology access vary across income levels and over time?
* How is technology access associated with gender-related indicators, such as education or workforce participation?
* To what extent does technology access relate to quality of life, life expectancy or happiness?

This project will help me better understand global patterns in technology access and how they reflect broader inequalities, using multiple datasets and comparative analysis.

## Week 11 Update
For my final project, I chose the World Bank API as my main data source because it provides global data on things like internet usage and GDP per capita across many countries and years, which makes it easy to compare patterns. I accessed the data using API requests and imported it into a Google Colab notebook, where I converted the JSON data into pandas dataframes. I may also include additional datasets, such as happiness or gender-related data, to explore broader social outcomes. One strength of this dataset is that it covers many countries over time, but it also has some limitations, such as missing data and the presence of aggregate entries that need to be removed. It is also important to note that the data shows relationships between variables but does not prove causation.

From my preliminary analysis, I found that internet access has increased over time and is positively related to GDP per capita, with clear differences across income levels. To prepare the data, I selected relevant variables, converted data types, removed aggregate entries, and merged datasets by country and year. One challenge I faced was working with nested JSON data and making sure the datasets were consistent when merging. Moving forward, I plan to improve my analysis and possibly include additional datasets to explore more complex relationships. I am particularly interested in incorporating happiness or quality-of-life data, but finding a suitable dataset or API has been challenging. It is also difficult to determine what factors actually influence happiness, so selecting appropriate variables and interpreting the results will be an important next step in my project.

## Week 12 Update
In this week, I focused on creating interactive visualizations to better understand global technology access.

First, I created an interactive scatterplot to examine the relationship between GDP per capita and internet access. Each point represents a country. The x-axis shows GDP per capita on a log scale, and the y-axis shows the percentage of internet users. I also colored the points by income level to make it easier to compare patterns across groups, and hovering over a point reveals the country name. The plot shows a clear positive relationship between GDP per capita and internet access. In general, countries with higher GDP per capita tend to have a larger percentage of internet users. The pattern also highlights differences by income level, with high-income countries clustering near very high internet access rates, while low-income countries tend to have lower access overall.

<iframe
  src="internet_gdp_interactive.html"
  width="100%"
  height="600"
  frameborder="0">
</iframe>

Next, to better understand how internet access has changed over time, I created an interactive line plot showing average internet usage by region. This makes it easier to compare how different parts of the world have changed over time. The visualization shows that internet access has increased steadily in all regions, especially after the early 2000s. However, there are still clear differences between regions, with some areas having much higher access than others.

<iframe
  src="time_trend_interactive.html"
  width="100%"
  height="600"
  frameborder="0">
</iframe>

Overall, these visualizations suggest that while global internet access has improved significantly over time, there are still strong inequalities between countries. Access to technology appears to be closely related to economic development, highlighting a global digital divide.
