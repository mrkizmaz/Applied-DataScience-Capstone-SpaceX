# Applied Data Science Capstone - SpaceX

> This repository is the final project of the <a href="https://www.coursera.org/professional-certificates/ibm-data-science" target="_blank">IBM Data Science</a> course I took from the online education platform Coursera.
<br/>Thanks for all the support and encouragement for all Coursera teams!

**Purpose of the repo:** Real-time dashboard application using the data of SpaceX, a space transportation company, under the roof of the materials I acquired during the whole course.

*You can review the **pdf** file that I have prepared with the application details <a href="https://drive.google.com/file/d/1pUt-anU0elJrcOk_J7hrLEn6YrqRRCl-/view?usp=sharing" target="_blank">here.</a>*

### Valuable knowledge gained in the course:
- Data Science Methodology
- Python Structure and Fundamentals
- Data Analysis with Python
- Data Visualization with Python
- Machine Learning with Python
- Databases and SQL for Data Science <br/>

Additionally, I had the opportunity to use **IBM Cloud Services** throughout this course.

### CONTENTS
1. [Data Collection][data_col]: In this file, data collection is performed by making a get request to the SpaceX API. It also includes some basic data editing and formatting.
2. [Web Scraping][web_scrap]: Web scrap Falcon 9 launch records with `BeautifulSoup`:
    - Extraction a Falcon 9 launch records HTML table from Wikipedia
    - Parsing the table and convert it into a Pandas data frame
3. [Data Wrangling][data_wrang]: Performing exploratory data analysis and determine training labels
    - Exploratory Data Analysis
    - Determining Training Labels
4. [EDA with SQL][eda_sql]: Using this Python notebook;
    - Understanding the Spacex DataSet
    - Loading the dataset into the corresponding table in a Db2 database
    - Executing SQL queries to answer assignment questions
5. [EDA Data Visualization][eda_vis]: Performing exploratory data analysis and feature engineering using `pandas` and `matplotlib`
    - Exploratory Data Analysis
    - Preparing Data Feature Engineering
6. [Launch Site Location][site_loc]: This lab contains the following stages:
    - Marking all launch sites on a map
    - Marking the success/failed launches for each site on the map
    - Calculating the distances between a launch site to its proximities
7. [Machine Learning Prediction][ml_pred]: Performing exploratory data analysis and determine training labels;
    - Creating a column for the class
    - Standardization the data
    - Spliting into training data and test data
    - Finding best Hyperparameter for SVM, Classification Trees and Logistic Regression
        - To find the method performs best using test data
8. [Dashboard - SpaceX][dash]: Real-time dashboard creation using all collected and processed datasets with Python libraries `dash` and `plotly`.


[data_col]: https://github.com/mrkizmaz/Applied-DataScience-Capstone-SpaceX/blob/main/01_jupyter-labs-spacex-data-collection-api.ipynb
[web_scrap]: https://github.com/mrkizmaz/Applied-DataScience-Capstone-SpaceX/blob/main/02_jupyter-labs-webscraping.ipynb
[data_wrang]: https://github.com/mrkizmaz/Applied-DataScience-Capstone-SpaceX/blob/main/03_labs-jupyter-spacex-Data%20wrangling.ipynb
[eda_sql]: https://github.com/mrkizmaz/Applied-DataScience-Capstone-SpaceX/blob/main/04_jupyter-labs-eda-sql-coursera.ipynb
[eda_vis]: https://github.com/mrkizmaz/Applied-DataScience-Capstone-SpaceX/blob/main/05_jupyter-labs-eda-dataviz.ipynb
[site_loc]: https://github.com/mrkizmaz/Applied-DataScience-Capstone-SpaceX/blob/main/06_lab_jupyter_launch_site_location.ipynb
[ml_pred]: https://github.com/mrkizmaz/Applied-DataScience-Capstone-SpaceX/blob/main/07_SpaceX_Machine%20Learning%20Prediction_Part_5.ipynb
[dash]: https://github.com/mrkizmaz/Applied-DataScience-Capstone-SpaceX/blob/main/spacex_dash_app.py
