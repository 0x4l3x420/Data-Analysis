# Variations of the data life cycle
 * Plan: Decide what kind of data is needed, how it will be managed, and who will be responsible for it.
 * Capture: Collect or bring in data from a variety of different sources.
 * Manage: Care for and maintain the data. This includes determining how and where it is stored and the tools used to do so.
 * Analyze: Use the data to solve problems, make decisions, and support business goals.
 * Archive: Keep relevant data stored for long-term and future reference.
 * Destroy: Remove data from storage and delete any shared copies of the data.
 ---
## U.S. Fish and Wildlife Service
The U.S. Fish and Wildlife Service uses the following data life cycle:

* Plan
* Acquire
* Maintain
* Access 
* Evaluate
* Archive
---
## The U.S. Geological Survey (USGS)
The USGS uses the data life cycle below:

* Plan
* Acquire
* Process
* Analyze
* Preserve
* Publish/share
  
Several cross-cutting or overarching activities are also performed during each stage of their life cycle:

* Describe (metadata and documentation)
* Manage quality
* Backup and secure
---
## Financial institutions
Financial institutions may take a slightly different approach to the data life cycle as described in 
The Data Life Cycle, an article in Strategic Finance magazine:

* Capture
* Qualify
* Transform
* Utilize
* Report
* Archive
* Purge
---
## Harvard Business School (HBS)
One final data life cycle informed by Harvard University research has eight stages:

* Generation
* Collection
* Processing
* Storage 
* Management
* Analysis
* Visualization
* Interpretation
---
### Data management universal principle : Govern how data is handled so that it is accurate, secure, and available to meet your organization's needs
---
# Spreadsheets
To collect and organize data, structure data in a meaningful way. 

* Collect, store, organize, and sort information
* Identify patterns and piece the data together in a way that works for each specific data project
* Create excellent data visualizations, like graphs and charts.
---
# Databases and query languages 
Collection of structured data stored in a computer system.

* Allow analysts to isolate specific information from a database(s)
* Make it easier for you to learn and understand the requests made to databases
* Allow analysts to select, create, add, or download data from a database for analysis
---
# Visualization tools
Two popular visualization tools are Tableau and Looker
* Turn complex numbers into a story that people can understand 

* Help stakeholders come up with conclusions that lead to informed decisions and effective business strategies  

* Have multiple features 

             - Tableau's simple drag-and-drop feature lets users create interactive graphs in dashboards and   

                worksheets 

             - Looker communicates directly with a database, allowing you to connect your data right to the visual 

                 tool you choose
---
# Spreadsheets
Main features of a spreadsheet: cells, rows, and columns.
 * Attribute is a characteristic or quality of data used to label a column in a table. Attributes are referred to as column names, column labels, headers, or the header row.
 * Observation includes all of the attributes for something contained in a row of a data table.
 * Formula is a set of instructions that performs a specific action using the data in a spreadsheet.
Spreadsheet resources : [Google Sheets Training and Help](https://support.google.com/a/users/answer/9282959?visit_id=637361702049227170-1815413770&rd=1) / [Google Sheets Quick Tips](https://support.google.com/a/users/answer/9300022) / [Microsoft Excel for Windows Training](https://support.microsoft.com/en-us/excel)
---
# SQL(Structured Query Language)

SQL queries use SELECT, FROM, and WHERE to specify the data to be returned from the query. Capitalization, indentation, and semicolons are useful for making your SQL queries easier to read. In addition, comments can be added to explain queries to others.
![query](https://github.com/user-attachments/assets/de627d57-2fe1-4372-b7d1-1996aded58cf)

 [SQL Cheat Sheet](https://www.sqltutorial.org/sql-cheat-sheet/)
: For more advanced learners, go through this handy 3-page resource to gain an overview of additional SQL functions and formulas. By the time you are finished looking through the cheat sheet, you will know a lot more about the various SQL techniques and will be prepared to use it for business analysis and other tasks.

---

## WHERE conditions
The SELECT clause identifies the column you want to pull data from by name, field1, and the FROM clause identifies the table where the column is located by name, table. Finally, the WHERE clause narrows your query so that the database returns only the data with an exact value match or the data that matches a certain condition that you want to satisfy. 

Example, if you are looking for a specific customer with the last name Chavez, the WHERE clause would be: 

WHERE field1 = 'Chavez'

However, if you are looking for all customers with a last name that begins with the letters “Ch," the WHERE clause would be:

WHERE field1 LIKE 'Ch%'

You can conclude that the LIKE clause is very powerful because it allows you to tell the database to look for a certain pattern! The percent sign % is used as a wildcard to match one or more characters. In the example above, both Chavez and Chen would be returned. Note that in some databases an asterisk * is used as the wildcard instead of a percent sign %.

---
## SELECT all columns
Can you use  SELECT * ?

In the example, if you replace SELECT field1 with SELECT * , you would be selecting all of the columns in the table instead of the field1 column only. From a syntax point of view, it is a correct SQL statement, but you should use the asterisk * sparingly and with caution.  Depending on how many columns a table has, you could be selecting a tremendous amount of data. Selecting too much data can cause a query to run slowly.

---
# Steps to plan a data visualization
Data analysts use lots of different tools and methods to visualize and share their data.

Step 1: Explore the data for patterns<br />
Step 2: Plan your visuals<br />
Step 3: Create your visuals<br />

Data visualization toolkit
* You can use the visualizations tools in your spreadsheet to create simple visualizations such as line and bar charts.

* You can use more advanced tools such as Tableau that allow you to integrate data into dashboard-style visualizations. 

* If you’re working with the programming language R you can use the visualization tools in RStudio.
![image](https://github.com/user-attachments/assets/6adac8e7-3840-431a-a66d-040fb3143613)
## Visualization software
### Tableau
Tableau is a popular data visualization tool that lets you pull data from nearly any system and turn it into compelling visuals or actionable insights. The platform offers built-in visual best practices, which makes analyzing and sharing data fast, easy, and (most importantly) useful. 
### Programming language (R with RStudio) 
A lot of data analysts work with a programming language called R. Most people who work with R end up also using RStudio, an integrated developer environment (IDE), for their data visualization needs. As with Tableau, you can create dashboard-style data visualizations using RStudio.

---

# The beauty of dashboards

| Benefits | For data analysts | For stakeholders |
|----------|----------|----------|
| Centralization | Share a single source of data with all stakeholders | Work with a comprehensive view of data, initiatives, objectives, projects, processes, and more |
| Visualization | Show and update live, incoming data in real time* | Spot changing trends and patterns more quickly |
| Insightfulness | Pull relevant information from different datasets | Understand the story behind the numbers to keep track of goals and make data-driven decisions |
| Customization | Create custom views dedicated to a specific person, project, or presentation of the data | Drill down to more specific areas of specialized interest or concern |
