# Sales Insights Data Analysis Project
Sales Insights Data Analysis Project using Power BI

Electronic Hardware company has HQ in Delhi and many branches across the country
Tracking sales in dynamically growing market, wants an overall simple insight of all the branches across the country
Now we use AIMS grid to get 

Purpose of the project:
Clients/Stakeholders: Sales director, marketing director, customer service team, IT team, 
End results: An automated dashboard providing a quick & real latest sales insights in order to make data driven decisions. 
Success criteria: Dashboard displaying providing a quick & real latest sales insights. Use the sales data and reduce overall sales process cost by 10%
Increase productivity by saving 10% of the time spent on doing things manually

The data is processed by sales management software which is MySQL based run by a 3rd party vendor, so we asked the 3rd party vendor to send us all the latest sales related SQL files from 2017 to 2020(3 yrs)
Now we do basic analysis of the SQL files in MySQL like checking the no of tables, no of column & rows, null & garbage & 0 values, dates, important primary keys, data types, type of currencies if any, important KPI data, etc 

Now we extract and upload the MySQL sales file into Power BI. 
Review all the tables(customer, date, market, product, transactions) in the data tab of Power BI. 
Start with clean the entire data from all tables as necessary:
In markets we see the company has sold mainly sold products only in India and has only two trans in foreign countries, so we will use transform(power query editor) of Power BI to resolve this. In transactions table we notice -1, 0 values which will be resolved. Remove duplicate(INR, USD) from currency column in transactions table. And futher cleaning.
Then creating a Dashboard displaying important KPIs for the Client
