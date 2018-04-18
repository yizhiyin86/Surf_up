## Surf Up
<p>Used SqlAlchemy to create a database to store weather inforamtion in Honolulu, Hawaii;</p>
<p>Queried the data from database, analyzed the data by PANDAS and offered visualization using matplotlib</p>
<p>Used FLASK APP to render the data to a webpage</p>

### Step1. Data Cleaning and database engineering
<li>Input: Two csv files with Hawaii weather and station information in the directory /Resources</li>
<li>Script: Used Pandas and SQLAlchemy to clean data and create database to store the data</li>
<li><a href="https://github.com/yizhiyin86/Surf_up/blob/master/data_engineering_and_database_engineering.ipynb">Jupyter notebook script is here</a></li>
<li>Output: Two cleaned csv files and hawaii.sqlite stored in the output directory </li>

### Step2. Data retrieving, analysis and visualization
<ul>
<li>Input: Retreieved data from the database created at Step1 </li>
<li><a href="https://github.com/yizhiyin86/Surf_up/blob/master/Climate_Analysis_and_Exploration.ipynb">Jupyter Notebook for Data Retrieving, Analysis and Visualization</a></li>
<li>Output: Data Visualizations as below</li>
  <ul>
  <li> A plot of the 12 months of precipitation from queries</li>
    <img src="/output/precipitation.png" alt="Precipitation of the last 12 months">
   <li> A histobgram of the last recorded 12 months of temperature observation data (tobs) from the most activate weather station </li>
    <img src="/output/tobs_hist_last_year_recorded.png" alt="A histobgram of the last recorded 12 months of temperature observation data">
    <li> I plan to take a trip from date 1 to datae 2, what is the average temperature around this time last year in Hawaii?</li>
    <img src="/output/trip_ave_temp.png" alt="bar graph of the average temperature of selected dates last year">
  </ul>
 </ul>
 
### Step3. Use Flask APP to render the information retrieved from Database 
<ul>
<li>Input: Retreieved data from the database created at Step1</li>
<li><a href="https://github.com/yizhiyin86/Surf_up/blob/master/Flask_API.md">A markdown of Flask_API.py is here</a></li>
<li>Output: Rendered info when run Flask, examples of some screenshots are here</li>
  <ul>
  <li> Flask Welcome Page</li>
    <img src="/output/Flask_API_welcome.png" alt="Welcome page">  
  <li> Start Date and End Date Weather Summary Page</li>
    <img src="/output/Flask_API_Start_End.png" alt="Start and end date weather summary page">  
  </ul>
</ul>

