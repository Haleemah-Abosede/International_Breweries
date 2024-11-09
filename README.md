# International_Breweries
## Table of Contents
-	Overview
-	Data Sources
-	Tools and Technologies Used
-	Data Cleaning and Preprocessing
-	Exploratory Data Analysis (EDA)
-	Analysis and Findings
-	Visualizations
-	Conclusions and Insights


### Overview
This project analyses data on breweries brands to uncover key factors impacting product performance and revenue growth. By leveraging Excel, SQL, and Power BI, this analysis provides actionable insights for the sales team and strategic planners.

### Data Sources
Source: Incubator Hub Data Analysis Class International Breweries data 
Description: Contains details of sales reps for 7 brewery brands including cost, profit and demographic information, with 1047 records across 13 columns.

### Tools and Technologies Used
-	Microsoft Excel: For initial data cleaning, analysis, and quick calculations.
-	SQL: Used for data extraction, transformation, and complex querying.
-	Power BI: For creating interactive dashboards and data visualizations.

### Data Cleaning and Preprocessing
#### Excel
-	Removed duplicates.
-	Filled missing values with appropriate substitutes.
#### SQL
-	Applied GROUP BY for aggregations and calculated new columns with CASE statements.
#### Power BI
-	Created custom calculated columns and measures to facilitate analysis.
-	Transformed data types as needed to optimize visuals and calculations.

### Exploratory Data Analysis (EDA)
#### Descriptive Statistics: 
The data shows the average sale transactions of each brand as 149.57 with beta malt, grand malt and hero totalling at 149 each while the other 4 brands were 150 each. The quantity sold for each brand differs across 6 regions, 5 countries anchored by 11 sales reps. 
#### Trends and Patterns: 
The sale of the breweries followed a sequential pattern around the regions with sales going on in southeast in January and July, in the west in February and August, in south-south in March and September, in the northwest in April and October, in the northeast in May and November and in the Northcentral in June and December.
#### Correlations: 
An increase in quantity sold does not necessarily increase the profit generated e.g. hero sold a total of 129,060 bottles and made 6,453,000 in profit compared to castle lite which sold 128,174 bottles and made 34,606,980 in profit. Factors like different in unit price and plant cost are responsible for this. It can be inferred that many customers buy hero but castle lite generated more profit

### Analysis and Findings
#### Product Performance:
Castle Lite performed best in terms of profit generated (34,606,980) while hero had the highest number of quantities sold (129,060). Jones proved to be the best sales rep generating a total of 18,770,830 in profit from the sale of 157,880 products.


#### Geographic Trends:
Castle lite has the highest profit across the 6 regions followed by Budweiser. Senegal sold the highest quantities of hero (26, 632), castle lite (25,974) and beta malt (25, 625), trophy (25, 743), eagle lager (25, 872) and Budweiser (26, 153) were the highest sold in Nigeria while Ghana sold the highest quantity of grand malt (25, 615)

### Visualization
![intBreweries_BI_1](https://github.com/user-attachments/assets/6dbd67d7-22e3-4bf5-be84-117f81fad7a2)
![intBreweries_BI_2](https://github.com/user-attachments/assets/c1388853-77f2-4b4c-a6f8-996670a04899)

This dashboard includes key metrics such as monthly sales, top products, and regional sales distribution.

### Conclusion and Insights
The analysis revealed that castle lite and Budweiser can be used as target product in terms of profit generation and though Budweiser falls short in terms of quantity sold at 126, 274 compared to castle lie at 128,174, it’s overall profit at 31, 568,500 was just short of castle lite’s 34,606,980 making it the second most profitable brand. Hero proved to be the most popular in terms of quantity sold. An increase in its unit price will boost its profitability.
