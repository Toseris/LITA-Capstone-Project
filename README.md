# LITA-Capstone-Project
A project focused on analyzing customer data to understand behavior, preferences, and trends to help businesses make customer-centric decisions.

### Project Title : Customer Data Analysis
 [Project Overview](#project-overview)
 
 [Data Sources](#data-sources)
 
 [Tools Used](#tools-used)
  
 [Data Cleaning and Preparations](#data-cleaning-and-preparations)
   
 [Exploratory Data Analysis](#exploratory-data-analysis)
  
 [Data Analysis](#data-analysis)
   
 [Data Visualization](#data-visualization)

 ### Project Overview
---
To analyze sales performance and customer behavior to identify trends, enhance customer satisfaction, and drive revenue growth.

Key Goals:

1.Customer Segmentation:
Analyze customer demographics, purchase history, and preferences.
Segment customers into distinct groups for targeted marketing strategies.

2.Customer Satisfaction Analysis:
Gather customer feedback through surveys and reviews.
Analyze the correlation between satisfaction levels and sales.

3.Recommendations:
Provide actionable insights to improve sales strategies and enhance customer experience.
Suggest improvements in product offerings and customer engagement tactics.

### Data Sources
---
The data source used an Excel worksheet by The Incubator Hub which consist of Customer data and Sales data. Other worksheet like this can be found on Kaggle or any other data site.

### Tools Used
---
- Microsoft Excel [Download Here] (http://www.microsoft.com)
  
     1.For Data Cleaning, MSExcel helps removes duplicates rows, which helps eliminate redundant data.
 
     2.For Analysing and using features like PivotTables, which allow users to filter, sort, and summarize large datasets for detailed analysis.
 
     3.For Visualising data trends and patterns

     4.For performing functions simplify tasks like summing, averaging, finding maximum or minimum values, and performing advanced calculations.
 
- SQL- Structured Query Language for Quering of Data, it also enable efficient data retrieval, manipulation, and management in relational databases, supporting applications from basic 
  data querying to complex analytics and transaction management.
  
- Microsoft PowerBi enables users to visualize and share insights from their data. Power BI provides a variety of tools and functions to help users import, transform, model, and 
  visualize data. [Download Here] (https://www.microsoft.com/en-us/download/details.aspx?id=58494)
  
- Github is a Web Based Portfolio Buliding Platform that hosts and manages code repositories, primarily focused on version control and collaboration for software development projects.
  
### Data Cleaning and Preparations
---
Data cleaning and preparation is a crucial first step in data analysis, ensuring that data is accurate, consistent, and ready for analysis;
1. Handling Missing Values
2. Removing Duplicates
3. Validation and Consistency Checks
4. Documenting Data Cleaning Process

### Exploratory Data Analysis
---
EDA involves the examination of data to uncover patterns, spot anomalies, and check assumption. It also involved the exploring of the Data to answer some questions 
  about the Data such as ;
- What is the size of the dataset (number of rows and columns)?
- Are there any duplicate rows or records that need to be removed?
- Is there sufficient data to answer the key questions or support a model?
- How many unique customers, products, and regions are there in the dataset?

### Data Analysis
  ---
  This is where we include some basic lines of codes or queries or even some of the DAX expressions used during your analysis

  ```SQL
  Select * from [dbo].[LITA SalesData]

 Select 
	Product, 
	SUM(Revenue) AS TotalRevenuePerProduct
FROM 
	[dbo].[LITA SalesData]
GROUP BY 
	Product
ORDER BY 
	TotalRevenuePerProduct DESC
  ```
 	EXCEL	
Sum of Revenue by Region	
|Region| Sum of Revenue|
|------- |-------------|
|East	|16958763|
|North	|16817972|
|South	|16899064|
|West	|16864376|
|Grand Total|	67540175|

### Data Visualization
![Powerbi CD](https://github.com/user-attachments/assets/7c964a9f-0456-49c5-81f8-8c3504ec0bc3)


![Customer data](https://github.com/user-attachments/assets/dcc4e7ad-40fc-481a-9dd9-550bbb10fa26)
![CD 2](https://github.com/user-attachments/assets/f554ef8e-46f1-4427-96b6-a2e2dd43700c)
![CD 3](https://github.com/user-attachments/assets/c23cd1d5-93c8-46e7-9595-de8bf5531df2)
![CD 4](https://github.com/user-attachments/assets/48b12e25-14cd-4524-9d29-b5bcb0048706)
![CD 5](https://github.com/user-attachments/assets/c686e09e-3721-4071-8215-bf66e5cac469)
![CD 6](https://github.com/user-attachments/assets/8ed4ac7d-ce2f-4693-a2d4-340d649bcc09)
![CD 7](https://github.com/user-attachments/assets/2389157c-7331-4ef1-802c-3290139869be)
![CD 8](https://github.com/user-attachments/assets/b9f23b43-7847-44d7-940d-e51435b8cda1)
![CD1](https://github.com/user-attachments/assets/56d116ae-9080-41c4-89b5-91dd35abf87a)
![CD](https://github.com/user-attachments/assets/e8f616d9-21e2-429b-9bf6-f38cdb399fb5)
