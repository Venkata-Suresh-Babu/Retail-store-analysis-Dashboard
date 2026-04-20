# Retail Store Sales Dashboard | Power BI

<img width="1024" height="1536" alt="image" src="https://github.com/user-attachments/assets/900dcef5-9366-4bfd-adea-78187d861ee9" />

# 1. Project Objective

Built an interactive Power BI dashboard to analyze retail sales performance and customer behavior across product categories, gender, seasonality, discounts, and item ratings. The objective was to identify revenue drivers, evaluate discount effectiveness, and surface actionable insights to support pricing, inventory planning, and marketing decisions.


# 2. Dataset Overview

The dataset contains transactional-level retail data with the following key attributes:

**Customer demographics:** Age, Age Group, Gender

**Sales metrics:** Amount, Discount Applied (%), Item Rating

**Product information:** Category, Item Purchased

**Behavioral attributes:** Payment Method, Previous Purchases

**Time dimension:** Season

The dataset represents **5,000 customers** with purchases distributed across multiple product categories and seasons.

# 3. Data Modeling & DAX Measures

Created DAX measures to support business reporting and aggregation:

Total Revenue

Total Revenue without Discount

Total Customers

Avg Discount %

Avg Item Rating

Avg Age

Male Count, Female Count

Male %, Female %

These measures enabled consistent calculations across visuals and supported cross-filtering and drill-down analysis.

# 4. Dashboard Design & Visuals Used

The dashboard was designed to support both executive-level overview and detailed category analysis:

KPI Cards: Display Total Revenue, Total Customers, Avg Age, Avg Item Rating, and Avg Discount % to provide a quick performance snapshot.

Treemap: Shows revenue contribution by product category to highlight top revenue drivers and low-performing categories.

Scatter Plot (Discount vs Revenue): Analyzes the relationship between average discount levels and total revenue by category, with bubble size representing customer volume.

Stacked Bar Chart (Category vs Gender Revenue): Compares gender-wise revenue contribution within each product category to identify customer preference patterns.

Line Chart (Revenue by Season): Tracks seasonal revenue trends to highlight demand fluctuations across Spring, Summer, Winter, and Autumn.

Performance Snapshot Table: Summarizes category-level performance with conditional formatting applied to revenue, ratings, and discount metrics to highlight high and low performers.

Slicers: Enabled filtering by Gender to allow focused analysis and interactive exploration.

<img width="1282" height="719" alt="image" src="https://github.com/user-attachments/assets/0980e927-dad7-4cc7-908a-af88662f3b87" />

# 5. Key Insights

Electronics is the primary revenue driver
Electronics contributes the highest share of total revenue by a significant margin. Performance changes in this category have the greatest impact on overall business results.

Discounts do not consistently drive higher revenue
Categories with higher average discounts do not always generate higher revenue. Revenue appears to be driven more by product demand and category popularity than discount depth alone.

Footwear and Sports show strong customer volume
Footwear and Sports attract a high number of customers and contribute meaningful revenue, indicating stable demand. These categories offer opportunities to increase average order value through bundles or cross-sell strategies.

Gender contribution varies by category
Overall revenue contribution by gender is relatively balanced; however, category-level patterns show differences in customer preferences. This creates opportunities for category-specific targeting and personalized marketing.

Spring is the strongest revenue season
Seasonal analysis shows that revenue peaks during Spring and declines toward Autumn. This pattern highlights the importance of aligning inventory and promotions with seasonal demand.

Product ratings remain stable across categories
Avg item ratings are relatively consistent across categories, suggesting customer satisfaction levels do not explain revenue differences. Revenue variation is more closely tied to demand, pricing, and category relevance.

<img width="1282" height="718" alt="image" src="https://github.com/user-attachments/assets/f461b2d6-45f5-4039-bc78-353587410adf" />


# 6. Business Recommendations

Prioritize inventory and assortment planning for Electronics due to its dominant revenue contribution.

Reduce blanket discounting strategies and shift toward targeted promotions for categories with proven demand sensitivity.

Launch bundled offers or cross-category promotions in Footwear and Sports to increase basket size.

Design category-specific marketing campaigns based on observed gender purchase patterns.

Increase marketing spend and stock availability ahead of the Spring season to capture peak demand.

<img width="1283" height="719" alt="image" src="https://github.com/user-attachments/assets/c159ce19-50b3-40ee-910c-9af36f4a11b7" />


# 7. Technical Skills Demonstrated

Built interactive dashboards using Power BI

Created reusable DAX measures for revenue, customer metrics, and demographic analysis

Applied conditional formatting to improve readability and highlight performance gaps

Designed business-focused visuals (treemap, scatter plot, stacked bar, line chart)

Implemented slicers and cross-filtering for interactive analysis

Structured visuals to support executive-level decision-making
