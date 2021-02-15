# Car Review: Project Overview
* Work in progress repository for the car review project
* Scraping information from **https://www.parkers.co.uk/ using python and BeautifulSoup
* Cleaning of obtained data using Pandas
* Performing Exploratory Data Analysis using matplotlib and seaborn
* TO FINISH: ml model for natural language processing on user's reviews 

## Code and Resources Used 
**Python Version:** 3.8 
**Packages:** pandas, numpy, sklearn, matplotlib, seaborn, beautifulsoup, csv 

## Web Scraping
Python Script to scrape PUT_NUMBER user car reviews from parkers.co.uk
With each review, I got the following:

* model : manufacturer/model/version
* user_score : user score from 0 to 5
* user_name 
* date_review 
* small_review : shortened review, only PUT NUMBER OF CHARACTERS
* full_review 

for tracking purposes: 
* ix : position of the review in relation to the car model
* link_review : specific link of each car version 

N.B. I purposely decided not to clean the data during scraping for two reasons: on the one hand, not to burden the programme so that it would be faster, and on the other hand, to combine data cleaning in one notebook to increase the clarity of the methods used.

## Data Cleaning
After scraping the data, I needed to clean it up so that it was usable for the visualization part and the machine learning model. 
I made the following changes and created the following variables:

*	
*	 
*	  

## EDA
I have displayed the main variables to better understand the composition of the dataset.
The visualisations mainly include the distribution of the various models.
Below are a few highlights. 

PUT IMAGES SAMPLE

## Model Building 


## Model performance

## Final thoughts and future improvements
