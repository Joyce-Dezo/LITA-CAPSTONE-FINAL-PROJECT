## LITA-CAPSTONE-FINAL-PROJECT
This repository contains Excel workbook, SQL scripts, Data visualization, and reports for analyzing customers demographics, purchasing choices and preferences. the goal is to provide insights for marketing strategies and customer engagements.

### Sales_ Data_ Respository
Sales Data refers to the quantitative and qualitative information related to sales transactions, customer interactions, and revenue generations.
This aspect consist of the;
OrderID: A unique identifier assigned to each cistomer order, typically used to track and manage ordeera throughout the entire sales process(e.g 1001).

Customer ID: Unique identifer for the customer.

Subscription Type: Type of Subscription plan chosen (e.g monthly,quarterly,yearly).

OrderDate:Date when the subscription became active or cancelled.

Product: A produc is a tangible or intangible item that meets the needs or wants of customers(e.g shirts, shoes etc).

Region: A geographical area that can be defined by various criteria( North,South,East,West).

Quantity: The amount or numbers of units of a product or item (Discrete quantity,continous quantity, decimals numbers).

Unit Price: Also known as Price per unit, is the cost of a single unit of a product or service(Total sales/quantity).

Total sales: Represents the entire aggregate vale of all sales transactions within a specified period of time( Sum= unit price * quantity sold.


### SQL CODE FOR SALES DATA
SELECT TOP (1000) [OrderID]
      ,[Customer_Id]
      ,[Product]
      ,[Region]
      ,[OrderDate]
      ,[Quantity]
      ,[UnitPrice]
      ,[Total_sales]
  FROM ['LITA_Capstone Dataset'].[dbo].[LITA Capstone SalesData]






#### CUSTOMER_DATA
Customer Data refers to the information collected about customers, including demographics, behaviours, preferences and interactions.
This aspects consists of the following; 
CustomerID: Unique identifier for the customer

Cudtomer Name: This is a very crucial piece of information  that identifies a customer.

Region: A geographical area that can be defined by various criterias.

Subscription Type: Type of subscription plan chosen(e.g monthly, quaterly or yearly).



















