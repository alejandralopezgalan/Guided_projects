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

I initiated a new Power BI report and imported five CSV datasets: `EducationLevel`, `Employee`, `RatingLevel`, `SatisfiedLevel`, and `PerformanceRating`. To clarify the table roles, I prepended 'Fact' or 'Dim' to each table name, designating them as either fact or dimension tables.

![Renaming the tables](https://github.com/user-attachments/assets/3abf9811-cdd0-41cf-a2fc-78a848619989)


Next, I ensure that the columns were correctly formatted following the [Metadata table](metadata.md). Then, I created a new calculated table using DAX code from the [DimDate.txt](DimDate.txt) file and connected it to the FactPerformanceRating table in the Model view. I also connected it to the DimEmployee table to star building the model for our data.

![Building the data model](https://github.com/user-attachments/assets/be1c975a-887d-449b-8f04-62d51ab0fe6e)





