# Overview
ETL(or Extract, Transform, Load) is a data pipeline process that takes in new data, perform transformations, and loads the data into in a database. This project focuses on using the ELT process to create an automated pipeline that takes in movie data from Kaggle and Wikipedia, cleans the data, and outputs the data into an SQL server. Through this project, the data is transformed by wrangling data from similar columns into a single column (different language colums become a single "language" column), dropping rows with irrelevant information (such as tv series and duplicate rows), reformatting values to consistent form (ex. 01/01/2022 vs. January 1, 2022) and merging data sets to fill in missing values. This pipeline then uploads the cleaned data into an SQL server, that exists locally in pgAdmin. 


 
### Technology used
   - Jupyter Notebook 
   - pgAdmin (as SQL server)

**Note that due to size constraints of github, original data files were not uploaded to repository.

