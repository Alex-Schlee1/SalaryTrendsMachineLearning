# Salary Trends for Machine Learning- Project Overview
### Project Goal: Get insights about the job market for Machine Learning Engineers in England
* Scraped job information from Indeed.com using Python and Selenium
* Saved results in a csv file and manipulated and worked with the data using the pandas package



### Code and Resources
* Python Version: 3.7
* Environment: Jupyter Notebook
* Packages: selenium, matplotlib, seaborn, numpy




## Step 1- Scraping Data with Selenium
* Job Title
* Company name
* Location
* Salary
* Job description
<img src='/image1.png' width=700>


### Output in pandas after scraping
<img src='/image2.png' width=600>


## Step 2- Data Cleaning and Feature Engineering
After scraping the data and storing it in csv and pandas, I had to do some cleaning steps like:
* remove rows where salary information is not availabe(before cleaning: 794 job entries, after cleaning: 211 job entries; data loss of more than 70(!))
* Changed the currency from '£' to '$'
* Extracted salary range entries (min, max) and created a new column with the average value
* Changed salary entries to numeric data
* Created different columns for chosen skills and checked if they were mentioned in the job description column ('1'=Skill required, '0'= Skill not required

  *Python Skills
  *R Skills 
  *Java Skills
  *AWS Skills
  *Hadoop Skills
  *SQL Skills 
  *Spark Skills
  *R Skills 
  *Matlab Skills
  *Tensorflow Skills 
  *NLP Skills


