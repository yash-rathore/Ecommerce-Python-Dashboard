# Ecommerce-Python-Dashboard
VISIT : https://datapane.com/u/yash3/reports/q34OKeA/e-commerce-report/ TO GET COMPLETE VISUALISATION AND USER INTERACTION FOR THE REPORT

------------------------------
What is a Dashboard in Python?
------------------------------
A dashboard is a collection of plots and images organized with a certain layout. 
There are two ways to create a Plotly dashboard: using the online creator or programmatically with Plotly's python API. 
In Plotly, dashboards can contain plots, text and webpage images.

-----------------
What is Datapane?
-----------------
Datapane is a Python library for building interactive reports for your end-users in seconds. 
Import our library into your existing script/notebook and build reports programmatically by wrapping components such as:
Pandas DataFrames
Plots from Python visualization libraries such as Bokeh, Altair, Plotly, and Folium
Markdown and text
General files, such as images, PDFs, JSON data, etc.

Datapane reports are flexible and can also contain pages, tabs, drop downs, and more. Once created, reports can be uploaded 
to the web, dynamically generated in the cloud, or embedded into your own application, where your viewers can interact with 
your data and visualizations. 

-------------
Requirements:
-------------
datapane library python
datapane user account to acquire api token and server url
pandas
numpy 
plotly
datetime
matplotlib

Before getting started, you will need your API token, which you can find on your settings page. If you are on a private 
Datapane instance, you will find it in /settings on your instance domain(i.e. https://[your-instance].datapane.net/settings).
Once you have you token, add it to the form field in the cell below to login to Datapane.

If you are using Datapane Community, set the datapane_server_url as https://datapane.com. Alternatively, if you are using a 
Teams instance, enter the URL of your instance (i.e. https://[your-instance].datapane.net).

--------
Database
--------
One .xls file and one .csv file which includes various superstores across US and all the details associated with the store, 
for example order ID, order date , ship date , customer ID ,segment , country and city , state, product name , sales, quantity
discount , profit across the year 2014-2017. Database files are provided with the script (.ipynb). Database files are , namely
"Sample - Superstore.xls" and "superstore_orders.csv".

--------------
About the code
--------------
1. Setting up the colab environment , loading in your personalised API token and server url
2. Importing and pip installing requirements
3. Reading the database files, ordering them and manipulating them to get in order for implementation
4. Sorting for every dataframe by year , month ,day of week and day to get a user interactive dashboard for later.
5. Analyzing database and making bar graphs , line graphs,point graphs , pie charts, heatmaps for every category , 
every city , state, country and divided by different categories.
6. Building a datapane report: using series of Plotly. Making dropdown menues using layout components of datapane report.
7. We have used the Page block to add multiple pages to our report, so the user can choose whether to view the forecast or the 
exploratory data analysis
8. Uploading report associated with the data on Datapane account of user using API token.
