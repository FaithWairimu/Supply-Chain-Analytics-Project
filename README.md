# Supply Chain Analysis
 ## Table of Content
 - [Project Overview](#project-overview)
 - [Data Sources](#data-sources)
 - [Tools](#tools)
 - [Data Cleaning](#data-cleaning)
 - [Exploratory Data Analysis](#exploratory-data-analysis)
 - [Data Analysis](#data-analysis)
 - [Findings](#findings)
 - [Recommendations](#recommendations)
 - [Limitation](#limitation)
 - [References](#references)
### Project Overview
This data analysis project aims to provide insights to an e-commerce company.By analyzing the various aspects of the sales or supply data, we seek to identify trends, make data driven recommendation and gain a beter understanding of the company's performance.

### Data Sources
Sales data: The primary dataset used for this analysis is the "sales-data.csv" file, containing detailed information about each sale made by the company.
### Tools
- Excel - Data cleaning
- SQL server - Data Analysis
- Power BI - Generating the report
  ### Data Cleaning
  1. Data loading and inspection.
  2. Handling missing values.
  3. Data cleaning and formatting.
 
     
  ### Exploratory Data Analysis
  - What is the overall supply trend?
  - Which products are top sellers?
  - What are the peak supply periods?

    ### Data Analysis
    ```SQL
    SELECT * FROM table1
    WHERE cond = 4;
    ```
    ### Findings
    The analysis results are summarised as follows:
    1. The company's supply have increased over the past years, with a noticeable peak during the chrismas holiday.
    2. Product category1 is the best performing category as per the supply and revenue.
    3. Customers segment with high lifetime value should be targeted for marketing efforts.

    ### Recommendations
    Based on the analysis we recommend the following actions:
    - Focus on promoting products in category1
    - Invest in marketing during the chrismas holiday for better sales and revenue
    - Implement customer segmentation strategy to target high LIV customers efeectively

    ### Limitation
    I had to remove all zero values from the revenue column because they would have affected the accuracy of my conclusions. There are a few outliers even after the ommission, but we can still see the positive correlation between the budget and the revenue.
    ### References
    1. SQL for business by datacamp
    2. [stackoverflow](http://stack.com)
    
    
