# ANALYSIS OF GLOBAL ONLINE RETAIL SALES: PRODUCT PERFORMANCE, MARKET CONTRIBUTION AND SALES TREND


<img width="208" height="101" alt="Capture" src="https://github.com/user-attachments/assets/148f7f44-d895-4043-a4dd-1fc2f5d13d2d" />


## Introduction
In today’s data-driven business environment, organizations rely on data analytics to gain insights into performance, customer behavior, and market trends. This project focuses on the analysis of a global e-commerce retail dataset to evaluate sales performance and identify key factors influencing revenue generation.
Using Microsoft Excel as the primary analytical tool, the dataset was explored through PivotTables and visualizations to uncover patterns in product performance, geographic distribution of sales, customer demand, and time-based trends. The insights derived from this analysis are intended to support informed decision-making and improve overall business strategy.
 
## Objectives
The main objective of this project is to analyze sales data to generate actionable business insights. Specifically, the study aims to:
-	Identify top-performing products by revenue
-	Analyze sales contribution by country
-	Examine the relationship between quantity, price, and revenue
-	Identify high-demand products
-	Evaluate monthly sales trends and seasonality
## Methodology
- **Data Collection:** Sales records were compiled from the company’s database.
- **Data Cleaning:** Duplicate entries and errors were corrected to ensure accuracy.
- **Data Analysis:** Pivot tables were created to summarize total sales by product, category, and region.
- **Visualization:** Bar charts, line chart and pie charts were generated to illustrate trends and performance.
- **Interpretation:** Findings were analyzed to extract meaningful insights

  **Question 1**. Which Products Generate the hiest Total Revenue?

<img width="309" height="233" alt="image" src="https://github.com/user-attachments/assets/49541ade-f947-44f6-bee5-204541892b8a" />
<img width="784" height="418" alt="image" src="https://github.com/user-attachments/assets/ec39dc4c-d842-4927-b25b-a26c9cba9f41" />


The main Objective here is to Identify and evaluate the top-performing products based on total sales revenue.
The PivotTable analysis, sorted in descending order of total sales and filtered to highlight the top five products, reveals that revenue generation is concentrated among a small number of items.
The product REGENCY CAKESTAND 3 TIER recorded the highest sales revenue at 286,486.30, followed by WHITE HANGING HEART T-LIGHT HOLDER with 252,072.46. Other notable contributors include PAPER CRAFT, LITTLE BIRDIE, Manual, and JUMBO BAG RED RETROSPOT, all of which generate substantial revenue but at lower levels compared to the top two products.
The accompanying bar chart reinforces these findings by providing a clear visual comparison of product performance. The chart shows a distinct ranking pattern, with REGENCY CAKESTAND 3 TIER having the tallest bar, followed closely by WHITE HANGING HEART T-LIGHT HOLDER, while the remaining products display progressively shorter bars. This visual representation makes it easier to observe the differences in revenue contribution among the top products.
### Business Insight
- Both the PivotTable and bar chart confirm that revenue is highly concentrated among a few key products
- The top two products stand out as major revenue drivers
- Visual analysis enhances understanding by making performance gaps immediately noticeable
#### Key Observation
The noticeable gap between the leading products and others suggests a reliance on a limited number of high-performing items for revenue generation.



**Question 2.** Which Country Contribute the Most to total Sales

<img width="309" height="204" alt="image" src="https://github.com/user-attachments/assets/68f9b61f-a25e-430b-8904-f1597627c0aa" />
<img width="764" height="450" alt="image" src="https://github.com/user-attachments/assets/e4d019aa-cff3-41b2-9369-421389c2828d" />


**Result Interpretation (Question 2)**
The main Objective is here to Analyze the geographic distribution of sales to determine key markets contributing most significantly to overall revenue.
The PivotTable analysis, sorted in descending order and filtered to highlight the top contributing countries, reveals a significant imbalance in revenue distribution across markets.
The United Kingdom stands out as the dominant market, generating 14,723,147.52 in total sales, which represents the largest share of overall revenue. Other countries such as Eire (621,631.11), Netherlands (554,232.34), Germany (431,262.46), and France (355,257.47) contribute comparatively smaller amounts.
The accompanying bar chart visually reinforces this disparity. The bar representing the United Kingdom is significantly taller than all others, clearly illustrating its overwhelming contribution to total sales. In contrast, the bars for the other countries are much shorter, indicating relatively lower revenue contributions and making the gap between the primary market and others immediately visible.
### Visual Insight from the Chart
- A clear dominance of one country (UK)
- A large gap between the UK and other markets
- Other countries contribute moderately and relatively evenly compared to the UK
 #### Business Insight
The business is heavily reliant on the United Kingdom market. 
Other markets, while present, contribute only a small fraction of total revenue.
**There is an opportunity to:**
- Expand internationally
- Strengthen underperforming markets
 ### Observation
The significant difference in bar heights highlights a high level of market concentration, which may pose a risk if the primary market experiences a decline.




**Question 3.** What is the relationship between quantity sold and total sales?		

Corelation Matrix showing the relationship between quantity sold and price		
						
		
<img width="833" height="931" alt="image" src="https://github.com/user-attachments/assets/a30a578b-7dc7-44be-bd88-2d7507c62e52" />

    
**Result Interpretation (Question 3)**
 The Objective is to Examine the relationship between sales volume (quantity), revenue, and price to understand key drivers of business performance.
The PivotTable analysis comparing total quantity sold and total sales revenue across products reveals that high sales volume does not always correspond to high revenue.
For instance, WORLD WAR 2 GLIDERS ASSTD DESIGNS recorded the highest quantity sold (109,169 units) but generated relatively low revenue (24,905.87), indicating a low-priced, high-volume product. In contrast, WHITE HANGING HEART T-LIGHT HOLDER achieved both high quantity (93,640 units) and high revenue (252,072.46), suggesting a strong balance between demand and pricing.
Further examples reinforce this pattern:
BROCADE RING PURSE shows high quantity but very low revenue, indicating low unit price
ROTATING SILVER ANGELS T-LIGHT HLDR generates relatively high revenue from moderate quantity, suggesting a higher-priced product.

