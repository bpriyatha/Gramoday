# Gramoday_Assignment

Dataset available on:
url='https://agmarknet.gov.in/SearchCmmMkt.aspx?Tx_Commodity=24&Tx_State=UP&Tx_District=1&Tx_Market=0&DateFrom=01-January-2020&DateTo=31-December-2020&Fr_Date=01-January-2020&To_Date=31-December-2020&Tx_Trend=0&Tx_CommodityHead=Potato&Tx_StateHead=Uttar+Pradesh&Tx_DistrictHead=Agra&Tx_MarketHead=--Select--'

Steps to run the file:
1. Open the Code in Google Colab
2. Download the data from the url mentioned above->'Export to excel'
3. Upload the .xls file to the colab in \content\ folder in 'files' section (or) change the data file path in the code accordingly.
4. Run the code by clicking Rull all from the 'Runtime' in the menubar.

Note: All the dependencies used are present in the colab by default

Code flow is as follows:
1. Data is separation based on Markets
2. Filling Data of Missing Dates using methods like Padding and Backwardfill
3. Spliiting of the Data: Out of 366 days, Train-test-split ratio is 300:66
4. Model defining,training and optimising.
5. Prediction of test data
6. Visualizing the test data

Refer to the word document below for Part-b and Part-c:
https://docs.google.com/document/d/1mpeHKe6X1RWF3O9f-rUfSCEH0Py-XXoN_pEWIOJ-UJY/edit?usp=sharing

[Bindu_Priyatha_Gramoday_Assignment.pdf](https://github.com/bpriyatha/Gramoday_Assignment/files/6415839/Bindu_Priyatha_Gramoday_Assignment.pdf)
