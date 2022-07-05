# Inventory-orders-last-30-days
API connection with WMS and OMS (Shipedge) platform that brings the current inventory to each client (fulfillment) to formulate the rotation of the products
in the last 30 days that are being stored.  

It was necessary to iterate through each client and browse the JSON response of the orders to obtain the information of interest.

#Google sheet
After extracting the data, these are stored in a google spreadsheet where after each inventory update and subsequent advances the days, the information is rewritten in the spreadsheet

#Tableau
Finally, the google spreadsheet serves as the database for a tableau view that will provide up-to-date inventory information to stakeholders or as a way to communicate analytical findings.
