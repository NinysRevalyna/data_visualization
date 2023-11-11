# DATA VISUALIZATION
# SUPERMARKET SALES
  Source Data : https://www.kaggle.com/datasets/aungpyaeap/supermarket-sales/data

## Business Understanding
  In the current business context, the expansion and proliferation of supermarkets within densely populated urban areas are on the rise. This growth is accompanied by heightened market competition among supermarkets. To gain valuable insights into the dynamics of this market and to make informed strategic decisions, a comprehensive analysis of historical sales data from a supermarket company is essential.

  The dataset under consideration encompasses sales records spanning three months and is derived from three distinct branches of the supermarket company. This dataset is particularly conducive to the application of predictive data analytics methods, offering a valuable opportunity to forecast trends, identify patterns, and derive actionable insights. Understanding the business landscape, market trends, and consumer behavior through data analysis is imperative for staying competitive, optimizing operations, and making informed business decisions in the dynamic and competitive supermarket industry.

## Data Understanding
- The dataset has 17 columns and 1000 rows
- The dataset comprises historical sales data from a supermarket company, offering insights into the trends and dynamics of the market. Here's a breakdown of the key variables present in the dataset :
  - Invoice id: Computer-generated sales slip invoice identification number.
  - Branch: Supercenter branches labeled as A, B, and C.
  - City: Location of the supercenters in different cities.
  - Customer type: Classification of customers into Members (those using a member card) and Normal (those without a member card).
  - Gender: Gender type of the customer.
  - Product line: General categorization of items, including Electronic accessories, Fashion accessories, Food and beverages, Health and beauty, Home and lifestyle, Sports and travel.
  - Unit price: Price of each product in dollars.
  - Tax: 5% tax fee applied to customer purchases.
  - Total: Total price, including tax.
  - Quantity: Number of products purchased by the customer.
  - Date: Date of purchase, recorded from January 2019 to March 2019.
  - Time: Purchase time, ranging from 10 am to 9 pm.
  - Payment: Payment method used by the customer for the purchase.
  - COGS (Cost of Goods Sold): The cost incurred by the supermarket in producing or purchasing the products sold.
  - Gross margin percentage: Percentage representing the gross margin.
  - Gross income: Gross income derived from sales.
  - Rating: Customer satisfaction rating on their overall shopping experience, measured on a scale of 1 to 10.
 
## Data Visualization and Story Telling
Looker Studio : https://lookerstudio.google.com/reporting/29649fd3-1f9f-4421-9a72-e6d101ea1d38

![image](https://github.com/NinysRevalyna/data_visualization/assets/72516143/f62d406d-ad8c-4368-9522-252532b76c02)

Based on the data, it can be seen that the residents of each city have different preferences for each product category. The residents of Naypyitaw tend to be more interested in the Food and Beverages category, with a percentage of 8.68% or 23,766, the residents of Yangon show a preference for Home and Lifestyle at 8.19% or 22,417, and the residents of Mandalay are more interested in Sports and Travel at 7.3% or 19,988.
     
![image](https://github.com/NinysRevalyna/data_visualization/assets/72516143/f52c9578-1b1e-4fa2-aeff-9905d3cd8f58)

Based on the data, it can be observed that female customers dominate both the member category, accounting for 27.29% or 88,146 customers, and the non-member or regular category, with a percentage of 24.69% or 79,735 customers.

![image](https://github.com/NinysRevalyna/data_visualization/assets/72516143/455fd07a-b551-47b1-976c-b941ff771baf)

Based on the data above, e-wallet payment is highly popular among customers, reaching 345 or approximately 34.5% of the total ID. Those using cash payment are about 344 or approximately 34.4% of the total ID, while credit card payments are slightly lower compared to e-wallet and cash, at around 311 or approximately 31.1% of the total Invoice ID.

![image](https://github.com/NinysRevalyna/data_visualization/assets/72516143/7299b097-2aad-4caf-8d2c-659eb61e11eb)

Based on the data above, it can be seen that Yangon has the highest total sales at 1,859 or 33.74%, followed by Naypyitaw at 1,831 or 33.23% dari total penjualan, and Mandalay has the lowest total sales at 1,820 or 33.03%.



