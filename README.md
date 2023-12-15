# City of Toronto Budget Analysis (Financial planning)

## Description of the Project 

This project talks about 
This initiative focuses on acquiring and analyzing comprehensive budgeting data for programs within the City of Toronto. Sourced from official government channels and municipal websites, the dataset encompasses crucial details, including program names, detailed expenditure and revenue categories, and corresponding budget amounts. Through this project, we aim to provide valuable insights that will contribute to informed financial planning and decision-making processes for the City of Toronto.

The analysis we're going to do is .. 
1. Exploratory Data Analysis (EDA):
   Conduct EDA to understand the characteristics of the budget data.
   Explore basic statistics such as mean, median, and standard deviation.
   Visualize the distribution of budget allocations using histograms or box plots.
   Identify outliers and anomalies in the data.
2. Expenditure and Revenue Category Analysis:
   Categorize expenditures into relevant categories.
   Explore the distribution of expenditures across different categories using bar charts.
   Study on Sub Category Analysis
4. Program Summary:
   Create a program summary that aggregates expenditures by program.
   Identify programs with the highest and lowest budgets.
   Visualize the distribution of budgets across programs using bar charts or stacked bar charts.
5. Trend Analysis:
   Analyze budget trends over multiple years if historical data is available.
   Identify categories or programs with significant changes in budget allocations over time using line charts or time series plots.
6. Predictive Modeling:
   Explore the possibility of building predictive models to forecast future budget allocations based on historical trends.
7. Comparison with Demographic Data:
   Explore the relationship between budget allocations and demographic data for the City of Toronto. This could include factors such as population density, income levels, or other relevant indicators.
8. Correlation Analysis:
   Investigate potential correlations between budget categories.
   Explore whether increased spending in one category is associated with changes in another using correlation matrices.

The questions we're going to answer are: 
1. What do the averages tell us about the operating budget data? ​
2. What categories of expenses/revenues have changed or completely eradicated? ​
3. How do the consistent expenditure trends and rankings across different categories reflect the city's overarching priorities and financial strategies over the five-year period? ​
4. Does the area demographic affect the budget allocation? ​
5. What Insights Do Outliers in Toronto's Operating Budget Provide when Analyzing Expenses and Revenues Separately? ​
6. What trends can be observed in the revenue and expenses for the different categories and programs of the city's financials within the period of 5 years? ​
7. Using the simple moving average of 3 periods, What is the overall behavior of the revenue throughout the past 10 years ? ​
8. Which Category has the highest and lowest expense and lowest for each year ?​
9. Is there any fluctuations in the trend for any specific category for any year ?​
10. Which Subcategory has the highest contribution in terms of Expense and Revenue ​
11. What is the percentage contribution for each category for each year ​
12. Is there any co-relation between different categories of revenue and expense ​
13. Relationship between years and Category ​

## Members of the group

The members in this group are: 
1. Aayush Gambhir (aayushgambhir2023)
2. Jason Tong (jasont1209)
3. Lucas Antonio Girelli (Girellil)
4. Muskan mittal (Muskanmittal323)
5. Anuradha Kishore (anuradhakishore)

## Work breakdown strucutre
- Aayush will be pulling the data from Open Toronto, clean and preprocess it, and analyzing it, and answering question 3,5 and 6.
- Jason will be transforming the data from open Toronto, and will be doing analysis 6, and answering question 4.
- Lucas will be transforming the data from open Toronto, and will be doing analysis 4, and answering question 6 and 7.
- Muskan will be transforming the data from open Toronto, and will be doing analysis 1 and 3, and answering question 1,2, and 8.  
- Anuradha will be transforming the data from open Toronto, and will be doing analysis 2 and 7, and answering question 8,9,10,11,12 and 13.


## Datasets used: 
1. https://open.toronto.ca/dataset/budget-operating-budget-program-summary-by-expenditure-category/
2. https://open.toronto.ca/dataset/budget-capital-budget-plan-by-ward-10-yr-approved/
3. https://www12.statcan.gc.ca/census-recensement/2021/dp-pd/prof/details/download-telecharger.cfm?Lang=E&SearchText=toronto%20centre&DGUIDlist=2023A000435109&GENDERlist=1,2,3&STATISTIClist=1,4&HEADERlist=0 


## Analysis 
See analysis.docx for full analysis.


## Limitations
For Demographic impact – Federal Electoral District data for 2021 was obtained from Census Canada which uses only 25% sample data. Ward profiles from the City of Toronto only publicly show 2016, and after contacting the Social Policy Analysis & Research unit of the Social Development, Finance and Administration division at the City of Toronto, they stated that the 2021 profiles are in the process of being created and should be out soon, and directed me to the data from Statistics Canada.
There is a gapping category exhibits a negative value in the summary. The negative value signals the presence of unaccounted expenses. These unidentified costs are likely incorporated as an adjustment to rectify the total operating budget. This underscores the necessity for a more in-depth study to categorize and understand these expenses, as they do not align with any specific category


## File Problems
98-401-X2021010_English_CSV_data.csv was too large to commit to github at 180MB, so some data that were irrelavent were deleted as it contains the census of electorial wards of all of Canada, and only the data for Toronto was needed.

## Presentation Link
https://onedrive.live.com/edit?id=4E368AAC1276387A!112&resid=4E368AAC1276387A!112&ithint=file%2cpptx&authkey=!AOqNd8yonEBrea0&wdo=2&cid=4e368aac1276387a
