# HR analytics project in Power BI

**A guided project from DataCamp´s career track: [Data Analyst in Power BI.](https://app.datacamp.com/learn/career-tracks/data-analyst-in-power-bi)**

![human resources word cloud](https://github.com/user-attachments/assets/07873f1b-6f8c-4140-b5c3-747e1a0a69e8)


## Table Of Contents

- [HR analytics project in Power BI](#hr-analytics-project-in-power-bi)
  - [Table of Contents](#table-of-contents)
  - [Introduction](#introduction)
  - [Importing and cleaning the data](#importing-and-cleaning-the-data)


## Introduction

The goal of this project is to help the HR team identify key metrics and actions to improve employee retention. The data is from a fictitious software company called Atlas Labs.

Using Power BI, I imported, cleaned, and analyzed six CSV datasets: `Date`, `EducationLevel`, `Employee`, `RatingLevel`, `SatisfiedLevel`, and `PerformanceRating`. Through exploratory data analysis and DAX calculations, I created visualisations to uncover insights into employee satisfaction, performance, and tenure. By understanding these factors, the company can develop targeted strategies to boost employee retention.


## Importing and cleaning the data

I initiated a new Power BI report and imported five CSV datasets: `EducationLevel`, `Employee`, `RatingLevel`, `SatisfiedLevel`, and `PerformanceRating`. To clarify the table roles, I prepended 'Fact' or 'Dim' to each table name, designating them as either fact or dimension tables. Next, I ensured that the columns were correctly formatted following the [Metadata table](metadata.md). Then, I created a new date calculated table using the DAX code from [DimDate.txt](DimDate.txt) file.

![Renaming the columns](https://github.com/user-attachments/assets/b20dcb79-c69c-4187-a0e8-1f70c925edc3)


<br/>Once the data was loaded and cleaned, I create a data model to establish the relatioships between tables. This image shows the initial data model.
![Initial model](https://github.com/user-attachments/assets/38db1b21-02cc-480a-bea1-857af4841be2)

<br/>This image show the final data model used for the analysis.
![The final model ](https://github.com/user-attachments/assets/404b18c9-f94a-494a-b5f1-e42d99c90d5e)


<br/>
as







