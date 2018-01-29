# Item-Stock-Management
About the Project:

In this project I  have  developed a web based application for the Item Stock Management module of Item inventory and warehouse location management application. Brief details of all the modules and description of Item inventory and warehouse location management application. are give below.
Item inventory and warehouse location management application is a web based application to automate the entire process of recording warehouse location details for the pharmaceutical, healthcare products and medical supplies:

Components of this Application: 

A)Item Inventory/Stock management - This component maintains an inventory/stock of the items. 
There are 3 main types of items:
1.Pharmaceutical drugs( tablet/capsule, syrup)
2.Health and Personal care products (Soap, moisturizer, lotion, gel, antiseptic   
Medical supplies and Equipments(surgical, life support, diagnostic like X-ray machines,Ultrasound, medical monitors like Blood pressure, ECG)

B)Warehouse Location management - This component maintains the active locations for the items.
1.Easy Lookup - This component allows the user to search the items and track its location history quickly.
2.User Administration - This component maintains a list of authorized users for the project (Authorized users: administrator and company staff).
3.Reporting and Analysis - This component allows the user to generate reports and perform analysis on the item stock and its movement across locations.



Item Stock Management Module Details:

In this project I have create  Database for Item Stock and Used MVC architectural Pattern. 
The following are the compontents of the UserInterface.
Add Item- The user should be able to add the following details of an item. 
Item Code - Number - A unique value to identify the item, should be autogenerated
Item Name - Text (Eg Dr. Assure Blood Pressure Monitor)
Unit  - Kg/mg/ml/pcs depending upon the category (Eg 250 ml, 50 mg, 100 pcs)      
Beginning Inventory - This field records the initial quantity of the item when the item first arrives the warehouse
Quantity on Hand - The current total stock on hand. 
Price per Unit - Should be stored as Rupees
Date Of Manufacture-Date Format of Manufacturing date
Date of Expiry-Date Format of Expiry Date.
Location - An item can be stored in any of the three locations ‘Bulk Zone’, ‘Pick Zone’, ‘ Distribution Center’
Item Category - Should be one of the values ( Pharma Drug, Health and Personal care, Medical Supplies and Equipment)	
Item Sub Category - Should be one of the values as given
Search Item - Displays the details of a particular item or all items.
Delete Item - Allows the user to delete an item. The item cannot be deleted if it is stored in a location.
Edit Item - Allows the user to edit all the details except Item code and Location of an item.