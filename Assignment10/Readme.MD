# Cleaning and Tidying Data in Pandas

In this exercise, I will be following along with the speaker as he discusses the concept of tidy data and how to use Pandas to make data tidy: https://www.youtube.com/watch?v=iYie42M1ZyU

The data files and notebooks used in the video are hosted in GitHub: https://github.com/chendaniely/pydatadc_2018-tidy

**Observations** 

1. In tidy data:
* Each variable forms a column.
* Each observation forms a row.
* Each type of observational unit forms a table.

2. Tidy data allows us to reduce the amount of time and effort needed for data cleaning.

3. Common issues with untidy data are:
* Some column headers are values, not variable names
* Multiple variables are stored in one column
* Variables are stored in both rows and columns
* Multiple types of observational units are stored in the same table

4. Pandas melt unpivots a DataFrame from wide format to long format.
