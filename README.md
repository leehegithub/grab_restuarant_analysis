# grab_restaurant_analysis
A data engineering project on extracting and transform dataset from a kaggle dataset on 16000 grab restaurant analysis
## Participants
Hassan Hosain, Hong Eng, Sailaja ,Rosni

* Extraction
1. First run the file Extract-api_kagglecall.ipynb and follow the instructions accordingly as you will need to download the kaggle.json file from your kaggle account.

* Transformation & Load
1. Run the reading_csv.ipynb to run the transformation and also load the dataframes into 4 tables in the postgresql data warehouse

* Analysis
- A portion of the analysis is done in the same reading_csv.ipynb
- Visualization is in power bi see visualization file
### Date 21-March-2024
Findings: From the cuisine table we found out there are establishments other than restaurants, which include marts, pet shops,health suppliments shops,toys & games shop etc.
### Decision taken:
Divide the data frame based on establishments into 3 tables- establishment_df, cuisine_df, delivery_df
## Details of establishment_df:(saila, Hong Eng)
id_source,name,address,latitude, longitude, opening hours,rating, reviews, location type
## Details of delivery_df:(ROSNI)
id_source,delivery_cost, radius, delivery_options, promo
##details of cuisine:(HUSSAN)
need to check
## Action to be taken
CLEAN address and opening hours,
delivery cost/100,
split cuisine column to table.

link to intrim project ppt at canva  https://www.canva.com/design/DAGBKTv81AQ/NU_B_3Db1EL5hFlgIMxJVA/edit?utm_content=DAGBKTv81AQ&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton
