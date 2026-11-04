# Gamezone Product Insights - Project Overview
## The goal of this project is to investigate the performance of Gamezone Company to surface recommendations that will help the product team make inventory decisions every month.
**Founded in 2016, Gamezone is a company that sells gaming electronic products to over thousands of customers. They sell new and refurbished products all around the world. They sell mostly through their online website, but they do also have a mobile app, and use a variety of marketing channels to find their customers.

Since they are strategising their inventory prioritisation decisions for the following months, they would like to build more understanding of the popularity of their products by assessing their customers' information.**

**In 2019, they launched a new set of marketing campaign categories** spanning topics like wellness tips, the affordability of their plans, and preventative care. 

## Dataset Structure
The dataset contains one table that includes information about product categories, marketing channels, regions, and customer demographics.

<img width="864" height="1222" alt="Gemini_Generated_Image_jbvogvjbvogvjbvo" src="https://github.com/user-attachments/assets/6e2f6f3c-fe94-4f3c-b8a6-20e6f0c58b08" />



## Insights Summary
#### To investigate gaming products, we focused on the following key metrics:

- **Sales**: The total monetary value of all successful purchases made within the selected timeframe.
- **Average Order Value **: The average amount of money a customer spends per order. Crucial for understanding customer purchasing behaviour, e.g are people purchasing cheap items or expensive bundles. 
- **Orders**: The total number of transactions or purchases that occurred. It tells the volume of business, regardless of how much each person spent.

#### Sales
- Across products, 27in gaming monitor, Nintendo Switch and Sony PS5 performed better than the other products, responsible for more than 75% of sales (84.8%).
- Within the three products with the highest sales, the LATAM region had relatively lower sales ($179k, $149k, $ 155k, respectively).
- 27in gaming monitor and Nintendo Switch showed high sales but had null regions (0.49%) – this needs to be investigated and could be due to missing data or issues with campaign tagging.


#### Average Order Value

- Across best-performing products by AOV, Sony PS5 and Lenovo Ideapad had the highest AOV, at nearly 5.8x and 3.9x the average, respectively.
- This high AOV is due to the NA and EMEA regions, which had by far the highest AOV across all product types (48.04%).
- Across all products, the LATAM region had the lowest AOV and also the lowest sales. Razor Pro Gaming Headset had zero sales, yet it had an AOV of $524 across regions; this needs investigation and could be due to missing data.

#### Orders
- Across products, Nintendo Switch had by far the highest number of orders (10,368), as well as the second-highest number of sales ($1,656k).
- This high order count is due to the NA (4,991) and EMEA (3,277) regions, which drove 16.9% of total orders.

## Recommendations
- Prioritise inventory and marketing for the 27in Gaming Monitor, Nintendo Switch, and Sony PS5. These three products drive nearly 85% of total sales. Securing stock and maintaining competitive pricing for these items is critical for overall revenue.    
- Targeted Regional Push: Implement targeted promotional campaigns in the LATAM region for the top three products. While these items perform globally, LATAM sales are lagging ($179k, $149k, and $155k) compared to other regions, representing a significant growth opportunity.
-Investigate the Razer Pro Gaming Headset, which shows zero sales but an anomalous AOV of $524. Similar to the high AOV for Sony PS5 and Lenovo Ideapad, this discrepancy should be audited to ensure data integrity and uncover potential high-value or bulk orders.
-  Address the wide gap between Nintendo Switch order volume (10,368 - the highest) and its sales rank (second). While NA and EMEA drove 16.9% of total orders, its relatively lower total sales ($1,656k vs. the Monitor's $1,969k) suggests a lower profit margin per unit. Explore bundling to increase the average basket size.
- Fix Data Quality issues: Urgently investigate the missing "null" region data associated with the 27in Gaming Monitor and Nintendo Switch (0.49%). This represents a significant portion of top-line revenue and will allow for more accurate regional targeting.
- Additionally, address the LATAM data gap, which consistently shows the lowest AOV and sales across all products.






