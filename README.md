![GitHub contributors](https://img.shields.io/github/contributors/katie-hu/Public_Safety)

# Welcome to the USD-ADS507 Team 7 Home Page!

### Public Safety
Our project is focused around the development of an ETL (extract, transform, & load) pipeline that starts with the extracting of data from public API data sources, of which have a focus around public safety and environmental awareness.

### Team Members
- Katie Hu: khu@sandiego.edu 
- Trevor Sauerbrey: tsauerbrey@sandiego.edu
- Grigor Tashchyan: gtashchyan@sandiego.edu



#### Set Up Requirements
This notebook is run using Python and SQL.
Keys: RapidAPI requires subscriptions to have keys to pull the requests.
For security purposes, it is recommended to save these keys in a configuration file. The file used in this design is named config.py

Following Libraries Needed:

numpy, pandas, config, pymysql, json, requests, warnings, getpass, mysql.connector, datetime, smtplib, ssl, email, mimetext, mimemultipart, boto3

Email Feature: 

This pipeline includes an automated email service. To use this part of the pipeline, you will need to have an email account and know the password. Within the code in the Jupyter Notebook, there is a troubleshooting section if the connection to your email errors. This is due to your email account settings. There is a step-by-step tutorial that will resolve these issues.
### Results
Final Output will be an automated email that will provide a daily update for Weather, Air Quality, and Covid-19 along with an Air Quality Index guide to understand the data.


#### Data Source Credits
Thank you to RapidAPI that provided the platform for the three APIs that were used in the creation of this pipeline.
