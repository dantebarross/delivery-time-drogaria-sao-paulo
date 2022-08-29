# Delivery time in Drogaria São Paulo

In this project, I've calculated how many motoboys each Drogaria São Paulo (drugstore) will need to contract, based on:
- Its daily working hours.
- How many deliveries this drugstore is receiving daily.

To do that, I've used Google API, searching Drogaria São Paulo all over São Paulo, SP, Brazil. Then, I've calculated, for each drugstore, travels from 1.5km to 15km, in four directions (north, south, east, west), getting the mean of everything. This gave me the average time travel by delivery.

You can consult the query and feature engineering in jupyter notebook. The .csv file contains the data collected. The .html file contains pinpoints representing the location of drugstores consulted.
