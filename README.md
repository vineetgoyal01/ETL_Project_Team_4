# ETL_Project_Team_4

## **The Notebooks should be run in the following order:
1. Notebook1_webscraping_API.ipynb
2. Notebook2_Housing_price_Data.ipynb
3. Notebook3_LGAs.ipynb

## **Important Notes and Function of each Notebook
## Notebook 1 Summary and Important Notes:
1. This notebook uses both web-scraping and API functions to obtain a dataset of the Local Government Areas (LGAs) in Greater Melboure, suburbs within those LGAs and the median prices of suburbs. 
2. Web-scraping is initially used to obtain a table of LGAs from Wikipedia. The next step is using the web-scraped table to obtain the sububrs in each LGA in Melbourne using the Local Council Website. This is converted into a Pandas Dataframe
3. The last step is then using the web-scraped table to interact with the Domain API to obtain the median price of houses in all suburbs within Greater Melbourne. This data is then also aggreggated by LGA so there are two separate csvs exported as a result of this process
4. This Jupyter Notebook imports four API keys from the config file. Please note that there are limits on API keys so the code cannot run successfully more than once a day unless new API keys from Domain are obtained.  Thus, please wait until at least August 20 to run this code. 

## Notebook 2 Summary and Important Notes 
1. Notebook 2 uses the median price csv obtained in Notebook 1 and interacts the suburban data with demographic data from the ABS. Thus, this notebook uses the new data-source of abs data. 
2. Once this transformation is complete, the csv exported at the end and this csv is uploaded into the pgAdmin4 site. 

## Notebook 3 Summary and Important Notes 
1. Notebook 3 is created based on the .csv file obtained from the ABS census data. It is then cleaned to obtain the data in the year 2016 with respective LGAs using the list provided by Wikipedia. 
2. Once this transformation is complete, the csv is exported at the end. 
