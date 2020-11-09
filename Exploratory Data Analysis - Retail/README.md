# Exploratory Data Analysis (EDA) on Sample Super Store

   This project is part of my internship, we have data of world's famous Sample Super Store. Our job is identify weak areas for this store and create interactive dashboard with the help of EDA.
   
![](Images/sample_super_store.png)

## Table of Contents
* Quick Overview on Dataset(#quick-overview-on-dataset)

## Quick Overview on Dataset
   Rather than checking for missing values, dublicate values, scatter plots and feature data types explicitly, I used profiling libaries like DataPrep and Pandas-Profiling. as they are quick and aims to give detailed information about dataset. 
 ### Have a look
  It shows that there is 8 categorical and 5 numeric features, no missing values, and 17 duplicate rows. At the same time it also showed that Country column is constant, therefore it's just taking up space in our dataset.
  
  <img src='Images/overview.png' width="500" /> <img src='Images/warnings.png' width="500" />
  
## Dashboard
I've used **jupyter notebook** and **Voila** to create interactive dashboard. I know it's not as cool as creating by Tablue, but it's also a good compititor and very light to use. And **Heroku** for the deployment. You can click below heroku icon or click [here](https://samplestore101.herokuapp.com) to see the dashboard on your fingertips.

<img src='Images/heroku.svg' width='80' />
  
