# Codecademy Data Engineer Career Path Notes

![Codecademy Logo](https://upload.wikimedia.org/wikipedia/commons/6/6c/Codecademy.svg)

## Introduction:
from languages like Python, SQL, and PySpark to tools like GitHub, the Command Line, and Digital Ocean alongside essential skills like working with big data, cloud-based hosting, and data wrangling. You’ll build a portfolio along the way to showcase your work to future employers.

After this Path, you will be able to:
- Clean, transform, and manipulate data with Python and SQL
- Build data pipelines
- Move data between different platforms and across languages
- Protect data and manage permissions
- Create logging functions to monitor your code
- Write unit tests to ensure resiliency of your code
- Improve your code’s efficiency with concurrent programming
- Create and manage NoSQL databases with MongDB
- Deploy a database on the cloud with Digital Ocean
- Use the command line
- Manage versions of your code with Git
- Collaborate with teammates on GitHub

Data Engineers make data usable. They build and monitor data pipelines, automate cleaning tasks, ensure data validity, manage ingestion, and are at the centre of any data-driven organisation.
- make sure that a vital resource is delivered without leaks or contamination
- In a perfect world, they also clean it up and develop tools for the end user to control the flow.

Portfolio Projects, here’s a preview of the projects featured in this Path:

1. Bike Rental Data Management
  - Use Jupyter Notebooks and PostgreSQL to explore, clean, and merge Citi Bike ridership and NOAA weather data to produce a database with analytics-ready views!
2. Analyze Common Crawl Data with PySpark
  - Use PySpark, Pandas, and SQL to tackle a big data problem and manage the output of common crawl data.
3. Subscriber Cancellations Data Pipeline
  - Use Python to create a data ingestion pipeline to automatically clean and update customer information.

## In the day Day with the Data Scientists
While Data Engineers are not themselves Data Scientists, the two teams work closely together to develop and deploy advanced analytics studies and models.

Data scientists work on the development side of this partnership, using tools like Python pandas to create models and analyses.

But even the most advanced models aren’t that useful if they aren’t regularly updated with new data or published in an accessible location. Enter the data engineers! Once a data model or study is prepared by data scientists, data engineers deploy it by creating automated data pipelines that:

- regularly update the data
- test for and log any errors
- load the output to a cloud database or business intelligence tool

### A Sample Pipeline
The data scientists at Codecademy have been studying users. They’ve been working with data from the user profiles. The study is ready to be put into production by a Data engineer.

`Notebooks -> Python`

Like most companies, data scientists work in Jupyter Notebooks. Jupyter Notebooks are browser-based workspaces that help data scientists quickly prototype analytics and visualisations. Vince’s first task is to transform the notebook into a Python script that can be run on its own outside of the notebook environment.

While doing this, Vince will also add unit tests, pieces of code that check to make sure the program is working as expected, and log errors if not. These tests weren’t strictly necessary for the Jupyter Notebook, which was always run directly by a data scientist. Data engineer version of the script will be run by a computer process, and so needs controls in place to stop it from improperly updating the study if something goes wrong.


### Live Data

The data scientists were working with snapshot data: copies of the live databases at a certain point in time. These were stored in Excel spreadsheets and CSVs (text-based tables that use commas to separate the columns).

Data engineer will have to use SQL to connect his script to the live databases, so it can be updated on a regular basis.


### Automation
To make it easier to regularly run scripts, use the command line or terminal, a method for directly giving commands to a computer.

command line program will handle running the Python script along with any tedious tasks like moving and renaming files or listing changes to the dataset. This way, updating the study will be as simple as running a single program (and checking the error log!).


### Output to the cloud
To see the results of the study. To make them available across the organisation, Vince’s script will output the results to Codecademy’s cloud database stored on the cloud computing platform DigitalOcean(asure). This database is connected to business intelligence tools, so everyone who needs to can use this study to understand user success!



### summary
Data engineer:
1. Used Python and SQL to reconcile two different database structures
2. Used Python, SQL, and the command line to deploy a data science study
3. Used DigitalOcean cloud to distribute data to the entire company


