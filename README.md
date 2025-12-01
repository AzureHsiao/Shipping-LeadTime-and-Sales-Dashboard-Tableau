# Shipping-LeadTime-and-Sales-Dashboard-Tableau

This repository contains an interactive Tableau dashboard analyzing product category sales and state-level shipment lead times across the United States. The visualizations include monthly sales crosstabs, cumulative sales trends, category distribution, lead-time heatmaps, and a geospatial map illustrating delivery performance.
The dashboard is designed to support operational decision-making, supply chain planning, and retail category management.



## Dashboard Overview

### Key Views Included
1. **PA Category Sales Crosstab**
   - Monthly sales breakdown by category and sub-category
   - Highlights seasonal patterns in Furniture, Office Supplies, and Technology
   - Includes dynamic year and category filters

2. **Sales & Units Sold Trend**
   - Running sum of sales and quantity over time
   - Shows cumulative revenue growth across months
   - Highlights volume-sales alignment across major categories

3. **Category Contribution Pie Chart**
   - Percentage contribution to total quantity sold
   - Technology: ~36%, Furniture: ~32%, Office Supplies: ~31%

4. **State Lead Times Heatmap**
   - Average shipping lead times by state, segment, and year
   - Clear indicators of slow vs fast delivery regions
   - Filters: year, segment, ship mode

5. **US Map – Average Lead Times**
   - Geospatial visualization of state-level delivery performance
   - Green = faster states (e.g., North Dakota: 1 day, Ohio: 5 days)
   - Red = slower states (e.g., Wyoming & Maine: 47 days)



## Data Insights

### Category Sales Insights
- Furniture shows strong early-year spikes (e.g., March & April peaks in Chairs and Tables)
- Office Supplies display more stable monthly performance
- Technology contributes the *highest* share of overall units sold (36%)

### Sales Trend Insights
- Sales grow consistently month-over-month, exceeding **$2.3M** by December
- Quantity sold follows a similar upward trend, reinforcing demand consistency
- Strong alignment indicates no major fulfillment bottlenecks impacting volume

### State Lead Time Insights
- **Fastest-performing states:** North Dakota (1 day), Ohio (5 days), Nebraska (6 days)
- **Slowest states:** Wyoming (47 days), Maine (47 days), Nevada (40 days)
- Delivery speed varies heavily by region and segment, revealing opportunities for logistics optimization
- Home Office and Consumer segments show larger fluctuations than Corporate



## Dashboard Features

- **Interactive filters:** Year, category, segment, and ship mode  
- **Heatmap color encoding:** Quick identification of outliers and performance gaps  
- **Geospatial map:** Immediate regional comparison of lead times  
- **Crosstab tables:** Detailed monthly sales reporting  
- **Dual-axis trend line:** Running Sum of Sales vs. Running Sum of Quantity  

<img width="1026" height="415" alt="Screenshot 2025-11-30 at 10 10 12 PM" src="https://github.com/user-attachments/assets/4a188901-779f-44cc-9e10-fc5d66df2727" />
<img width="1026" height="358" alt="Screenshot 2025-11-30 at 10 10 27 PM" src="https://github.com/user-attachments/assets/391c14a6-4586-4783-8457-fad54d89884d" />
<img width="1026" height="408" alt="Screenshot 2025-11-30 at 10 10 51 PM" src="https://github.com/user-attachments/assets/b3a86971-7ebd-45e0-affa-f712a907d7d9" />
<img width="1026" height="377" alt="Screenshot 2025-11-30 at 10 11 04 PM" src="https://github.com/user-attachments/assets/e30c4047-cf55-4411-bd5b-5f19a75036b8" />




## Tools Used

- Tableau (Workbook & Dashboard)
- Tableau Mapbox Integration (for geospatial mapping)
- Excel / CSV data source (Superstore or equivalent)



## Business Applications

This dashboard supports:

- **Supply Chain Optimization** – identify slow-performing states and improve carrier routing  
- **Inventory Planning** – understand seasonal demand by product category  
- **Category Management** – evaluate the contribution of major product lines  
- **Operational Benchmarking** – compare lead times across segments and years  



## Conclusion

The Tableau dashboard provides a comprehensive view of U.S. sales performance and delivery lead times. By combining category sales analysis with state-level shipping data, it offers actionable insights for operational efficiency, logistics improvement, and strategic planning.
