# grab_restaurant_analysis
A data engineering project on extracting and transform dataset from a kaggle dataset on 16000 grab restaurant analysis
## Participants
Hassan Hosain, Hong Eng, Sailaja ,Rosni


Creating a python virtual environment do the steps below:
This is to install all python libraries in this virtual environment

1. Create a Python Virtual Environment: python -m venv venv
2. Activate the Python Virtual Environment: venv/Scripts/activate
3. Install the appropriate python libraries required for this project
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


