# MYSQL
In this project I looked at company layoffs ranging from their industry, how many people laid off,the percentage of their total workforce laid off, and how much funds the company raised. First I removed the duplicates in the data, standardized it by removing the null values. In order to standardize this data I created a staging table and in this new table I created new rows by partitioning columns in order to find duplicates. I created tables and CTEs along in order to remove duplicates. I standardized the data once more to by trimming white space off of the values in all columns. Next I formatted the date in order to standardized it as well. Then I removed nulls and blanks if both columns "total_laid_off" and "percentage_laid_off" were empty since having one value would still be considered useful information. After standardizing everythin I removed columns I created and deemed unuseful. This would conclude the first part of this project.

Next I did some exploratory data analysis from the data I cleaned. This is what I found:
* Max number of people laid off from a company.
* Bankrupt companies by searching when percentage_laid_off was = 1.
* Which companies laid off the most people.
* Industry that laid off the most people.
* Country that laid off the most people.
* How much people were laid off in each year, and each month.
* The top 5 companies that laid off the most people in each year.
* Who laid off the most people while recieving the most raised funds.

These such examples are findings I have done but there is still more I can explore depending on the clients needs.
