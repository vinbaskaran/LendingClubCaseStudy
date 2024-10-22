# LendingClubCaseStudy
> To understand the driving factors behind loan default, i.e. the variables which are strong indicators of default for a consumer financial services company to improve risk assessment. 

## Objectives:
- Identify patterns in default rates.
- Understand borrower demographics and financial characteristics.
- Provide insights for improving loan risk assessment.

## Table of Contents
* [EDA Approach](#eda-approach)
* [Conclusions](#conclusions)
* [Technologies Used](#technologies-used)
* [Contact](#contact)
* [NB Viewer Link](#nb-viewer-link)


## EDA Approach
- Data Preprocessing 
  - Remove columns that do not add value to analysis
  - Missing Value Analysis and Treatment
  - Data Type Conversion
  - Derived Columns generation for better insights
- Univariate Analysis
  - Outlier Analysis of numerical variables through box plot
  - Visualize Distribution of loans by binning numerical variables
  - Visualize Distribution of loans by categorical variables
- Bivariate Analysis
  - Relation between categorical and numerical variables through box plot
  - Correlation Matrix to understand correlation among numerical variables and with default rate
  - Comparison of Default rate with all variables


## Conclusions
- Stricter Criteria for Larger Loans: Limit high loan amounts to reduce default rates.
- Promote 36-Month Loans: Focus on shorter-term loans that are more manageable for borrowers.
- Target Grade A and B Customers: Tailor products to the needs of high-grade borrowers.
- Segmentation Analysis: Use customer segments based on their credit history, income, and loan amount to better predict default risk and tailor products accordingly.
- Historical Credit Review: Assess customers with delinquent histories better.
- Small Business Loans: Assess Small Business loans better especially those issued in Q3.


## Technologies Used
- jupyterlab - version 4.2.5
- ipython - version 8.25.0
- pandas - version 2.2.2
- numpy - version 1.26.4
- seaborn - version 0.13.2
- matplotlib - version 3.8.4
- ipywidgets -version 8.1.5
- plotly - version 5.22.0


## Contact
Created by [Vineeth B - @vinbaskaran](https://github.com/vinbaskaran) 


## NB Viewer Link
[https://nbviewer.org/github/vinbaskaran/LendingClubCaseStudy/blob/main/Lending_club_case_study_EDA.ipynb](https://nbviewer.org/github/vinbaskaran/LendingClubCaseStudy/blob/main/Lending_club_case_study_Vineeth.ipynb)
