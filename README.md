# mini ETL
# Inventory and orders last-30-days
API connection with WMS and OMS (Shipedge) platform that brings the current inventory to each client (fulfillment) to formulate the rotation of the products (SKU) in the last 30 days that are being stored.  

It was necessary to iterate through each client and browse the JSON response of the orders to obtain the information of interest.

# Google sheet
After extracting the data, these are stored in a google spreadsheet where after each inventory update and subsequent advances the days, the information is rewritten in the spreadsheet

# Tableau
Finally, the google spreadsheet serves as the database for a tableau view that will provide up-to-date inventory information to stakeholders or as a way to communicate analytical findings.

![WhatsApp Image 2022-06-28 at 11 13 12 AM](https://user-images.githubusercontent.com/70334697/177383054-15a773f1-f275-4b06-8378-b8f288460be3.jpeg)
