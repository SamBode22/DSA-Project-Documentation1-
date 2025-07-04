# DSA-Project-Report-Documentation
## Project Title: Amazon Product Review Analysis
### Dataset Description:
 The dataset contains information scraped from Amazon product pages, including:
- Product details: name, category, price, discount, and ratings
- Customer engagement: user reviews, titles, and content
- Each row represents a unique product, with aggregated reviewer data stored as comma-separated values
- Total Records: 1,465 rows
- Total Fields: 16 columns
- Given file format: Excel workbook_xlsx

## Introduction
 This report gives analysis about product and customer review data to generate insights that can guide product improvement, marketing strategies, and customer engagement. By leveraging key metrics and insights from advanced analytics tools, company can make informed decisions, respond quickly to market trends, and outperform competitors in a saturated digital marketplace.

## Step-by-step Approach
### Step 1: Import, Clean and Prepare my data
-	Open Excel, load my dataset (Amazon Excel workbook.xlsx) and created a copy of raw data for backup.
-	Added calculated column: =TRIMLEFT(B2, FIND(“#”, SUBSTITUE(B2, “ ”, “#”, 4) & “#”) – 1)) to shorten “Product_name” column and  applied text to column for parsing strings on “Category” column due to long characters which make my data looks rough
-	Unused columns were hidden and my data becomes cleaner
-	New columns were created: potential_revenue(Actual_price  * Rating_Count), price_bucket. e.t.c
-	Filter was used to temporarily hide rows
-	Sort was used to rearrange in smallest to largest and vice versa
	
### Step 2: Data Transformation
-	Used PivotTables to summarize values by; sum, count, average, max,
### Step 3: Exploratory Data Analysis (EDA)
-	Used Conditional Formatting to highlight patterns.
-	Visualized trends using charts (Bar, Clustered column, Line, Pie).
-	Applied PivotCharts to grouped visual summaries.
### Step 4: Dashboard and Reporting
-	Creates dynamic dashboards using pivotCharts, Key Performance indicators (KPIs) and Slicers for interactivity
Insights and Interpretation
Product Rating and Reviews:
-	Electronics, Computer & accessories, Home & kitchen categories receive high rating due to the effectiveness of the products, functionalities and the caliber of people that use the products
-	Customers who leave 3 – 4 star reviews suggest product improvements and active responses/feedback by the company
-	Potential revenue can be greatly increased if product’s rating is being worked on
-	Low rating (1 & 2 stars) reviews speak about customer dissatisfaction, products deficiency and lack of company responses, however implementing a review response policy could improve brand perception
-	The difference between the average actual price and average discounted price is reasonable and can be improved
-	Discount percentage increased product sales volume, potentially lead to higher customer ratings and improved cash flow.
## Recommendations
- Automate review responses to improve responsiveness
- Target ads using language and tone found in 5-star reviews.
- Incorporate praised features more broadly across product lines.
- Prioritize fixes based on high-frequency complaints
- Launch loyalty programs targeting positive reviewers and brand advocates.

## Conclusion 

 Analyzing customer and product review data provides actionable insights that go beyond traditional surveys and focus groups. By integrating review analysis into the decision-making process, organizations can enhance product quality, tailor marketing efforts, and build lasting customer relationships
