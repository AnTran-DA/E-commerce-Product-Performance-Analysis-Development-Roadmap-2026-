# Project Background
TCA is one of the fastest-growing startups in the e-commerce industry, with a strong presence across major international markets including the United States, the United Kingdom, Germany, France, and Spain.
The company operates across multiple e-commerce platforms, namely Amazon, Etsy, Shopify, Google, and Facebook, and currently manages four core product categories: Kids Bedding Sets, Jewelry Boxes, Photo Frames, and Tote Bags.
Key Strategic Question
Which product category should be prioritized for the 2026 growth strategy, and what data-driven insights and strategic recommendations can support this decision?

Insights and recommendations are provided on the following key areas:
* Revenue and volume growth over time at both category and product levels.
* Product quality based on customer feedback (product and review scoring), identifying categories and ASINs with outstanding customer preference.
* Product matrix analysis, leveraging revenue growth, sales volume, and customer preference indicators.
* Variation effectiveness analysis, assessing the contribution of variations by brand, color, size, and piece count to identify the most in-demand, stable, and scalable variations.

An interactive PoweBI dashboard used to report and explore potential products can be found [Ecommerce product performance analysis.pbit](https://github.com/AnTran-DA/E-commerce-Product-Performance-Analysis-Development-Roadmap-2026-.pbi/blob/main/Ecommerce%20product%20performance%20analysis.pbit)

# Data Structure & Initial Checks
The companies main database structure as seen below consists of four tables: Kids Bedding Sets, Jewelry Boxes, Photo Frames, and Tote Bags. Each of table is complexity data structure, so I clean data and restructure data for four tables and 1 help table: metric, product dimension, review dimension, analysis ASIN and calculate.
A description of each table is as follows:
* Metrics table: Contains all transaction-level data over a two-year period.
* Product dimension: Includes the attributes and characteristics of the products being sold.
* Review dimension: Captures customer ratings and review information.
* ASIN analysis table: This table is created after identifying high-potential products and is used to further analyze their performance by size, color, brand, and other variation attributes.

  <img width="1633" height="783" alt="diagram" src="https://github.com/user-attachments/assets/02429e29-d50e-4d7b-a243-062ddc4a3365" />

# Executive Summary

**Overview of Findings**

The company currently operates across four product categories: Kids Bedding Sets, Tote Bags, Jewelry Boxes, and Photo Frames. Three categories stand out as strategically significant:
* Kids Bedding Sets: This category demonstrates a strong balance between scale and growth. It remains the company’s core business, delivering the highest profitability and sales volume, despite relatively moderate growth.
* Tote Bags: The second-largest category by revenue, Tote Bags show substantial market potential, trailing.
* Kids Bedding Sets by only 11.5%. The category has also exhibited clear growth momentum over the past two years.
* Jewelry Boxes: This is the company’s fastest-growing category, achieving a revenue growth rate of 56.7%, positioning it as a key growth engine going forward.

<img width="1173" height="658" alt="1" src="https://github.com/user-attachments/assets/0feb3fa1-af34-4b22-b06a-5a7c2dbdd4d6" />

**Insights Deep Dive**


Revenue and volume growth over time at both category and product levels.

* Kids Bedding Sets: While this category shows strong potential, it carries relatively high risk due to highly dispersed and volatile revenue and volume growth. Most ASINs are growing at relatively low levels, with revenue growth below 48.8%. This indicates breakout potential, but also elevated risk, requiring deeper analysis at the ASIN and variation levels, as well as a restructuring of the product portfolio within the category.
* Tote Bags: Market demand is relatively stable, with limited revenue volatility. Revenue growth ranges from 3.95% to 82.14%, positioning this category as a safe and steady growth driver.
* Jewelry Boxes: Despite strong overall growth, performance is largely driven by product assortment expansion, rather than exceptional growth at the individual product level.
* Photo Frames: This category shows no notable growth signals, with low and clustered performance distribution.

<img width="1170" height="657" alt="2" src="https://github.com/user-attachments/assets/7fdd48a6-81e7-43bc-b998-cfeeaa6943a0" />


Product quality based on customer feedback (product and review scoring), identifying categories and ASINs with outstanding customer preference.

Note: Most of the company’s categories receive ratings between 4 and 5 stars, and Tote Bags have the highest volume of customer reviews among all categories.
Assumption: The Tote Bag category also exhibits a strong concentration of 4–5 star ratings.
Most ratings are concentrated at 4–5 stars, which is a positive signal but requires further quality validation.
The category-level rating distribution shows a strong clustering around 4–5 stars; however, this must be interpreted with caution. A high volume of star ratings with limited written reviews (low review depth) differs materially from a large number of detailed, positive written reviews.

* Kids Bedding Sets: This category has the highest total number of reviews and ratings, with many ASINs receiving exceptionally high review counts. This indicates strong customer trust and the largest market scale among all categories. However, performance at the ASIN level is highly volatile, suggesting uneven product-level outcomes.
* Tote Bags: While many ASINs receive relatively high ratings—and some score extremely well—the actual number of customer reviews is limited. This suggests that the category may lack sufficient “wow” factor to motivate customers to leave reviews.
* Jewelry Boxes and Photo Frames: These categories show no particularly notable signals, with low review volumes and limited ratings overall. Although Jewelry Boxes previously appeared to be a high-growth category, customer feedback indicates that this growth may be short-lived and lacks clear signs of long-term sustainability.

  <img width="1172" height="655" alt="2" src="https://github.com/user-attachments/assets/cf9aa9f6-eed7-4792-8eec-c08058e9b8e9" />

Product matrix analysis

* Conclusion on category selection: Based on the analysis of revenue growth, volume growth, and customer feedback, Kids Bedding Sets emerge as the category that combines core sales importance, strong revenue growth potential, and high customer preference. To mitigate risks associated with underperforming ASINs while continuing to scale winning ASINs, a product matrix analysis should be conducted to identify the category’s priority product segments.

* Threshold definition: The threshold is defined as the overall average value across all ASINs, combined with the degree of growth dispersion among ASINs.
→ Any item exceeding the average plus the growth variance is considered a top-performing (outperforming) item.

* Product grouping based on revenue growth contribution (80–90–95 rule):
Group A: Most critical items, contributing 80% of total revenue growth
Group B: Moderately important items, contributing the next 10%
Group C: Lower-priority items, contributing an additional 5%
Group D: Remaining items

<img width="1163" height="411" alt="11122025_Trần Bích An (1)" src="https://github.com/user-attachments/assets/80eb180d-5082-4648-8c73-ad80d806c39e" />

Visualization of the 17 selected products grouped by category

<img width="1806" height="818" alt="11122025_Trần Bích An (2)" src="https://github.com/user-attachments/assets/a55dbca6-1305-4991-98fa-0e447405bd78" />












