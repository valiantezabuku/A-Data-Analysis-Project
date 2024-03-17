# A-Data-Analysis-Project (India Startup Funding Analysis)
This project presents an analysis of funding received by Indian startups from 2018 to 2021 using Exploratory Data Analysis (EDA) techniques. The objective of this analysis was to gain insights into the Indian startup ecosystem, and as the data expert of the team, my role was to investigate the ecosystem and propose the best course of action by providing valuable information for decision-makers considering entry into the market, and understand the funding and growth patterns of newly launched startups.
### Summary
| Project Code | Project Name | Published Article | Power BI Dashboard |Libraries Used|
|--------------|--------------|-------------------|-----------------|--------------|
| LP1          | India <br> Startup <br> Funding <br> Analysis| Article | PowerBI|Pandas <br> Numpy <br> Matplotlib <br> Seaborn|
### Exploratory Data Analysis (EDA)
Exploratory Data Analysis (EDA) plays a vital role in understanding and extracting insights from datasets. It allows us to uncover patterns, relationships, and key characteristics of the data. The main objective of this project is to utilize the CRISP-DM framework as a guiding framework for conducting exploratory data analysis (EDA) and extracting valuable insights. The Cross Industry Standard Process for Data Mining (CRISP-DM) is a process model that serves as the base for data processing.
### Introduction
The analysis was performed using the Python programming language and popular libraries such as Pandas, NumPy, Seaborn and Matplotlib. These libraries facilitated various analysis tasks, including examining individual variables, exploring relationships between variables, analysing correlations, and handling duplicate and missing data.

The analysis was conducted in a Jupyter Notebook environment, which allowed for an interactive and organized workflow. The notebook provided a seamless platform to execute code, visualize data, and document the analysis process. Standard EDA procedures were followed, including assessing data quality, performing descriptive statistics, and creating visualizations.

The dataset was explored to understand its structure, check for missing or duplicated data, and convert variables to appropriate formats when necessary. Descriptive statistics provided a summary of the data, allowing for an understanding of the central tendencies, variations, and distributions of the funding received by Indian startups. Visualizations, such as histograms and scatter plots were created to identify patterns, trends, and relationships between variables. The analysis also involved examining the relationship between funding and the growth of startups, enabling the identification of potential factors influencing success and providing insights for decision-making.

Imported libraries
To begin the analysis, I started by importing the necessary libraries and packages that will be used throughout the process. These libraries include:
•	Pandas: for data cleaning and manipulation
•	Numpy: for data cleaning and manipulation
•	Matplotlib: for visualizations
•	Seaborn: for visualizations
•	Plotly: for visualizations
•	Mann Whitney: for Hypothesis testing
•	Re: for regular expressions

### Understanding the Data
##### 1.	Acquisition Process
The dataset used in this analysis comprises information sourced from various platforms, including a database, OneDrive account, and GitHub repository. Each source contributes different sets of data, which are integrated for comprehensive analysis.
###### 1.	Database (2020 and 2021 Data):
- The primary dataset originates from a database containing information spanning the years 2020 and 2021.
- Access to this dataset requires utilizing environment variables, which I used to enable seamless data retrieval.
###### 2.	OneDrive Account (2019 Data):
- Additional data for the year 2019 is sourced from a CSV file stored on a OneDrive account.
- This file was downloaded and imported into the analysis environment using the Pandas library.
###### 3.	GitHub Repository (2018 Data):
- The dataset for the year 2018 is obtained from a CSV file hosted on a GitHub repository.
- Similar to the OneDrive data, the GitHub data was downloaded and incorporated into the analysis workflow using Pandas.
##### 2.	Shared Columns across Datasets:
The datasets share several common columns, each providing essential insights into the startup ecosystem. These shared columns and their descriptions include:
- Company/Brand: Name of the startup or company 
- Founded: The year in which the startup was founded, providing insights into its establishment timeline.
- Sector: The sector or industry in which the startup operates, categorizing its area of business.
- What it does: A brief description outlining the core activities or services offered by the startup.
- Founders: Individuals or groups credited with founding the startup, indicating key personnel involved.
- Investor: Entities or individuals participating in funding rounds or investment deals involving the startup.
- Amount($): The total amount of funds raised by the startup, denominated in dollars, reflecting its financial backing.
- Stage: The current stage of funding or investment round in which the startup is engaged.
- Headquarters: Location of the startup's headquarters, providing geographical context for its operations.
##### 3.	Gaining Insights into Data.
- df.shape(): This function is a handy tool that tells us the dimensions of our dataset. For example, in our analysis, the 2018 dataset contains 526 rows and 6 columns, while the 2019 dataset has 89 rows and 9 columns. Similarly, the 2020 dataset comprises 1051 rows and 9 columns, and the 2021 dataset boasts 1189 rows and 9 columns.
- df.head(): When we use this function, it reveals the first five rows of our dataset. This sneak peek gives us a quick glance at the structure and content of our data, helping us understand its initial layout and potential insights. Similarly, df.tail() showcases the last five rows of the dataset, completing our view of both ends of the data spectrum.
- df.info(): This function provides a comprehensive overview, including the column names, data types, and the number of non-null values in each column. With this information, we gain a deeper understanding of the dataset's composition and potential areas for data cleaning or preprocessing.

### Business Questions
1.What sectors have shown the highest growth in terms of funding received over the past four years?
2.What locations within India have emerged as the primary hubs for startup activity and investment, and what factors contribute to their prominence?
3.Are there any notable differences in funding patterns between early-stage startups and more established companies?
4.Which sectors recieve the lowest level of funding and which sectors recieve the highest levels of funding in India.
5.Which investors have more impact on startups over the years?
### Hypothesis
During the analysis process, I formulated a null and alternative hypothesis to guide the investigation. Various business questions are posed and analysed to gain insights from the data. Ultimately, the null hypothesis is either accepted or rejected based on the findings derived from the data analysis.

Null Hypothesis (Ho): There is no significant difference in the amount of funding between startups in Bangalore.

Alternative Hypothesis (Ha): There is a significant difference in the amount of funding between startups in Bangalore.

### CONCLUSIONS
Based on my analysis, it's clear that the Technology sector has been a standout performer in terms of funding trends from 2018 to 2021. This sector, along with related tech-incorporated sectors like Commerce, Transport and Finance, presents promising opportunities for investors and entrepreneurs. Additionally, Bangalore and Mumbai, being prominent hubs for startups and investments, offer valuable networking prospects. Therefore, exploring opportunities in tech-driven sectors and engaging with Mumbai's startup ecosystem could lead to favourable outcomes in terms of growth and innovation.

#### Address
Email: vezabuku09@gmail.com
#### Author
Adiru Valiant Ezabuku

























