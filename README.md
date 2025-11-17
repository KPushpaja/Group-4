## Group-4

## Team: Group 4 

## Team Members:

Bobby Szramel - [@RSzramel](https://github.com/RSzramel)

Pushpaja Katepalli - [@KPushpaja](https://github.com/KPushpaja)

Andrew Sheehan - [@ASheehan](https://github.com/AndrewSheehan1234)

Evan Voss - [@evanv5](https://github.com/evanv5)

## Dataset: Warehouse and Retail Sales

 Source - Data.Gov

 Link - https://catalog.data.gov/dataset/warehouse-and-retail-sales

 <img width="676" height="248" alt="image" src="https://github.com/user-attachments/assets/da53fadd-9ed8-4a5c-b6ec-ea71f44a27b1" />

Description:

This dataset contains a list of sales by the month and calendar year. This dataset is updated monthly and records liquor and alcohol sales. It includes a list of sales and movement data by item and department appended monthly. This shows the chain of sales between the Warehouse and retailers, along with the transfers. It helps the company track their highest purchasing retailers, sales trends, demand, and make improvements according to their analysis. We picked this dataset to have an understanding of this industry and how the company uses it to its advantage. 

Dimensions:

- Rows: 307,646

- Columns: 9

- Columns: Year, Month, Supplier, Item code, Item description, Item type, Retail sales, Retail transfers, & Warehouse sales. 

- Data type: Most of the data is Numeric and Varchar. 

## Questions:

### Question 1: Which items and suppliers generate the highest liquor sales in Montgomery County, and how do these sales compare across different product categories?
 This question helps identify the top-performing products and suppliers in the county’s liquor market. Knowing which items sell the most provides valuable insights into consumer preferences, market demand, and supply chain performance.
 
 From an economic perspective, this analysis can inform procurement and inventory decisions, ensuring that high-demand products are well-stocked while reducing overstock of slower-moving items. It can also help the Department of Liquor Control and local retailers design targeted promotions or strategic partnerships with key suppliers to maximize sales and efficiency.
 
 From a cultural and social viewpoint, identifying the most popular types of alcoholic beverages can shed light on changing consumption patterns, for example, whether customers are shifting toward local craft products, premium spirits, or specific categories like wine or beer.

You want to:
- Group sales by item and supplier

- Calculate total sales volume (from retail and warehouse)

- See which items and suppliers have the highest total sales

- Optionally, compare across item types (categories)

### Question 2: What seasonal trends exist across monthly liquor sales throughout the entire year, and how do these patterns vary from year to year?
This question helps identify seasonal trends across monthly liquor sales throughout the year and how these patterns vary from year to year. Understanding these trends provides valuable insights into consumer behavior, peak demand periods, and potential fluctuations in supply needs. 

From an economic perspective, this analysis can inform inventory management, staffing, and promotional strategies by highlighting months with higher or lower sales. It also allows the Department of Liquor Control and local retailers to plan targeted marketing campaigns, seasonal promotions, or supplier agreements that align with consumer demand cycles. 

From a cultural and social viewpoint, recognizing seasonal consumption patterns can reveal shifts in customer preferences, such as increased demand for certain beverage types during holidays, summer, or special events, and can guide decisions on product offerings or special events.

You want to:
- Group sales by month and year

- Calculate total sales volume (from retail and warehouse) per month


- Identify peak and low sales months and compare them across years


- Optionally, break down by item type or category to see if trends differ by product

## Manipulations Added:
- Question 1: For question 1, the only manipulations were changing the item code data type from number to varchar because it was not only numbers in the data. The other calculation that was used throughout question 1 was combining retail sales and warehouse sales in order to get total sales. This allowed us to visualize the sales as a whole rather than as separate groups.

- Question 2: For Question 2, there were simple calculations and aggregations. Additionally, we utilized GROUP BY and ORDER BY functions to sort the data, primarily by YEAR and MONTH. The calculations were simple, dealing with finding total sales and calculating percentages.

## Analysis and Results:

<img width="849" height="381" alt="image" src="https://github.com/user-attachments/assets/40fdf54a-19bf-4f8e-9563-5442d220b987" />

<img width="1824" height="885" alt="image" src="https://github.com/user-attachments/assets/2ee49c4d-fc0f-49bb-9b88-3bf2821dc69b" />

This shows which item type was the most profitable and which products are the most profitable. We solved for the total sales revenue and total sales for each category.. We could change our supply according to the result and continue to work with the most profitable suppliers. 

<img width="1011" height="425" alt="image" src="https://github.com/user-attachments/assets/2caa2f12-afc7-44ce-889a-b8cd908338bc" />

<img width="1401" height="571" alt="image" src="https://github.com/user-attachments/assets/6fd1af56-88ca-47a9-a0bf-1eac8758743a" />

These results help us understand that if there is a correlation between seasons and sales, and which seasons have a huge impact on the industry and the demand surges during festive seasons. This shows that the company could concentrate on promoting their products during the rest of the year. The sales during the year 2019 was the highest and the warehouse sales were always comparatively higher than the retail sales.  Both of our questions help the company improve sales as we understand the demand and concentrate the marketing efforts of the industry to improve sales. They also help us understand how the industry work and the market trends in the industry. 

## Snowflake links:

- Question 1: https://app.snowflake.com/us-east-1/ekc66140/#/question-1-dOnCEB8zk

- Question 2: https://app.snowflake.com/us-east-1/ksc93446/#/warehouse_and_retail_q2-ddU2gzNYC
