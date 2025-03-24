# EDACO-S-CUSTOMERS-SHOPPING-TREND-ANALYSIS
EDACO’S CUSTOMERS SHOPPING TREND ANALYSIS FOR THE YEAR 2023
![EDACO’S CUSTOMERS SHOPPING TREND - DASHBOARD](https://github.com/user-attachments/assets/5b9aad6a-13cd-43dd-aa48-35f817508ea8)

2. INTRODUCTION
This report presents an analytical review of Edaco’s customers shopping trend for the year 2023. The data-driven insights provided in this report aim to highlight inventory optimization, payment method preferences and market performance. The dashboard serves as a visual representation of various sales metrics and provides a comprehensive overview of the business's financial health and operational success.
2.1 Purpose of The Project
The purpose of this project is to analyze and understand customer shopping trends for EDACO in the year 2023. By examining purchasing behaviors, preferred payment methods, best-selling products, and customer preferences, this analysis aims to provide data-driven insights that can inform business decisions, optimize inventory management, and enhance customer satisfaction
2.3. Objectives
The main objectives of this analysis are:
	To identify the top-selling items and categories.
	To determine the most preferred product sizes and colors.
	To analyze customer purchase locations and trends.
	To evaluate the most commonly used payment methods.
	To assess customer feedback based on review ratings.
	To provide actionable insights to improve sales strategies and customer experience.

2.3. Problem Being Addressed
Retail businesses often struggle with inventory optimization, payment method preferences, and customer satisfaction due to a lack of clear insights into shopping trends. This project addresses the following challenges:
	Lack of clarity on best-selling products, leading to inefficient stock management.
	Uncertainty regarding customer preferences for sizes, colors, and product categories.
	Difficulty in identifying the most effective payment methods for customer convenience.
	Limited understanding of customer feedback and review ratings.
By addressing these challenges, EDACO can streamline its operations, reduce costs, and enhance customer satisfaction.

2.4. Key Dataset and Methodologies
Key Dataset
The dataset used for this analysis includes:
	Product purchases: Number of purchases for different items, sizes, colors, and categories.
	Geographical distribution: Locations with the highest purchase activities.
	Payment methods: Preferred payment channels such as PayPal, credit card, and bank transfer.
	Customer review ratings: Ratings given to different products.
	Sales distribution: Analysis of the best-selling items and categories.
Methodologies
	Data Collection: The data was gathered from EDACO’s sales and transaction records for the year 2023.
	Data Processing & Visualization: The data was cleaned, aggregated, and visualized using dashboards and graphical representations.
	Trend Analysis: Key metrics such as most purchased items, top locations, and preferred payment methods were analyzed.
	Statistical Insights: Review ratings and size/color preferences were examined to understand customer satisfaction and buying behavior.

3.0 STORY OF THE DATA
3.1 Data Source
The dataset used for this analysis was downloaded from Kaggle.com, a widely known platform for data science and machine learning datasets. Kaggle provides publicly available datasets from various industries, including retail and e-commerce, making it a reliable source for conducting shopping trend analysis.

3.2. Data Collection Process
The dataset was collected from customer transaction records at EDACO throughout the year 2023. The data includes:
	Sales transactions: Details of products purchased, quantity, and price.
	Customer preferences: Size, color, and category of items bought.
	Geographical insights: Locations of purchases.
	Payment methods: Distribution of different payment options used.
	Customer feedback: Review ratings for purchased items.
Data collection was automated through point-of-sale (POS) systems, online transactions, and customer feedback forms.

3.3. Data Structure
The dataset consists of multiple structured data fields that provide insights into customer behavior. The main components include:
	Product Information: Item name, category, color, and size.
	Transaction Details: Number of purchases, location of purchases, and payment method.
	Customer Preferences: Most preferred colors, sizes, and categories.
	Review Ratings: Customer feedback scores assigned to different products.
These structured fields enable trend analysis by aggregating and visualizing key metrics in the dashboard.

3.4. Important Features and Their Significance
Several key features contribute to understanding shopping trends. These include:
Feature	Significance
Top Items Purchased	Identifies the most popular products, aiding in inventory planning.
Most Size Purchased	Helps in stock management by ensuring availability of preferred sizes.
Best Selling Categories	Shows the most in-demand product groups, guiding marketing strategies.
Location of Purchases	Provides geographical insights into customer distribution, optimizing logistics.
Preferred Payment Method	Helps businesses understand and optimize payment options.
Best Review Rating Items	Identifies well-received products to enhance future sales strategies.
Best Color Purchased	Helps in predicting customer preferences for future stock updates.

3.5. Data Limitations and Biases
While the dataset is valuable, it has certain limitations:
	Sampling Bias: The data is based on EDACO’s customers and may not generalize to the broader market.
	Missing Context on Customer Demographics: The dataset lacks information on customer age, gender, and purchasing power, which could provide deeper insights.
	Limited Timeframe: Data is only for 2023, which may not reflect long-term trends.
	Potential Data Entry Errors: Human and system errors in data collection may introduce inconsistencies.
	Review Bias: Customer ratings may not be fully representative due to subjective opinions.

4 DATA SPLITTING AND PREPROCESSING 
4.0 Purpose
Data splitting and preprocessing are critical steps in preparing data for analysis and modeling. The goal is to ensure data quality, remove inconsistencies, and structure the dataset in a way that enables meaningful insights. This process ensures that sales data can be used for reporting, predictive analytics, and decision-making within the food distribution industry. 

4.1 Data Cleaning
This dataset was cleaned as downloaded from Kaggle.com. However steps were taken to ensure its properly cleaned, these includes
a.	Removing Duplicates: A test to ensure there’s no repeated sales transactions that could distort revenue calculations.
b.	Standardizing Formats: Ensuring consistent formatting for headings such as dates, currency, and categorical labels (e.g., city names, product categories).
c.	Correcting Inconsistencies: Resolving data discrepancies, such as different spellings for the same city or missing product names.
d.	Standard Excel Table: Ensuring the dataset is on standard excel table

4.2	Handling Missing Values
Missing data can occur due to incomplete transactions, technical failures, or customer entry errors. Common approaches include: Filling missing numerical values using central tendency measures. assigning the most common category for missing categorical data, if a record lacks essential fields (e.g., missing both item and price), it may be removed.

4.3 Data Transformations
To enhance usability and consistency, transformations were applied:
•	Encoding categorical variables: Converting non-numeric data like payment methods and product categories into numerical codes for analysis.
•	Scaling numerical values: Normalizing transaction amounts and purchase counts to improve model performance.
•	Feature engineering: Creating new features, such as average purchase per customer or preferred size by location, to extract deeper insights

4.4 Data Splitting
a.	Dependent data points: Values that can stand alone and influences other points and still make complete meaning. Such as shown above
b.	Independent data points: Values that cannot stand alone, influences other points and make complete meaning. Such as shown above
Category 1: Independent data points – Customer ID, Age, Gender, Item purchase, Category, Location, Size, Colour, Season, Subscription, Payment method, Shipping type, Preferred payment method, Frequency of purchase
Category 2: Dependent data - Purchased amount, Review rating, Discount applied, Previous purchases

4.5 Industry Context
This dataset is relevant to the retail and e-commerce industry, where customer behavior analysis is crucial for decision-making. It provides insights into:
	Consumer preferences (most purchased items, sizes, colors).
	Market demand across locations.
	Payment method trends.
Retailers use such analyses to optimize inventory, pricing strategies, and marketing campaigns.

4.6. Stakeholders
The key stakeholders benefiting from this analysis include:
	Retail Business Owners: Improve product stocking decisions and sales strategies.
	Marketing Teams: Develop targeted campaigns based on top-rated products and purchase patterns.
	Inventory Managers: Plan supply chains efficiently using demand forecasts.
	Financial Teams: Optimize payment options based on preferred methods.

4.7. Value to the Industry
This analysis provides actionable insights that help businesses:
	Enhance customer experience by stocking preferred sizes, colors, and categories.
	Optimize pricing strategies based on demand trends.
	Increase revenue by focusing on best-selling and highly-rated products.
	Improve operational efficiency by aligning stock availability with customer preferences.

5. PRE-ANALYSIS
Key Trends Identified
a.	Top Item Purchased: Blouses were the most frequently bought product, suggesting high demand in the clothing category.
b.	Most Purchased Size: M (Medium) was the most popular size, indicating a general preference for mid-sized apparel.
c.	Top-Rated Item: Jewelry received the highest customer ratings, signifying customer satisfaction with the product quality.
d.	Best-Selling Category: Clothing dominated sales, far outperforming accessories, footwear, and outerwear.
e.	Preferred Payment Methods: PayPal and Credit Cards were the most commonly used methods, while Bank Transfers were the least preferred.
f.	Location with Highest Purchases: Montana and California had the highest purchase rates, suggesting a strong customer base in these states.
g.	Best Color Purchased: Olive was the most favored color, followed by Yellow and Silver, which could influence future stocking and marketing strategies.

5.2. Potential Correlations Identified
From the available data, several potential relationships and correlations can be explored:
a.	Item Popularity vs. Customer Ratings: Jewelry, despite being a top-rated product, was not the most purchased item. This suggests that while quality is recognized, factors like pricing or demand could impact sales.
b.	Size Preference vs. Sales Performance: Medium-sized items were the most purchased, which may correlate with clothing sales, as apparel had the highest sales volume.
c.	Location vs. Purchase Trends: Montana and California showed the highest sales, which could be linked to population demographics, income levels, or local fashion trends.
d.	Payment Method Preference vs. Purchase Volume: Higher adoption of PayPal and Credit Cards indicates a preference for secure, digital payments, which might correlate with higher average transaction values.
e.	Best-Selling Color vs. Clothing Category Dominance: Olive, Yellow, and Silver being the most purchased colors might be driving the dominance of the clothing category.

5.3. Initial Insights
	Clothing remains the top category, and retailers should prioritize stocking blouses and other popular apparel items in Medium size.
	Since digital payment methods like PayPal and Credit Cards dominate, offering promotions or incentives for these methods could further enhance sales.
	Targeted marketing campaigns and inventory allocation should focus more on states like Montana and California, where demand is highest.
	Jewelry, being the top-rated product, presents an opportunity to expand its offerings or improve visibility to increase sales.
	Olive, Yellow, and Silver should be emphasized in future clothing and accessories designs to match customer preferences.

5.2.1 INITIAL INSIGHTS
a.	Since government sales dominate revenue, KISCO should prioritize government contracts, compliance, and bulk supply agreements.
b.	Exploring new government procurement programs in other countries could increase revenue streams.
c.	Paseo’s high COGS requires a review of production, sourcing, and pricing strategies to maximize profit margins.
d.	Cost-cutting strategies, such as alternative suppliers or bulk material purchasing, could improve overall profitability.
e.	With October showing the highest demand, inventory management should align with seasonal peaks to avoid stockouts.
f.	Targeted marketing and promotions before high-demand periods (such as September and early December) can further boost revenue.
g.	Reducing reliance on government contracts by growing the Small Business and Enterprise segments can create a more balanced revenue mix.
h.	Expanding distribution channels in other promising markets could enhance global sales performance.

6 IN-ANALYSIS
6.1. UNCONFIRMED INSIGHTS & AREAS REQUIRING FURTHER VALIDATION
From the initial observations, several patterns emerge, but their validity needs further investigation:
A.	Customer Preferences vs. Sales Volume:
	Clothing is the highest-selling category, but Jewelry has the best review ratings. A deeper analysis of whether high ratings translate into higher repeat purchases is necessary.
	The best-selling size (M) aligns with clothing dominance, but a breakdown of size preference by category is missing.
B.	Regional Sales Trends vs. Product Type:
	Montana and California have the highest purchases, but the dashboard does not specify whether these states prefer a particular category or product.
	Further exploration is needed to determine if purchasing behavior is influenced by climate, fashion trends, or income levels.
C.	Payment Method Correlations:
	PayPal is the most preferred payment method, while Bank Transfer is the least. However, the dashboard does not show whether high-value purchases correlate with specific payment methods.
	The impact of discounts or promotions on digital payment usage should also be analyzed.
D.	Color Preference vs. Product Category:
	Olive, Yellow, and Silver are the most purchased colors, but the specific product types associated with these colors remain unclear.
	Are these colors mainly preferred for clothing, accessories, or footwear?



6.2. AREAS REQUIRING FURTHER VALIDATION (DATA GAPS & MISSING ANALYSIS)
Despite providing significant insights, the dashboard has several data gaps that require further analysis:
A.	Customer Segmentation: No demographic insights (age, gender, income level) are available, limiting the ability to tailor marketing strategies. Customer retention trends and repeat purchase rates are missing.
B.	Time-Based Sales Analysis: The dashboard lacks sales distribution over months, weeks, or seasonal trends. Understanding peak shopping periods can help optimize inventory and marketing campaigns.
C.	Influence of Discounts & Promotions: No indication of how discounts or promotions impacted sales across different items or categories. Analyzing discount-driven sales vs. organic purchases is crucial.
D.	Comparison of High vs. Low-Performing Products: While we know the top-selling and top-rated items, the dashboard does not show the lowest-performing items. Identifying slow-moving inventory would help in clearance strategies.
E.	Customer Feedback & Review Trends: The review rating data does not indicate specific customer complaints or praises. A sentiment analysis of customer reviews could provide deeper insights.

7. POST-ANALYSIS AND INSIGHTS

7.1 key findings and comparison with initial findings
A. Product Performance & Customer Preferences
i.	Best-Selling Item: Blouse, indicating strong customer demand for women's clothing.
ii.	Top-Rated Item: Jewelry received the highest review rating (642.3), but its purchase volume (171) does not significantly outpace other items. This suggests that while jewelry is highly rated, its sales potential may not be fully realized.
iii.	Best-Selling Category: Clothing (1,737 units), outperforming Accessories, Footwear, and Outerwear.
iv.	Most Purchased Size: Medium (M) at 1,755 units, followed by Large (L) at 1,053. Small (S) and Extra-Large (XL) have significantly lower demand, which can help optimize inventory.
v.	Most Purchased Colors: Olive (177), Yellow (174), and Silver (173) lead in popularity, suggesting a strong preference for earthy and neutral tones.

B. Regional Sales Trends
i.	Highest Purchasing Locations: Montana (96 purchases) and California (95 purchases) top the list, with Idaho (93) and Illinois (92) closely following.
ii.	Potential Market Expansion: Alabama, despite ranking lower (89 purchases), still demonstrates strong purchasing activity. Targeted promotions here could drive higher engagement.

C. Payment Preferences & Consumer Behavior
i.	Most Used Payment Methods: 
	PayPal (677 transactions) leads, followed by Credit Card (671) and Cash (670).
	Debit Card (636), Venmo (634), and Bank Transfer (612) are less preferred, indicating that consumers prioritize digital payment security and convenience.
ii.	Trend Observation: The difference between PayPal, Credit Card, and Cash usage is minimal, suggesting that customers have diverse but balanced payment preferences.

D. Customer Satisfaction & Review Analysis
	Top Review Ratings: 
•	Jewelry (642.3), Pants (635.9), and Blouse (629.9) are the highest-rated items, aligning with the best-selling product trends.
•	However, Dress (623.3) and Sweater (617.8) have lower review scores, possibly indicating issues with quality, pricing, or fit.


2. Comparison with Initial Findings & Insights

Key Areas	Initial Findings	Post-Analysis Refinements
Top-Selling Product	Clothing category dominates	Blouse is the most purchased item
Review Ratings & Sales	Jewelry has the highest ratings	High-rated items do not always translate to high sales
Regional Demand	Montana & California lead	Strong purchasing activity seen in Alabama, offering expansion potential
Payment Methods	PayPal was leading	Cash and Credit Card usage is nearly the same as PayPal
Size Preference	M was dominant	L is also significantly popular; S and XL have lower demand
Color Trends	Olive, Yellow, Silver preferred	Need to link color preferences to product categories for targeted marketing


Strategic Insights & Recommendations
i.	Enhance Jewelry Sales Strategy: - Since jewelry is top-rated but not the highest-selling, bundle offers or targeted promotions can boost sales.
ii.	Optimize Clothing Inventory: - The demand for M and L sizes should drive stocking decisions, while S and XL require a demand assessment.
iii.	Regional Market Expansion: - Alabama shows potential for increased sales; targeted advertising or location-specific promotions could enhance growth.
iv.	Diversify Payment Incentives: - Offering discounts for underutilized payment methods (e.g., Bank Transfer, Venmo) may balance consumer choices.
v.	Improve Lower-Rated Products: - Understanding customer dissatisfaction in dresses and sweaters could help improve quality or pricing strategies.
vi.	Leverage Color Preferences: - Further research into whether Olive, Yellow, and Silver are linked to specific product types (e.g., clothing vs. accessories) can enhance targeted marketing.


9. OBSERVATIONS AND RECOMMENDATIONS
9.1 OBSERVATIONS
The following observations were made in course of the analysis: 
1.	Blouses are the most purchased item, followed by Pants and Jewelry.
2.	Clothing is the dominant category, with Accessories and Footwear trailing behind.
3.	Montana, California, and Idaho show the highest number of purchases, indicating strong customer engagement in these regions.
4.	The Medium (M) size is the most popular, followed by Large (L).
5.	Olive, Yellow, and Silver are the most preferred colors, indicating trends in fashion choices.
6.	PayPal and Credit Card are the most used payment methods, suggesting a preference for digital payments over bank transfers and cash.
7.	Jewelry, Pants, and Blouses receive the highest ratings, suggesting customer satisfaction with these products.

9.2	RECOMMENDATIONS
1.	Increase stock levels for Blouses, Pants, and Jewelry to meet demand.
2.	Focus more on the Clothing category while maintaining a balanced inventory for Accessories and Footwear.
3.	Expand marketing efforts in Montana, California, and Idaho, as these states show strong purchasing activity.
4.	Conduct market research in lower-performing regions to improve sales.
5.	Introduce more designs and variations in Medium and Large sizes, as they are the most preferred.
6.	Continue offering popular colors like Olive, Yellow, and Silver while experimenting with new shades.
7.	Enhance PayPal and Credit Card payment experiences, as they are the most preferred methods.
8.	Consider promotions or discounts for purchases made via Bank Transfers and Venmo to boost their usage.
9.	Maintain high quality in Jewelry, Pants, and Blouses, as they are the top-rated items.
10.	Use customer feedback to improve lower-rated products and enhance the shopping experience.
11.	Offer targeted discounts or promotions for popular products and sizes.
12.	Use social media and email campaigns to showcase trending colors and best-selling items.


10 CONCLUSIONS
The EDACO's Customers Shopping Trend Analysis for 2023 highlights key purchasing behaviors, preferred payment methods, and product demand. Clothing remains the most dominant category, with blouses being the top-purchased item. Montana and California show the highest number of purchases, and medium-sized products are in high demand. PayPal and credit card payments are the most preferred, and Jewelry is the top-rated item.
Overall, the analysis suggests that customers prefer fashionable and well-rated clothing and accessories, particularly in medium sizes and colors like olive and yellow. Digital payment options play a crucial role in the purchasing process, reinforcing the need for a seamless online shopping experience.

Key Learnings:
1.	Customer Preferences:
	Clothing is the best-selling category, with blouses, pants, and jewelry leading in purchases.
	Jewelry ranks as the highest-rated item, reflecting strong customer satisfaction.
	Medium-sized products dominate sales, indicating a key size range to stock.
	Olive, yellow, and silver colors are the most popular among buyers.
2.	Regional Insights:
	Montana, California, and Idaho have the highest purchase volumes.
	Potential opportunities exist in lower-performing regions through localized promotions.
3.	Payment Preferences:
	PayPal and Credit Cards are the most used payment methods.
	Bank Transfer and Venmo have the least usage, indicating possible friction in their adoption.
4.	Customer Satisfaction & Ratings:
	Jewelry, pants, and blouses have the best ratings, showing customer preference for these items.
	Sweaters and sandals have lower ratings, signaling potential improvement areas.

Future Research Areas:
1.	Investigate why Montana and California lead in purchases while other regions lag behind.
2.	Explore how seasonality impacts purchases to optimize inventory accordingly.
3.	Conduct a study on why Bank Transfers and Venmo have lower adoption rates and how to improve them.
4.	Assess the impact of offering payment-based discounts or rewards programs to encourage higher spending.
5.	Study why sweaters and sandals receive lower ratings and identify areas for improvement.
6.	Analyze the correlation between customer reviews and sales volume to optimize product promotions.
7.	Research emerging fashion trends to anticipate future product demand.
8.	Develop personalized recommendations based on customer purchasing behavior.
9.	Examine loyalty programs and retention strategies to increase repeat purchases.

11. REFERENCES & APPENDICES
References:
	Kaggle.com
	Charts and Dashboard extracted from the EDACO's sales data and trend.
	Market Research Reports – Studies on fashion industry trends, regional consumer preferences, and payment method adoption.
	Observations, Recommendations and Conclusion derived from data visualization techniques (bar charts, pie charts, and trend lines) applied in the dashboard.
