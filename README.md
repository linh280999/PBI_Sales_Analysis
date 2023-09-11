# PBI_Sales_Analysis
Data Modelling, choosing the right visualizations to perform different metrics and using proper structure to tell a story, which is actionable and provide insightful facts and recommendations to meet requirements of stakeholder (Sale Department)
# Table of contents
1. Introduction
2. Apply design thinking mindset
3. Process
4. Insight & Recommendation
# Introduction
## 1. Business Context
Adventure Works Cycles, a large, multinational manufacturing company,  produces and distributes metal and composite bicycles to North American, European,  and Asian commercial markets. While its base operation is located in Bothell,   Washington, and employs 500 people, several regional sales teams are located throughout the company’s market region. 
After a successful fiscal year, Adventure Works Cycles is looking to broaden its  market share by focusing its sales efforts on the company’s best customers. The sales teams have identified the following requirements that will enable them to perform their jobs better:
### Customer segmentation and profiling:
- What are the early warning signs of problems? 
- Who are the best customers across all product lines? With whom should the sales team focus its efforts for building long-term relationships? 
- What are customers’ issues, categorized according to demographic groups (geographic location, revenue history, and so on)?
- What products are the customers buying and at what rate?
### Sales performance:
- When analyzing the insights of Sales Performance, the manager will comprehend the trend of the performance of each region through time series analysis, and recognize the region as either the potential one or not. Then, they will be supported to make good decisions for business strategies.
## 2. Dataset
Dataset: adventureworks2019 (public Google BigQuery dataset)
Dataset dictionary: Please reach file "Data Dictionary" attached above
Dataset access:
- Log in to your Google Cloud Platform account and create a new project.
- Navigate to the BigQuery console and select your newly created project.
- In the navigation panel, select "Add Data" and then "Star a project by name".
- Enter the project name "adventurework2019"
# Apply Design Thinking Mindset
## 1. Empathize
![image](https://github.com/linh280999/PBI_Sales_Analysis/assets/144362005/cd3c46ab-18f9-4065-8280-30395814a0f1)
## 2. Define point of view
![image](https://github.com/linh280999/PBI_Sales_Analysis/assets/144362005/7a94d08d-4503-4d0d-860d-054ff30e2e3d)
## 3. Ideate
![image](https://github.com/linh280999/PBI_Sales_Analysis/assets/144362005/16d208e1-90a2-4857-b775-d5ad5dbbf662)
## 4 & 5. Prototype & Review
![image](https://github.com/linh280999/PBI_Sales_Analysis/assets/144362005/cb5383f8-37c4-46b1-b39e-07b4368c370f)
# Process
## 1. Connect data to PBI and modelling
* Get data by connect Big Query to Power BI
* Select the necessary table 
* Using Power Query to edit and clean data. Transform the HTML document into formatted text
* Connect them based on primary key (Modelling)
![image](https://github.com/linh280999/PBI_Sales_Analysis/assets/144362005/63b6326a-cc7e-4156-a26b-8f59eba3c26b)
## 2. Build dashboard
* Using DAX to create measures and calculated columns
* Build 3 report pages
### Sale overview
![image](https://github.com/linh280999/PBI_Sales_Analysis/assets/144362005/c883fa0a-27f8-48e8-81aa-5c456eedcd31)
### Customer Analysis
![image](https://github.com/linh280999/PBI_Sales_Analysis/assets/144362005/8c8e7ddf-7657-4a8f-99a6-1c6cf09033a2)
### Sale by product
![image](https://github.com/linh280999/PBI_Sales_Analysis/assets/144362005/1281a0fc-b375-45ac-bd95-1a0ae4f5abe2)
# Insight & recommendation
## 1. Insight
### Sale overview
During the period 2011-2014, the business had 19,000 customers with more than 31,000 orders, the number of products ordered was more than 275,000 thousand, revenue was more than 110 million USD, profit was 9.37 million USD, the profit was 9.37 million USD. profit ratio was 8.53%

Annual growth rate reached 22.34%

Sales value increased steadily over the years, however, in 2011 sales value increased quarterly, but in 2012 and 2013 it increased steadily until the third quarter then decreased in Q4 (Q4/2012 decreased by 19.91%, Q4/2013 reduced by 4.54%)

Sales value tend to increase quarterly but profits are very low, especially in 2012 and the first half of 2013, profits were almost non-existent.

The best-selling item is Bike, accounting for 86.2%

Most of the orders are placed through sales person (accounting for 73.27%), the remaining orders are placed by customers themselves online, accounting for 26.73%.

US is the market bringing in the most revenue (57.35%), following by CA (14.89%) and AU (9.7%), and GB, FR, DE (with respective proportions is 6.98%, 6.60%, 4.47%)
### Customer

The majority of customers are over 55 years old, accounting for 74.56%. The number of male and female customer is not too different, male customers contribute slightly more sales value than female customers.

The proportion of customers by age group in different markets is similar: Over 70% are customers over 55 years old, 22-26% are customers from 36-55 years old, the rest are the remaining age groups, and the younger the customer, the less sales value are generated

Income groups 50001-75000 and 25001-50000 are the two groups that spend the most, accounting for 30.42% and 29.25% respectively. Both income groups have the highest proportion of customers over the age of 55

Bicycles are the best-selling items among all age groups, with groups under 17 mainly buying jewelry and clothes.
### Product
The best-selling subcategory is Road Bike (more than 44 million bikes) and Mountain bike (more than 37 million bikes)

Low-selling products are chains (more than 9 thousand), pumps (14 thousand), locks (16 thousand),...

Touring bikes, mountain bikes, road bikes are the 3 products with the highest discount percentage (47.67%, 33.88%, 13.22%) respectively.
## 2. Recommendation
Warning: Due to the decrease in revenue in the Q4/2012 and the Q4/2013, the company should pay attention in the Q/2014 to avoid this situation.

Market expansion: The goal is to develop the CA and AU potential markets first, then maintain and develop the US market (although the US market accounts for the largest proportion of sales value, the quarterly growth rate is not high as the AU market and not as profitable as the CA market) and invest in stimulus programs in DE, FR, GB to develop the market

Invest in stores and sales teams as well as customer service because more than 70% of orders are placed through sales people.

The company should focus on segmenting customers aged 36-55, and over 55 years old, regardless of gender, with average income levels (about 25001-50000, and 500001-75000) (pays special attention to the group of customers over 55 years old), these two age groups have average income levels, even at higher income levels, this age group is also the majority

The 3 best selling items are Touring bikes, mountain bikes, and road bikes have the highest discount percentage => Sales are still growing over the years => Temporarily limit the implementation of discounts on these key products (Touring bikes, mountain bikes, road bike) to optimize revenue and use other concept of marketing instead

The company should not focus on the younger because the company is just in the market expansion phase, profits from business activities are not high, there is even a negative period so should not spend money on development and product innovation to serve customers that account for a small proportion (3%). However, it is possible to maintain sale value of this group by maintaining the accessories product line, which costs the least, has the highest profit margin, and is suitable for younger that is the price-sensitive group.

