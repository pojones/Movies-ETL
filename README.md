# Movies-ETL
## Overview
The goal of this analysis was to create a data pipeline that extracts, transforms, and loads. The process was broken down into four parts to simplify troubleshooting. The ETL function itself is comprised of multiple nested functions that are called in a single instance using three variables, each set to the relevant datasets. 
## ETL_function_test
-	This first section reads our webscraped data into dataframes for analysis. 
-	We can easily display the dataframes to ensure everything translated properly.
## ETL_clean_wiki_movies
-	This section introduces another function that removes distinction on language and combines similar genres between tables.
-	It also expands on our ETL function, and adds other operations that further clean the data.
## ETL_clean_kaggle_data
-	The ETL function gets further operations to clean the data extracted from Kaggle by removing unwanted columns and filling missing values. 
-	Once the dataframes are cleaned, they are merged.
## ETL_create_database
-	This final function loads the merged and cleaned data to tables in a SQL database. 
