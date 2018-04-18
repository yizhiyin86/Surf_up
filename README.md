## Surf Up
<p>Used SqlAlchemy to create a database to store weather inforamtion in Honolulu, Hawaii;</p>
<p>Queried the data from database, analyzed the data by PANDAS and offered visualization using matplotlib</p>
<p>Used FLASK APP to render the data to a webpage</p>

### Step1. Data Cleaning and database engineering
<li>Input: Two csv files with Hawaii weather and station information in the directory /Resources</li>
<li>Script: Used Pandas and SQLAlchemy to clean data and create database to store the data</li>
[Jupyter notebook script is here](https://github.com/yizhiyin86/Surf_up/blob/master/data_engineering_and_database_engineering.ipynb) <br />
<li>Output: Two cleaned csv files and hawaii.sqlite stored in the output directory </li>
[I'm an inline-style link](https://www.google.com)
### Step2. Data retrieving, analysis and visualization
<li>Input: Retreieved data from the database created at Step1 </li>
<li>Script:[Jupyter notebook script](Climate_Analysis_and_Exploration.ipynb)</li>
<li>Output: Data Visualizations as below</li>
<p>  12 months of precipitation from queries</p>
![Precipitation Plot](/output/precipitation.png?raw=true "Precipitation of the last 12 months")

### Step3. Use Flask APP to render the information retrieved from Database 
<li>Input: Retreieved data from the database created at Step1</li>
<li>Script: [A markdown of the script is here](Flask_API.md) </li>
<li>Output: Rendered info when run Flask, examples of some screenshots are here</li>
![Flask Welcome](output/Flask_API_welcome.png?raw=true "Welcome page")
![Start date and end date weather information](output/Flask_API_Start_End.png?raw=true "Welcome page")


