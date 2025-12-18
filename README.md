# Project Background
TCA is one of the fastest-growing startups in the e-commerce industry, with a strong presence across major international markets including the United States, the United Kingdom, Germany, France, and Spain.
The company operates across multiple e-commerce platforms, namely Amazon, Etsy, Shopify, Google, and Facebook, and currently manages four core product categories: Kids Bedding Sets, Jewelry Boxes, Photo Frames, and Tote Bags.
Key Strategic Question
Which product category should be prioritized for the 2026 growth strategy, and what data-driven insights and strategic recommendations can support this decision?

Insights and recommendations are provided on the following key areas:
* Revenue and volume growth over time at both category and product levels
* Product quality based on customer feedback (product and review scoring), identifying categories and ASINs with outstanding customer preference
* Product matrix analysis, leveraging revenue growth, sales volume, and customer preference indicators
* Variation effectiveness analysis, assessing the contribution of variations by brand, color, size, and piece count to identify the most in-demand, stable, and scalable variations

An interactive PoweBI dashboard used to report and explore potential products can be found [Ecommerce product performance analysis.pbit](https://github.com/AnTran-DA/E-commerce-Product-Performance-Analysis-Development-Roadmap-2026-.pbi/blob/main/Ecommerce%20product%20performance%20analysis.pbit)

# Data Structure & Initial Checks
The companies main database structure as seen below consists of four tables: Kids Bedding Sets, Jewelry Boxes, Photo Frames, and Tote Bags. Each of table is complexity data structure, so I clean data and restructure data for four tables and 1 help table: metric, product dimension, review dimension, analysis ASIN and calculate.
A description of <img width="1656" height="807" alt="diagram" src="https://github.com/user-attachments/assets/3aa69c1f-fb9e-4c09-84aa-5619258aa7e1" />
each table is as follows:
* Metrics table: Contains all transaction-level data over a two-year period.
* Product dimension: Includes the attributes and characteristics of the products being sold.
* Review dimension: Captures customer ratings and review information.
* ASIN analysis table: This table is created after identifying high-potential products and is used to further analyze their performance by size, color, brand, and other variation attributes.
  <img width="1656" height="807" alt="image" src="https://github.com/user-attachments/assets/745f1ce9-3a28-4eaa-b087-18189924030e" />
