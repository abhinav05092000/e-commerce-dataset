# e-commerce-dataset
This project demonstrates how a structured dataset can be transformed into a clear business narrative using data visualization and storytelling principles.

Instead of using the commonly used Superstore dataset, this project uses a synthetic e-commerce order dataset created specifically for this case study. The dataset contains 3,600 orders across 2024–2025 and includes sales, discounts, returns, costs, categories, regions, and channels.

The objective is not to model a real company, but to demonstrate a professional analytical workflow from:

Business question → Data preparation → KPI analysis → Visualization → Insight → Recommendation

🎯 Business Question
Why did profit fall in Q3 2025 even though revenue grew?

The analysis investigates whether the decline was caused by:

Higher discounting
Increased shipping/fulfilment costs
Higher product returns
Category-level margin differences
Regional profitability differences
📈 Key Findings
KPI	Q3 2025	Change vs Q2 2025
Revenue	₹6.15M	+26.8%
Profit	₹0.68M	-9.9%
Profit Margin	11.0%	Compressed
Return Rate	8.7%	Higher pressure
Average Discount	17.4%	Higher promotional intensity
Main insight

Revenue growth did not translate into profitable growth.

The Q3 growth was achieved alongside heavier discounting and increased cost-to-serve. Returns and fulfilment costs further reduced the value of incremental sales.

📊 Visual Story

The PowerPoint presentation follows a deliberate narrative:

1. Executive Summary

Revenue increased strongly, but profit declined.

2. Trend Evidence

The revenue/profit trend shows that sales remained resilient while profitability weakened.

3. Profit Driver Analysis

The driver bridge highlights discounting, shipping and returns as important sources of profit erosion.

4. Category Analysis

Profitability is not uniform across categories. The weakest category in Q3 was Electronics, with a margin of 5.2%.

5. Regional Analysis

Regional economics also differ. The weakest regional margin was West, at 10.8%.

6. Recommendation

The business should move from a revenue-growth mindset toward profitable-growth management.

💡 Recommendations
1. Introduce category-level discount guardrails

Set minimum contribution-margin thresholds and require approval for promotions that fall below the threshold.

2. Reduce return-related leakage

Analyze return reasons by category, product and supplier. Apparel and Electronics should receive particular attention.

3. Manage delivery cost by geography and channel

Review free-shipping policies in low-margin regions and marketplace orders.

4. Change the primary promotion KPI

Do not evaluate campaigns using revenue alone. Track:

Contribution margin
Profit per order
Discount rate
Return rate
Cost-to-serve
Incremental profit
🧰 Tools Used
Python
Pandas — data preparation and analysis
NumPy — synthetic data generation
Matplotlib — data visualization
python-pptx — PowerPoint generation
Microsoft Excel — supporting analysis
GitHub — project/version management


The synthetic dataset contains fields such as:

Order ID
Order Date
Region
Category
Channel
Units
Gross Sales
Discount Rate
Net Sales
Returned
Refund Amount
COGS
Shipping Cost
Payment Fee
Return Handling Cost
Profit
▶️ How to Reproduce

Install the required packages:

pip install pandas numpy matplotlib python-pptx

Then run:

python analysis.py

The analysis script generates the core KPI tables used in the project.
