## Group-4

## Team: Group 4 

## Team Members:

Bobby Szramel - [@RSzramel](https://github.com/RSzramel)

Pushpaja Katepalli - [@KPushpaja](https://github.com/KPushpaja)

Andrew Sheehan - 

Evan Voss - 

## Dataset: Warehouse and Retail Sales

 Source - Data.Gov

 Link - https://catalog.data.gov/dataset/warehouse-and-retail-sales
 
Description: This dataset contains a list of sales by the month and calendar year. This dataset is updated every month and records sales of liqour and alcohol. It contains a list of sales and movement data by item and department appended monthly. This shows the chain of sales between the Warehouse to retailers and the transfers. It helps the company track their highest purschasing retailers, sales trends, demand and make improvements according to their analysis. We picked this dataset to have an understanding of this industry and how the company uses this to their leverage. 

Dimensions:

- Rows: 308k

- Columns: 9

- Columns: year, month, supplier,item code, item description, item type, Retail sales, Retail transfers, and warehouse sales. 

- Data type: Most of the data is Numeric and Varchar. 

## Questions:

### Question 1: Which items and suppliers generate the highest liquor sales in Montgomery County, and how do these sales compare across different product categories?
 This question helps identify the top-performing products and suppliers in the county’s liquor market. Knowing which items sell the most provides valuable insights into consumer preferences, market demand, and supply chain performance.
 
 From an economic perspective, this analysis can inform procurement and inventory decisions, ensuring that high-demand products are well-stocked while reducing overstock of slower-moving items. It can also help the Department of Liquor Control and local retailers design targeted promotions or strategic partnerships with key suppliers to maximize sales and efficiency.
 
 From a cultural and social viewpoint, identifying the most popular types of alcoholic beverages can shed light on changing consumption patterns for example, whether customers are shifting toward local craft products, premium spirits, or specific categories like wine or beer.

You want to:
- Group sales by item and supplier

- Calculate total sales volume (from retail and warehouse)

- See which items and suppliers have the highest total sales

- Optionally, compare across item types (categories)

## Manipulations Added:

## Analysis and Results:

## Snowflake links:

- Question 1:

- Question 2: https://app.snowflake.com/us-east-1/ksc93446/#/warehouse_and_retail_q2-ddU2gzNYC
