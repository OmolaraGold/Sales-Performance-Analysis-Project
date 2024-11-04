# Sales-Performance-Analysis-Project

### PROJECT TITLE: SALES PERFORMANCE ANALYSIS FOR A RETAIL STORE. PROJECT 1

### PROJECT OVERVIEW
The primary objective of this project is to analyze the sales performance of a retail store to gain insights into top selling product, regional sales distribution, and sales trends over time. By identifying high-performing products, regions with strong or weak sales, this analysis aims to provide data-driven insights that support better decision-making in inventory, marketing, and sales strategy.

### DATA OVERVIEW
The data used in this analysis includes:
1. Products: A break down of each product, quantity sold and their revenue.
2. Regions: The geographical areas where the retail store operate. Which enables us to compare sales performance across locations.
3. Dates: The date in which a particular transaction was made. Which enable analysis on daily, monthly, quarterly or yearly bases.
4. Quantity: The number of unit sold per transaction.
5. Unit Price: The price of single unit of each product. It is used to compare similar product sold in different quantities.
6. Total Sales: The total monetary value generated from sales over a given period. Which helps with inventory management.

### KEY METRICS
- Total Sales Revenue: This is the total income generated from sales. It provide overall performance and its helps to track revenue growth.
- Sales Per Region: This is the total sales from each geographical location of the store. It helps to identifies high and low performing region.
- Sales Per Product: This is the total sales generated by each product. It helps to know which product has the most or least sales.
- Sales Trens: This is the general direction of sales overtime. It helps to understand seasonal impacts and peak.

### TOOLS USED
- Microsoft Excel [DOWNLOAD HERE](https//www.microsoft.com): For cleaning,analysis,and visualization of data. Pivot tables was use to summarize the data for easy interpretation. Charts were also created for virtual representation.
- SQL: This is Structured Query Language for Data Quering
- PowerBI: This is used for Data Visualisation 

### FORMULAR USED
``` Excel
Total sales =sum(quantity * unit price)
```
```sql
select * from [dbo].[salesperformance_project]
```

### VISUALIZATION
#### 1. TOTAL SALES BY PRODUCT
- PIVOT TABLE
 ![image](https://github.com/user-attachments/assets/3cfc1da4-d261-41fd-b280-d4aeebcf2a3d)
- CHART
![image](https://github.com/user-attachments/assets/ea3836ca-7395-4a1d-ab39-6a9a62c66a51)
- SQL QUERY
![SALES DATA PROJECT SQL QUE 1](https://github.com/user-attachments/assets/74abd1be-e254-4a44-8d5f-2313f2789b1b)
![SALES DATA PROJECT SQL QUE 3](https://github.com/user-attachments/assets/3f03151c-8599-490c-8852-5deaef47abf9)

#### DEDUCTION
The following can be deduce;
1. Shoes is of high demand, indicating that customers prioritize footwear over other items. This could mean either the market for shoes is larger or that the brand or style of shoe being sold are most preferred by people.
2. The marketing around shoes might be stronger. They could be promoted more effectively, either through store layout, advertising, or digital marketing.
3. The low sales of socks could suggest an opportunity to increase bundle deals or promotions to encourage customers to buy socks along with shoes.
4. The low sales in socks could also be issues in pricing, stock levels, or even quality perceptions.
Examining customer feedback or comparing pricing against competitors might offer insights into why socks are underperforming. Offering unique designs, better quality, more advertisment around socks might increase sales.
#### 2. REGION BY TOTAL SALES
- PIVOT TABLE
![image](https://github.com/user-attachments/assets/f204bb77-b511-46ba-9156-e73288b030ec)
- CHART
![image](https://github.com/user-attachments/assets/844e1d71-e9c9-4b88-ada3-51006e657103)
![image](https://github.com/user-attachments/assets/4f5c9776-da0c-4aea-8dac-f5d30a6697c9)
- SQL
![SALES DATA PROJECT SQL QUE 7](https://github.com/user-attachments/assets/146a1d97-7ca6-4f15-80b5-4ea7923a53ab)

#### DEDUCTION
The following can be deduce from the above visuals;
The South region has the highest total sales with 4.675 millions out of 10.587 millions.
1. The company might have invested more in marketing efforts in the South region and this could be driving higher sales.
2.  The prices of the product might be more appealing in the South. Discounts or region-specific offers can increase sales. It would be helpful to examine whether the South has benefited from any price adjustments.
3.  High turn over in the south might also be as a result of better stock availability and more accessible sales channels.
4.   Lower competition in the South could be allowing the products to stand out more, contributing to higher sales.
The west region has the lowest total sales with 1.512 millions out of 10.587 millions. This might be as a result of;
1. Low purchasing power as a result of higher price and fewer discounts in the West region could be reducing sales. More and frequent discount sales can help boost sales in this region.  
2. If products are less available or there are fewer distribution points in the West, it might make it harder for customers to purchase. More distribution points with regular avaliability of products might help.
3. If the West region has higher competition with many similar products this could be drawing potential customers away. Analyzing competitor performance and market saturation in the West could reveal if this is a factor.
4.  If demand is low, this could mean that the products offered aren't resonating with the West region's demographic. Consider whether product adjustments or targeted marketing could align better with this region's interests.
#### 3. REGION YEARLY SALES
- PIVOT TABLE
![image](https://github.com/user-attachments/assets/8bae1070-8e43-4cad-a9e8-2e9f7c55a71d)
- CHART
![image](https://github.com/user-attachments/assets/3371fdb0-cd92-4c9f-b2de-0d635315e172)
![image](https://github.com/user-attachments/assets/bf121fdb-474f-451f-be9d-6f1718234ad9)
- SQL
![SALES DATA PROJECT SQL QUE 5](https://github.com/user-attachments/assets/119daf85-69d9-4577-ba08-ce79c29a64e8)

#### DEDUCTION
1. There is a noticeable decline in total revenue across East and South regions from 2023 to 2024. This suggests potential challenges in sales performance or market conditions affecting revenue generation. There is an increase in total revenue across the North and West regions.
a. East: The East region had the highest revenue in 2023 but shows a significant drop in 2024. This decline may indicate market saturation or increased competition in the region.
b. South: The revenue for this region appears to have decreased slightly, indicating a potential area of concern which could suggest challenges in maintaining sales. Although it remains one of the higher-performing region.
c. North and West regions: Both regions show an increase in revenue figures. And more marketing and advertisement is needed to boost more sales revenue in these regions.
Focusing on marketing and customer engagement strategies may be necessary to revitalize sales in declining regions.


### POWERBI VISUALIZATION
Below is powerBI dashboard that visualizes the insights found in excel and SQL.
![SALES DATA  PROJECT VISUAL](https://github.com/user-attachments/assets/3e10087b-3afb-4f6d-adc9-bc83de0ee89a)













