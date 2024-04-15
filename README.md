# grab_restuarants_analysis
A data engineering project of a 16000+ Grab Restaurants in Singapore dataset from Kaggle, focusing on ETL.

## A Junior Data Engineer Program Project
## Participants
Lee Hong Eng, Hassan Hosain, Sailaja ,Rosni

* Extraction
1. First run the file Extract-api_kagglecall.ipynb and follow the instructions accordingly to download the kaggle.json file from your kaggle account.

* Transformation & Load
1. Run the reading_csv.ipynb to run the transformation and also load the dataframes into 4 tables in the postgresql data warehouse

* Analysis
- Visualization with Power bi - see visualization.pbix
- Visualization with Python - see reading_csv.ipynb

Date 21-March-2024
Findings: From the cuisine table we found out there are establishments other than restaurants, which include marts, pet shops,health suppliments shops,toys & games shop etc.
Decision taken:
Divide the data frame based on establishments into 4 tables- establishment_df, openinghour_df, cuisine_df, delivery_df

### Details of establishment_df:(saila) 
id_source,name,address,latitude, longitude, opening hours,rating, reviews, location type
### Details of openinghour_df:(Hong Eng) 
id_source,opening hours
### Details of delivery_df:(Rosni) 
id_source,delivery_cost, radius, delivery_options, promo
### details of cuisine:(HUSSAN)

### To note: 
delivery cost/100,
split cuisine column to table.