To further investigate this relationship, a correlation analysis was conducted between quantity and price. The result produced a correlation coefficient of -0.0049, indicating an extremely weak negative relationship between the two variables.
This result suggests that there is no significant linear relationship between price and quantity sold. In other words, changes in price do not strongly influence the quantity purchased within this dataset.

#### Business Insight
Sales performance is influenced by a combination of:
- Quantity sold (demand)
- Price per unit
However, price alone does not determine demand.
Products can achieve:
- High quantity with low revenue (low-priced items)
- High revenue with moderate quantity (higher-priced items)


**Question 4.** which Products are sold in the hiest quantity?	

<img width="309" height="204" alt="image" src="https://github.com/user-attachments/assets/ac65e831-1a61-4406-9777-555ab7a31141" /><img width="708" height="422" alt="image" src="https://github.com/user-attachments/assets/8abfc5b0-4165-4dff-81e6-42255f4a59ac" />


**Result Interpretation (Question 4)**
The Objective is to Assess product demand by identifying items with the highest sales volume.
The PivotTable analysis, sorted in descending order and filtered to highlight the top five products by quantity sold, indicates that demand is concentrated among a select group of items.
The product WORLD WAR 2 GLIDERS ASSTD DESIGNS recorded the highest sales volume with 109,169 units, followed by WHITE HANGING HEART T-LIGHT HOLDER (93,640 units) and PAPER CRAFT, LITTLE BIRDIE (80,995 units). Other high-demand products include ASSORTED COLOUR BIRD ORNAMENT and MEDIUM CERAMIC TOP STORAGE JAR, contributing significantly to total quantity sold.

The accompanying pie chart visually represents the proportion of total quantity contributed by each of these top products. Each slice illustrates the relative share of demand, with WORLD WAR 2 GLIDERS ASSTD DESIGNS occupying the largest portion of the chart, indicating its dominance in sales volume.

#### Visual Insight from the Chart
The pie chart clearly shows how total demand is distributed among top products
The largest slice represents the most demanded product
Differences in slice sizes highlight relative demand levels

#### Business Insight
A small number of products account for a large share of total sales volume.
These products are key to:
- Customer engagement.
- Frequent transactions.
High demand products should be:
- Consistently available
- Closely monitored in inventory


**Question 5.** How do sales vary over Time?

<img width="309" height="407" alt="image" src="https://github.com/user-attachments/assets/575b540b-3926-4642-82fc-6eedebdd1f82" /><img width="700" height="433" alt="image" src="https://github.com/user-attachments/assets/5859f635-487b-472f-82f0-2c34a6bd8481" />

**Result Interpretation (Question 5)**

To Evaluate sales trends over time to identify patterns, seasonality, and potential growth opportunities.
The PivotTable and corresponding line chart reveal clear monthly variations in sales performance, indicating that revenue is not evenly distributed throughout the year.
Sales begin at a moderate level in January (569,445.04) and decline in February (447,137.35). From March onward, revenue shows a gradual upward trend, with some fluctuations, reaching higher levels in May (678,594.56) and June (661,213.69).
A more significant increase is observed in the later months:
September (952,838.38) marks a sharp rise
October (1,039,318.79) continues the upward trend
November (1,161,817.38) records the highest sales of the year
However, sales drop noticeably in December (518,210.79), indicating a post-peak decline.

 **Trend from the Line Chart**
The line chart visually confirms this pattern:
- A gradual increase in sales over time
- A strong peak toward the end of the year (Sep–Nov)
- A sharp decline after the peak

#### Business Insight
- Sales exhibit a clear seasonal pattern
- The peak sales period is in Q4 (especially November)
- Early months (Jan–Feb) and December show relatively lower performance

 #### Key Analytical Observation
The sharp increase from September to November suggests a high-demand season, possibly driven by promotions, holidays, or increased customer activity.
The drop in December may indicate post-peak demand reduction or stock limitations.

#### Findings
Top Products: Certain products consistently generated higher sales. 
Category Insights: Some categories outperformed others, reflecting customer preferences.
 Regional Trends: Sales distribution varied by region, with some areas contributing more revenue. 
Proportional Contributions: Pie charts revealed the percentage contribution of each product and category to total sales

#### Recommendations
Based on the findings from the analysis, the following recommendations are proposed:
1. Focus on High-Performing Products
- Increase inventory levels for top revenue-generating products
- Prioritize these items in marketing and promotional campaigns
2. Expand Market Reach
- Reduce over-reliance on the United Kingdom by exploring growth opportunities in other countries
- Develop targeted strategies to improve sales in underperforming regions
3. Optimize Pricing Strategy
- Review pricing for high-volume, low-revenue products
- Introduce strategies to improve margins, such as bundling or price adjustments
4. Strengthen Inventory Management
- Ensure consistent availability of high-demand products
- Use demand insights to avoid stockouts or overstocking
5. Leverage Seasonal Trends
- Increase stock and marketing efforts ahead of peak periods (especially September–November)
- Introduce promotions during low-sales periods (e.g., January, February, and December)

#### Conclusion
The analysis demonstrates the value of using pivot tables and charts to understand sales performance and customer preferences. Visual insights from this study enable management to make informed, strategic decisions, optimize sales strategies, improve customer satisfaction, and maximize revenue.


Author
- Kor Isaac Tersue
- Analyst.
- Email: isaachimself03@gmail.com
- Phone. 09036589441














