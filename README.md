# Swiggy_dataAnalysis
Swiggy Data Analysis: Strategic Insights & Interactive Dashboard
📖 Project Overview
This project is an end-to-end data analysis of Swiggy’s operational data, covering 197,430 unique dish entries. The goal was to transform raw restaurant and order data into a high-impact dashboard that tracks revenue performance, consumer preferences (Veg vs. Non-Veg), and regional growth across states like Karnataka and Sikkim.

🚀 Key Performance Indicators (KPIs)
Total Revenue: ₹53.01 Million (Sum of Price)

Total Items Sold: 197,430

Average Order Value (AOV): ₹268.51

Average User Rating: 4.34 / 5.0

Total Review Volume: 5.59 Million Ratings

📈 Deep Dive Insights
1. Revenue Segmentation (Food Type)
The market shows a strong preference for Vegetarian options in the regions analyzed:

Veg Revenue: ₹33,842,210 (~63.8%)

Non-Veg Revenue: ₹19,170,295 (~36.2%)

2. Time-Series Analysis (Monthly Trends)
Revenue peaks were observed in late Spring, while the start of the year showed steady growth:

Highest Performance: May (₹7.46 Million)

Steady Growth: January (₹6.82 Million) and February (₹6.26 Million)

Quarterly Distribution: Significant volume remains consistent through Q1 and Q2.

3. Regional & Restaurant Highlights
Karnataka (Bengaluru): High volume of "Recommended" and "Snack" categories. Key players include Anand Sweets & Savouries and Srinidhi Sagar Deluxe.

Sikkim (Gangtok): Significant demand for specialized categories like Momos. Mama's Kitchen is a top contributor with high ratings (4.4+).

🛠️ Data Engineering Steps
Data Cleaning: Handled nearly 200k rows, ensuring consistency in currency formats and category names.

Date Dimensionality: Extracted Quarters, Weekdays, and Months to identify cyclical ordering patterns.

Aggregation: Built complex Pivot Tables to bridge the gap between "Dish Name" count and "Rating Count" impact on revenue.

Dashboarding: Integrated Slicers for State, City, and Food Type to allow stakeholders to drill down into specific micro-markets.

📂 Repository Structure
Swiggy Data: Raw data including State, City, Restaurant, and Pricing details.

Sheet1: The "Calculation Engine" containing KPI summaries and Pivot Tables.

Dashboard: The final interactive user interface.

💻 How to Interact
Open the Swiggy Data Dashboard.xlsx.

Navigate to the Dashboard sheet.

Use the Slicers to filter by your city of interest (e.g., Bengaluru).

Observe the KPI Scorecards update in real-time to show regional AOV and Revenue.
