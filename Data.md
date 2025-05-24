# Big and small data

| Small Data | Big Data |
|----------|----------|
| Describes a dataset made up of specific metrics over a short, well-defined time period | Describes large, less-specific datasets that cover a long time period |
| Usually organized and analyzed in spreadsheets | Usually kept in a database and queried |
| Likely to be used by small and midsize businesses | Likely to be used by large organizations | 
| Simple to collect, store, manage, sort, and visually represent | Takes a lot of effort to collect, store, manage, sort, and visually represent |
| Usually already a manageable size for analysis | Usually needs to be broken into smaller pieces in order to be organized and analyzed effectively for decision-making |

---

# Data can be imported and combined in both spreadsheets and SQL databases. To import data into a spreadsheet, use the IMPORTRANGE function. To import data into a SQL table, use the INSERT INTO, SELECT, and WHERE commands. Use CONCATENATE to combine two or more data strings in spreadsheets. In SQL, use the CONCAT function to combine fields.

---

# The three (or four) V words for big data

| Volume | Variety | Velocity | Veracity |
|----------|----------|----------|----------|
| The amount of data | The different kinds of data  | How fast the data can be processed | The quality and reliability of the data |

---
![image](https://github.com/user-attachments/assets/a8917418-4233-4715-a2ff-edd0cf2add97)

---

| Wide data is preferred when   | Long data is preferred when  |
|----------|----------|
| Creating tables and charts with a few variables about each subject | Storing a lot of variables about each subject. For example, 60 years worth of interest rates for each bank |
| Comparing straightforward line graphs | Performing advanced statistical analysis or graphing |

---
# Sort data with SQL
## Sort data by one column
The ORDER BY command sorts data by column in a database. By default, the data is sorted in ascending order. 

1. In the BigQuery Explorer pane, select the movie dataset, then the movies table. 

2. Select the Preview tab from the Details pane.

3. Select Query then In new tab and enter the following code into the query editor: 
SELECT *
FROM projectID.movie_data.movies
ORDER BY `Release Date`;

4. 4. Use the ORDER BY command to sort the data. Enter ORDER BY `Release Date`; (notice the back-ticks, which are used to capture a column name that contains a space) to sort by the Release Date column.

5. Your code should now match this code block:

6. SELECT *
FROM projectID.movie_data.movies
ORDER BY `Release Date`;

7. Select RUN. The results return all the movies in the database sorted from oldest to newest.
