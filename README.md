# Superstore Sales Analysis & Data Visualisation

Project description from HiCounselor website: [Link](https://hicounselor.com/projects/superstore-sales-analysis-data-visualisation)

![Image](https://user-images.githubusercontent.com/127648422/224529590-829d20b8-d812-416e-ba33-c11a11132d7f.png)


## EXECUTIVE OVERVIEW:
Superstore is a fictional retail company based in the United States. They specialize in selling furniture, office supplies, and technology products. This summer, they hired me as a Business Intelligence Analyst at their Seattle office. My role is to identify weaknesses and opportunities within their business. My goal is to help them enhance their business growth and profitability.

### Business Questions:
- Which states and cities are generating the highest revenue?
- Which product category is both the best-selling and the most profitable?
- Which product sub-categories and specific products are top performers as well as those that are underperforming?
- Are there products that are frequently bought together?
- Which customer segment is bringing in the most profit?
- What is the most preferred shipping mode among our customers?
- How has the company's performance trended over recent months?
-  What are the KPIs?

## DATASET:
The original dataset was obtained from the HiCounselor website. It contains 9993 sales transactions that occurred from 2019 to 2022. This dataset encompasses a wide range of information, including order specifics, geographical data, and product-related data. There are no missing values or any irrelevant data types and values. During the inspection process, a duplicate entry was identified and removed for accuracy. For those who are interested in viewing or downloading the refined dataset, it is available in my GitHub repository.

## DASHBOARDS:
<img width="1080" alt="Screenshot 2023-09-23 at 23 47 55" src="https://github.com/WuCandice/Superstore-Sales-Analysis/assets/127648422/bd3fb6ee-09f2-42f5-b7fa-5cd1b1fe366d">


### KPIs: 
Over the past four years, Superstore generated $2.3 million in revenue but only had a gross profit of $286.41K. The company's average discount stood at 15.62%, suggesting that the discounting strategy might have influenced the profit margin. A detailed breakdown of the profit margin within the discount category will be explored later in the Financial Analysis dashboard.

### Sales by Region and state:
The West region boasted the highest revenue, with sales amounting to $725K, followed by the East region with sales of $678K. Within those two regions, California, Washington, and New York were the top states that contributed the most revenue to the company. Therefore, the company should focus on marketing efforts and optimizing inventory in those states to further increase sales. 

The Central region with sales of $501K, and the South with sales of $392K, represented two regions that might have had untapped potential worth exploring.

### Sales vs. Profit by Category and Sub-Category:
The Technology category emerged as the leading performer in both sales and profit. Within this category, the Phones sub-category stood out with impressive sales and profit figures. On the other hand, the Furniture category showcased significant sales but had a notably lower profit margin. Within the Furniture category, the Tables displayed decent sales but operated at a loss. Additionally, both Bookcases and Supplies resulted in a negative profit for the company. These observations raise concerns, suggesting potential issues with the cost structure or pricing strategy, especially for the Tables, Bookcases, and Supplies subcategories.

### Customer Segments and Preferences
* Orders by Customer Segment:
The Consumer segment was the largest customer base. Superstore should create tailored marketing campaigns targeting this segment to increase sales. The Corporate and Home Office segments with smaller customer bases, present growth opportunities with focused B2B strategies.
* Orders by Shipping Preferences:
Most customers preferred Standard Class shipping, indicating that they might prioritize cost savings over faster delivery. 
* Top Three Customers by Order:
Raymond Buch, Sean Miler, and Tamara Chand were the most frequent shoppers with a max of 6 orders for the past 4 years. This pattern suggests a potential gap in customer loyalty. To address this, Superstore could introduce exclusive offers and a loyalty program, adjust pricing for regular customers, and actively seek their feedback to refine the shopping experience. Engaging customers through educational content on social media, newsletters, and tailored content for different segments could further foster loyalty and retention.

<img width="1082" alt="Screenshot 2023-09-23 at 23 50 06" src="https://github.com/WuCandice/Superstore-Sales-Analysis/assets/127648422/72d17110-9e96-469f-a701-6214307d11bf">

* Top Three Cities by Sales Over Time:
Los Angeles and New York City consistently lead in sales, but while Los Angeles saw a slight decline in 2022, New York City surged. Seattle, on the other hand, experienced a significant rebound in 2022. 
* Bottom Three Cities by Sales Over Time:
Philadelphia shows a promising upward trajectory, contrasting with the relatively stagnant sales in Houston and San Antonio. 	
* Top 10 Cities by Quantity:
New York City and Los Angeles dominate in product quantities across all categories.
* Quantity by Sub-Category and State:
Binders, Paper, and Phones are consistently popular across California, New York, and Texas.

<img width="1081" alt="Screenshot 2023-09-23 at 23 50 34" src="https://github.com/WuCandice/Superstore-Sales-Analysis/assets/127648422/3e021c3c-68a0-427e-aa34-b71783e004f9">

* Segment by Sales and Profit Over Time:
Sales across all segments had increased year-over-year, with the Consumer segment leading the growth. The Home Office segment was smaller, yet it showed a significant increase in sales in 2022. Profit trends mirror the sales trends, but it's noteworthy that the Corporate segment's profit in 2022 didn't grow proportionally to its sales.
* Ship Mode by Sales and Profit Over Time:
Standard Class remains the dominant shipping mode in terms of sales and profit, However, while sales for Standard Class increased in 2022, its profit decreased. First Class and Second Class have seen substantial growth in 2022. 
* Profit by Segment and Category
The Consumer segment dominates in profit in Technology. This suggests that consumer-oriented tech products might be the most profitable items. Furniture is the least profitable category across all segments, indicating potential areas for cost optimization or pricing adjustments.
* Top 10 Cities by Orders
New York City and Los Angeles had the most orders, highlighting their importance to Superstore's overall sales success.

<img width="1083" alt="Screenshot 2023-09-23 at 23 51 12" src="https://github.com/WuCandice/Superstore-Sales-Analysis/assets/127648422/809c29a4-21e9-48c3-b366-b103228f9015">

#### Top Performing Sub-Categories:
- Phones, Chairs, and Storage are the top three sub-categories in sales.
-  Binders, Machines, and Tables sub-categories have the highest discount rate, which might impact their profitability. 
-  Labels, Paper, and Envelopes are the most profitable sub-categories, which indicates that the cost of goods sold was lucrative for those products.

#### Top Products by Sales vs. Profit:
- The "Cisco TelePresence System EX90 Videoconferencing Unit”,  "Cubify CubeX 3D Printer Triple Head Print",  “High-Speed Automatic Electric Letter Opener" and "Riverside Palais Royal Lawyers Bookcase, Royale Cherry Finish" showcased decent sales, but negative profit, indicating inefficiencies.
- "Canon imageCLASS 2200 Advanced Copier" had a good balance of high sales and profit, indicating it's both popular and profitable.

<img width="338" alt="Screenshot 2023-09-20 at 22 08 05" src="https://github.com/WuCandice/Superstore-Sales-Analysis/assets/127648422/af9d6ad5-5ae1-4620-a7eb-afea5c2e541d">

#### Basket Items:
* The items "FUR-FU-10003464" and "TEC-PH-10002496" are often bought together, appearing in 0.04% of all transactions. If a customer buys "FUR-FU-10003464", there's a 50% chance they'll also buy "TEC-PH-10002496". Their combined purchase likelihood is four times higher than when bought separately.

<img width="796" alt="Screenshot 2023-09-23 at 23 45 43" src="https://github.com/WuCandice/Superstore-Sales-Analysis/assets/127648422/ac9f6e1a-e823-416e-baf6-b5d646f5f17b">

#### PVM by Category:
* Profit Drivers: The "Copiers" sub-category had the highest profit, followed by "Phones" and "Paper". These were the main profit drivers for the store. The "Tables" sub-category was operating at a significant loss, and "Bookcases" had a minimal profit, indicating areas of concern that need attention.
* Price Impact: The "Binders" sub-category had seen a significant reduction in profit due to its price, while "Copiers" and "Phones" had benefited from their pricing strategy.
* Volume Impact: "Storage" and "Phones" had seen a positive impact on profit due to volume, while "Machines" have been negatively impacted.
* Mix Impact: The "Binders" sub-category has benefited the most from the product mix, while "Envelopes" have been negatively impacted.
* New Products Impact: "Copiers" and "Phones" have seen a significant profit from new products, but "Machines" and "Tables" have been negatively impacted.
* Discontinued Products Impact: The discontinuation of certain products in the "Machines" and "Tables" sub-categories has led to a loss.

<img width="1085" alt="Screenshot 2023-09-23 at 23 51 52" src="https://github.com/WuCandice/Superstore-Sales-Analysis/assets/127648422/76ead2aa-6c61-46ab-8b69-0a3dd68a1cce">

The table provides a breakdown of profits for various product sub-categories based on the discounts applied to them. The profits are presented for the current year (denoted as "AC") and the previous year (denoted as "PY").
* No Discount: The highest profit without any discount is seen in the "Copiers" sub-category, followed by "Phones" and "Paper".
* Up to 10% Discount: "Chairs" have the highest profit in this discount range.
* 10% to 20% Discount: The "Copiers" sub-category leads in profit, followed closely by "Phones" and "Paper".
* Greater than 20% Discount: Despite offering a hefty discount, the "Copiers" sub-category still manages to top in profit, but "Machines" and "Tables" are operating at a loss.
