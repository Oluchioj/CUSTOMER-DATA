## CUSTOMER-DATA
Project: Customer Segmentation for a Subscription Service

Objective
The goal of this project is to analyze customer data to identify segments, trends, and behaviors in subscriptions, cancellations, and renewals. By understanding customer behaviors and trends, you’ll provide actionable insights into subscription types and key drivers behind cancellations. The final output will be an interactive Power BI dashboard.

Tools Used
Excel: Initial data exploration and calculation of basic metrics
SQL Server: In-depth querying and extraction of specific insights
Power BI: Visualization and interactive dashboard creation
Step 1: Data Exploration in Excel
1.1 Initial Data Exploration
Load Data: Import the customer subscription data into Excel.
Familiarize with Columns: Identify relevant fields such as Customer ID, Subscription Type, Start Date, End Date, Status (active/canceled), Region, and Revenue.
1.2 Creating Pivot Tables
Using pivot tables, you can explore initial patterns in the data:

Subscription Patterns by Type: Place Subscription Type in Rows and Customer ID in Values (Count) to show customer counts by subscription type.
Subscription Patterns by Region: Place Region in Rows and Customer ID in Values (Count) to show customer distribution by region.
Cancellation and Renewal Rates: Use Status (Active/Canceled) to explore rates of cancellation versus renewal by segmenting data across different fields.
1.3 Calculating Key Metrics with Formulas
In Excel, use formulas to calculate specific metrics:

Average Subscription Duration: Calculate the difference between End Date and Start Date for each subscription, then average this duration across all customers.
Popular Subscription Types: Use a COUNTIF or pivot table to identify the most popular types.
Additional Reports: Consider metrics like monthly average cancellations, customer lifetime value, or revenue per customer, which may provide additional insights.

These queries will reveal key insights about customer distribution, popular subscriptions, average duration, revenue, and cancellations.

Step 3: Building a Power BI Dashboard
Once the data has been analyzed in Excel and SQL, you can create a visually engaging and interactive Power BI dashboard to present the findings.

3.1 Importing Data
Import both the raw data and any extracted SQL insights (if necessary, export SQL query results to CSV for ease of import).
Use Power Query to clean and transform the data, ensuring a consistent format.
3.2 Dashboard Layout and Structure
Design a user-friendly layout with key sections:

Customer Segmentation Overview:

Include visuals to show customer count by region, subscription type, and average subscription duration.
Use bar charts, pie charts, or a map to represent customer distribution.
Subscription Trends:

Display the most popular subscription types and total revenue per type with bar charts.
Use cards to show average subscription duration and overall active versus canceled subscriptions.
Cancellations and Renewals:

Visualize cancellation trends with a line chart to display monthly cancellations.
Show the top regions by cancellations using a bar chart.

3.3 Adding Interactive Elements
Slicers: Add slicers for region, subscription type, and time frame to allow users to filter data interactively.
Drill-Down Options: Enable drill-down in visuals for further exploration (e.g., from region to individual customers in that region).
Filters: Use filters to focus on specific segments like active subscriptions or customers with long durations.

3.4 Formatting and Customizing Visuals
Ensure consistent use of color coding and label fonts.
Use dynamic titles that adjust based on slicer selections.
Test interactions to ensure smooth navigation between views and accurate filtering.

3.5 Publishing and Sharing
Review: Verify calculations, visual clarity, and data accuracy across the dashboard.
Publish: Share the dashboard via Power BI Service for stakeholders, ensuring permissions are set for secure access.

Conclusion
This guide provides a comprehensive approach to analyzing and visualizing customer data for a subscription service. By following these steps, you’ll deliver insights into customer segmentation, popular subscription types, trends in cancellations, and revenue contributions by subscription type. The Power BI dashboard will provide a powerful tool for understanding customer behavior and making informed business decisions.

![image](https://github.com/user-attachments/assets/936b4f70-6a14-49af-a686-0edc1df33b72)

![image](https://github.com/user-attachments/assets/e38c8a07-fe75-4c10-a577-b68661ad2927)

![image](https://github.com/user-attachments/assets/3012bfcf-d112-44cf-aec6-4e926bd904cf)

![image](https://github.com/user-attachments/assets/6ec16ae3-1a64-43ee-be51-8c655762f0b4)



