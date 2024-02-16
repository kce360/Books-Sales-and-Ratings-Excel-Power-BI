# Books-Sales-and-Ratings-Excel-Power-BI
Overview
The Books Dataset: Sales, Ratings, and Publication provides comprehensive information on various aspects of books, including their publishing year, author details, ratings given by readers, sales performance data, and genre classification. This portfolio project aims to utilize the dataset to gain insights into the book market, analyze author performance, identify trends in publishing, and explore correlations between different variables.
The data set was downloaded from https://www.kaggle.com/datasets/thedevastator/books-sales-and-ratings/data

**Dataset Description**
The dataset consists of several key columns that capture important attributes related to each book:<br>
Publishing Year: Indicates the year in which each book was published.<br>
Book Name: Contains the titles of the books.<br>
Author: Specifies the name(s) of the author(s) responsible for creating each book.<br>
Language Code: Represents the code assigned to indicate the language in which each book is written.<br>
Author Rating: The rating assigned to the author based on their previous works.<br>
Book Average Rating: The average rating given by readers for each book.<br>
Book Ratings Count: The number of ratings given to each book by readers.<br>
Genre: Books are classified into different genres or categories.<br>
Gross Sales: Total sales revenue generated by each book.<br>
Publisher Revenue: Revenue earned by publishers from selling each book.<br>
Sale Price: The price at which each copy of a book is sold.<br>
Sales Rank: A numeric value indicating a book's rank based on its sales performance.<br>
Units Sold: Total number of copies sold for each specific title.<br>

**Research Questions**

**Which author has the highest average book rating?**<br>
Analyzed authors' average book ratings to identify the most acclaimed authors.<br>
**What is the trend in book publication over the years?**<br>
Explored the distribution of book publication over time to understand publishing trends.<br>
**What are the top-selling genres based on gross sales revenue?**<br>
Identified the genres that generate the highest gross sales revenue to understand commercial success.<br>
**Which publisher has the highest number of units sold?**<br>
Determined the publisher with the highest sales volume to highlight market dominance.<br>
**What authors sold the most books and generated the most gross sales?**<br>
Analyzed authors' sales performance and gross sales generated to identify top-selling authors.<br>

**Process**

**Data Cleaning in Excel:**<br>
Standardized Publishing Year.<br>
Removed corrupted data in Book Name and Author columns.<br>
Checked for duplicates.<br>
Verified gross sale calculation.<br>
Some data was restored by ChatGPT because it was incorrectly parsed (49 rows in Latin and Arabic languages mostly)<br>
Analysis in Excel:<br>
Identified top 10 authors with the highest average book rating (Pivot Table).
 
**Visualization in Power BI:**<br>
Explored trends in book publication over the years.<br>
Identified top-selling genres based on gross sales revenue.<br>
Determined the publisher with the highest number of units sold.<br>
Analyzed authors' sales performance and gross sales generated.<br>
For Average Book Rating the measure was used: Average Book Rating = AVERAGE('Books_Data_Clean'[Book_average_rating])<br>
Publishing Year Data was divided into bins (20 years each).<br>

**Conclusion**
Through data cleaning, analysis, and visualization, this portfolio project provides valuable insights into the book market, author performance, publishing trends, and sales performance. The findings can be used by publishers, authors, and stakeholders in the publishing industry to make informed decisions and strategies for success in the competitive book market.

