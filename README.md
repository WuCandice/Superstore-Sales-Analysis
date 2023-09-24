# Superstore Sales Analysis & Data Visualisation

Project description from HiCounselor website: [Link](https://hicounselor.com/projects/superstore-sales-analysis-data-visualisation)

![Image](https://user-images.githubusercontent.com/127648422/224529590-829d20b8-d812-416e-ba33-c11a11132d7f.png)


## EXECUTIVE OVERVIEW:
Superstore is a fictional retail company in the United States. They specialize in selling furniture, office supplies, and technology products. This summer, they hired me as a Business Intelligence Analyst at their Seattle office. My role is to identify weaknesses and opportunities in their marketing performance. My goal is to help them enhance their business growth and productivity.

### Business Questions:
- Which states and cities are generating the highest revenue?
- Which product category is both the best-selling and the most profitable?
- Which product sub-categories and specific products are top performers as well as those that are underperforming?
- Are there products that are frequently bought together?
- Which customer segment is bringing in the most profit?
- What is the most preferred shipping mode among our customers?
- How has the company's performance trended over recent months?
- What are the key performance indicators (KPIs) for Superstore?

## DATASET:
The dataset was sourced from the HiCounselor website. The dataset contains 9993 sales transactions that occurred from 2019 to 2022. It encompasses a wide range of information, including the specifics of the order, geographical information, and particulars about the products ordered. There are no missing values or any irrelevant data types and values. During the inspection process, one duplicate entry was identified and removed. Therefore, the dataset maintains full accuracy and integrity, making it suitable for further analysis. To view or download the cleaned dataset, you can check my repositories on GitHub.

## DASHBOARDS:
<img width="735" alt="Pasted Graphic 4" src="https://github.com/WuCandice/Superstore-Sales-Analysis/assets/127648422/6f8e47ec-6d6e-4e61-99ab-fbdff8f6568f">

### KPIs: 
Over the past four years, the superstore generated $2.3 million in revenue but had only a gross profit of $286.41K. Additionally, the company's average discount was 15.62%, indicating that the discounting strategy might have impacted the profit margin. The breakdown of profit margin in the discount category in the Financial Analysis dashboard will be examined later.

### Sales by Region and state:
The West region boasted the highest revenue, with sales amounting to $725K, followed by the East region with sales of $678K. Moreover, California, Washington, and New York were the top states that contributed the most revenue to the company. Therefore, the company should focus on marketing efforts and optimized inventory in these states to further enhance sales. 

The Central region, with sales of $501K, and the South, with sales of $392K, represented two regions that might have had untapped potential worth exploring.

### Sales vs. Profit by Category and Sub-Category:
The Technology category emerged as the leading performer in both sales and profit. Within this category, the Phones sub-category stood out with impressive sales and profit figures. On the other hand, the Furniture category showcased significant sales but had a notably lower profit margin. Within this category, the Tables sub-category displayed decent sales but operated at a loss. Additionally, both Bookcases and Supplies resulted in a negative profit for the company. These observations raise concerns, suggesting potential issues with the cost structure or pricing strategy, especially for the Tables, Bookcases, and Supplies subcategories.

### Customer Segments and Preferences
* Orders by Customer Segment:
The Consumer segment was the largest customer base. Superstores should create tailored marketing campaigns targeting this segment to enhance sales. The Corporate and Home Office segments with smaller customer bases, present growth opportunities with focused B2B strategies.
* Order by Shipping Preferences:
Most customers preferred Standard Class shipping, indicating they might prioritize cost savings over faster delivery. 
* Top Three Customers by Order:
Raymond Buch, Sean Miler, and Tamara Chand are our most frequent shoppers with max 6 orders for the past year. Superstore should conduct exclusive offers or a loyalty program, offer pricing adjustments for returning customers, collect and use customers' feedback to enhance their shopping experience, and keep them informed through educational content on social media, newsletters, and personalized content tailored to various customer segments.
<img width="734" alt="Pasted Graphic 5" src="https://github.com/WuCandice/Superstore-Sales-Analysis/assets/127648422/b36ed1ce-a0b8-48af-9cd4-70f728ece3db">

### insights: 
* Los Angeles and New York City consistently lead in sales, but while Los Angeles saw a slight decline in 2022, New York City surged. Seattle, on the other hand, experienced a significant rebound in 2022. 
* Philadelphia shows a promising upward trajectory, contrasting with the relatively stagnant sales in Houston and San Antonio. 	
* New York City and Los Angeles dominate in product quantities across all categories.
* Binders, Paper, and Phones are consistently popular across California, New York, and Texas.

<img width="734" alt="Pasted Graphic 6" src="https://github.com/WuCandice/Superstore-Sales-Analysis/assets/127648422/dbd145c2-85dd-438d-a970-f09ada20937a">

<img width="734" alt="Pasted Graphic 7" src="https://github.com/WuCandice/Superstore-Sales-Analysis/assets/127648422/cae76944-e6b7-4b8b-9add-45f0e0f2931e">

### insights

#### Top Performing Sub-Categories:
* Sales: "Phones" lead in sales, closely followed by "Chairs" and then "Storage".
* Discount: The "Binders" sub-category has the highest discount rate, which might impact its profitability. "Machines" and "Tables" also have significant discounts, which could be a strategy to boost sales but may also affect profit margins.
* Profit Margin: "Labels", "Paper", and "Envelopes" are the most profitable sub-categories in terms of profit margin percentage. This indicates efficient cost management for these products.

#### Top Products by Sales vs. Profit:
* The "Cisco TelePresence System EX90 Videoconferencing Unit" leads in sales, but its profit is not the highest among the top products. This suggests that while the product is popular, its cost structure or pricing might need revisiting.
* "Canon imageCLASS 2200 Advanced Copier" has a good balance of high sales and profit, indicating it's both popular and profitable.
* Some products, like the "Cubify CubeX 3D Printer Triple Head Print", despite having high sales, operate at a loss. This is a red flag and suggests a need for pricing or cost structure review.
* Products like the "High Speed Automatic Electric Letter Opener" and "Riverside Palais Royal Lawyers Bookcase, Royale Cherry Finish" have decent sales but minimal or negative profit, indicating potential inefficiencies.
   
<img width="338" alt="Screenshot 2023-09-20 at 22 08 05" src="https://github.com/WuCandice/Superstore-Sales-Analysis/assets/127648422/af9d6ad5-5ae1-4620-a7eb-afea5c2e541d">

#### Basket Items:
* The combination of products "FUR-FU-10003464" and "TEC-PH-10002496" are frequently bought together, with a support of 0.040%. This means that in 0.040% of all transactions, these two items are bought together.
* The confidence of 50.000% indicates that when "FUR-FU-10003464" is purchased, there's a 50% chance "TEC-PH-10002496" is also in the cart.
* The average lift of 4 suggests that "FUR-FU-10003464" and "TEC-PH-10002496" are four times more likely to be bought together than if they were purchased individually.

<img width="734" alt="Pasted Graphic 8" src="https://github.com/WuCandice/Superstore-Sales-Analysis/assets/127648422/7f8fe47f-2e23-44a9-8d10-117bffadf30c">

#### PVM by Category:
* Profit Drivers: The "Copiers" sub-category has the highest profit, followed by "Phones" and "Paper". These are the main profit drivers for the store.
* Concern Areas: The "Tables" sub-category is operating at a significant loss, and "Bookcases" have a minimal profit, indicating areas of concern that need attention.
* Price Impact: The "Binders" sub-category has seen a significant reduction in profit due to pricing, while "Copiers" and "Phones" have benefited from their pricing strategy.
* Volume Impact: "Storage" and "Phones" have seen a positive impact on profit due to volume, while "Machines" have been negatively impacted.
* Mix Impact: The "Binders" sub-category has benefited the most from the product mix, while "Envelopes" have been negatively impacted.
* New Products Impact: "Copiers" and "Phones" have seen a significant profit from new products, but "Machines" and "Tables" have been negatively impacted.
* Discontinued Products Impact: The discontinuation of certain products in the "Machines" and "Tables" sub-categories has led to a loss.

<img width="1086" alt="Screenshot 2023-09-22 at 20 53 30" src="https://github.com/WuCandice/Superstore-Sales-Analysis/assets/127648422/31bdbdcf-1e5c-4347-ba81-88804a233d38">

The table provides a breakdown of profits for various product sub-categories based on the discounts applied to them. The profits are presented for the current year (denoted as "AC") and the previous year (denoted as "PY").
* No Discount: The highest profit without any discount is seen in the "Copiers" sub-category, followed by "Phones" and "Paper".
* Up to 10% Discount: "Chairs" have the highest profit in this discount range.
* 10% to 20% Discount: The "Copiers" sub-category leads in profit, followed closely by "Phones" and "Paper".
* Greater than 20% Discount: Despite offering a hefty discount, the "Copiers" sub-category still manages to top in profit, but "Machines" and "Tables" are operating at a loss.
