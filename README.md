
 Data Exploration & Analysis
 Data Preparation
Loaded dataset containing 9,994 records and 21 features
Converted Order Date and Ship Date into datetime format for time-series analysis
Verified data quality and summary statistics
 Exploratory Data Analysis (EDA)
1️⃣ Sales Distribution & Business Scale
Average sales per transaction: ~230
Maximum sales: 22,638 (high-value transactions exist)
Sales distribution is highly skewed, indicating a few large orders drive revenue

 Interpretation:
Revenue is concentrated in high-value customers/orders

2️⃣ Customer Segmentation
Consumer segment dominates (51%)
Followed by Corporate and Home Office

 Insight:
The business relies heavily on individual consumers, presenting opportunities for:

Customer loyalty programs
Upselling strategies
3️⃣ Shipping Mode Analysis
Standard Class dominates (≈60%)
Same-day delivery is least used

Insight:
Customers are price-sensitive rather than speed-sensitive

 Geographic Performance (City-Level Analysis)
🔝 Top Performing Cities by Sales
New York City
Los Angeles
Seattle
San Francisco

 These cities contribute a significant portion of total revenue

⚠️ Profitability Concern
Cities like:
Philadelphia
Houston
Chicago

generate high sales but negative profits

 Critical Insight:
High revenue ≠ High profitability
Losses are likely driven by:

High discounts
Cost inefficiencies
 Product & Category Insights
A small group of products drives the majority of sales (Pareto principle effect)
Categories show varying profitability patterns

 Insight:
Not all products contribute equally — optimization is needed

📉 Discount vs Profit Analysis
Weak negative correlation between Discount and Sales
Stronger relationship between Discount and Profit (negative impact)

 Insight:
Increasing discounts:

Does NOT significantly increase sales
BUT reduces profitability
 Correlation Analysis
Strong Positive Relationships:
Sales ↔ Profit (0.48 correlation)

Higher sales generally lead to higher profit (but not always)

Weak/Negative Relationships:
Discount has minimal impact on sales
Slight negative effect on profitability
 Feature Engineering Insight

Created a new variable:

Net_sales = Profit - Discount

 Found relationship between profitability and revenue generation

 Quantity & Sales Behavior
Certain combinations of City + Quantity drive extremely high sales
Example:
New York City dominates across multiple quantity levels

 Insight:
Bulk purchases significantly impact revenue

 Key Business Insights
Revenue is highly concentrated in a few cities and products
High discounts are eroding profitability
Some high-sales regions are actually loss-making
Customer base is heavily skewed toward Consumers
Bulk purchases and high-value orders drive performance
 📈 Business Recommendations
1️⃣ Optimize Discount Strategy
Reduce excessive discounting in loss-making cities
Implement data-driven discount thresholds

 Expected Impact:
✔ Improved profit margins

2️⃣ Focus on High-Performing Cities
Increase marketing spend in:
New York
Los Angeles
Seattle

 Expected Impact:
✔ Higher ROI on marketing

3️⃣ Fix Loss-Making Regions
Investigate:
Philadelphia
Houston
Chicago

 Actions:

Adjust pricing
Reduce discounting
Optimize logistics costs
4️⃣ Customer Strategy Improvement
Introduce:
Loyalty programs
Targeted promotions for repeat customers

 Expected Impact:
✔ Increased customer lifetime value

5️⃣ Product Optimization
Focus on:
High-margin products
Remove or redesign:
Low-performing products
6️⃣ Leverage Bulk Sales Strategy
Encourage bulk purchases via:
Volume discounts (controlled)
Bundled offers
