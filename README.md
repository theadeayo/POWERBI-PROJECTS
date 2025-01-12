# Project Objective
This project showcases the financial performance of business segments across countries and years. It uses metrics such as profit (analyzed by month and quarter), gross sales, discounts offered, and units sold to derive actionable insights. Attached is the pbit file

<img width="715" alt="image" src="https://github.com/user-attachments/assets/18f8a9e6-a369-4aaa-acaa-d915490eff3c" />


# Process:
## Dataset Transformation
#### Pre-Loading Adjustments : Attached is the raw dataset used or view here 👉 [financial_data.csv](https://github.com/user-attachments/files/18391392/financial_data.csv)

These were the transformations implemented on the datasets to derive the resulted dashboard
1.  Removed the “$” symbols from the below columns
    - Units Sold, Manufacturing Prices, Sales Price, Gross Sales, Sales, Discount, COGS & Profit
2.  Changed the data type of the above columns to Whole Numbers
3.  Replaced “-” to “0” in the discount column to avoid Errors
4.  Replaced the Error rows in the Profit Column to 0 for data validity
5.  Created a new date column to change the format from MM/DD/YYYY to DD/MM/YYYY
    - Regenerated Columns Month, Quarter and Year
6. Added prefix “Q” to the quarter column
#### Post Loading Adjustments
1. Due to the high volume of transaction-level data, grouping by Year and Quarter was necessary to provide aggregated insights and improve performance in visualizations
2. Disabled Auto Date Hierarchy creation and refreshed
3. Created custom Date Hierarchy and added grouped years and quarters to the date hierarchy to aid visualizations and drilling

# Visualizations
#### Below are the visual elements utilized
- Clustered Column Chart for the Quarterly Profit Graph
- Cards for the Gross Sales, Discount, Units Sold & Cost of Goods Sold presentation
- Slicers further formatted into “Dropdown” was used for the Segments, Country and Year presentation
- Area Chart was used for the Monthly Profit presentation
Additionally:
    - Background canvas is a self-created imported PowerPoint template. The imported PowerPoint template provided a professional and cohesive background, aligning with the dashboard's financial theme.

# Insights:
1. The loss making SEGMENT is the ENTERPRISE SEGMENT.
2. Additionally, Enterprise Segment's total discount is more than the cumulative discounts of Channel and Mid Market Segments
3. Overall Top Performing Product is PASEO
4. USA is the top performing country generating the top net sales
5. France is the Country with the Highest Total Profit

# Skills Demonstrated:
- Technical Skills: DAX, M Query, Power BI.
- Design Skills: Custom PowerPoint background design.
- Soft Skills: Data storytelling and communication.

# Instructions for Use:
Download the PBIT file and open it in Power BI Desktop.

##### Project inspired by @TheMrityunjayPathak
