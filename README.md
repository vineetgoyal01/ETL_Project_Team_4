# Analyses for Housing prices of Greater Melbourne 

## The Notebooks should be run in the following order:

1. Notebook1_webscraping_API.ipynb
2. Notebook2_Housing_price_Data.ipynb
3. Notebook3_LGAs.ipynb
4. Notebook_4_Suburb_Housing_Price_data

# Summary of the project:

This ETL project relied on using different data sources to compare the median house price depending on where they lived in Greater Melbourne.

# This analysis was completed at two levels. 
            The first level was comparing the median house price of the suburb that they lived in within Greater Melbourne. 
            The second level of analysis involved conducting a similar comparison, but instead compared the Local Government Area within Greater Melbourne . 

# Sources:
      1) Domain API 
      2) https://en.wikipedia.org/wiki/Local_government_areas_of_Victoria
      3) https://knowyourcouncil.vic.gov.au/councils
      4) https://www.abs.gov.au/AUSSTATS/abs@.nsf/DetailsPage/1410.02014-19?OpenDocument

We used Domain API and different web sources to get the data. Imported the data into Jupyter Notebook. Than transformation of data with 4 notebook attached.
  
  Notebook1 and Notebook2 are for Extracting, Transforming and exporting of house price data for suburbs and LGAs
  Notebook3 and Notebook4 and for Extracting, Transforming and Loading of suburb/LGA popullation data and merging it with House price data
  
  Finaly we used pgAdmin to load it to SQL. We used sequential relational database as our tables are relationaly  structured.
  
  Please see the output PNG for a quick summary of the outcome.
  
  # Thank You.
