📊 Sales Analytics Dashboard – Power BI

This repository contains a Power BI Sales Analytics Dashboard designed to visualize key business metrics, including sales performance, geographical insights, product categories, and salesperson delivery statistics.

🚀 Overview

The dashboard provides a full analytical view of sales data across multiple dimensions.
It is built using Microsoft Power BI and includes the following interactive visualizations:

🔹 1. Total Sales by Day (Line Chart)

Shows daily sales trends throughout the month.

Helps identify sales spikes, drops, and overall performance patterns.

🔹 2. Total Sales by Geo (Donut Chart)

Displays total sales distribution across geographic regions.

Includes filters for regions such as Australia, Canada, India, UK, USA, and more.

🔹 3. Count of Sales_person by Geo and Product (Map Visual)

Geographic map illustrating salespersons distribution.

Categorized by products (e.g., 50% Dark Bites, 70% Dark Bites).

Note: The map visual type used is being retired soon by Power BI.

🔹 4. Total Sales by Category (Pie Chart)

Shows the portion of total revenue coming from each product category:

Bars

Bites

Other

🔹 5. Delivered Sales by Sales_person (Bar Chart)

Ranks salespersons by delivered sales.

Highlights top performers and underperforming individuals.

🗂️ Data Tables Used

The dashboard uses the following datasets:

Table Name	Description
calendar	Calendar table with date attributes
Geo	Country/Region data
locations	City / Regional mapping
people	People or sales team details
Product	Product-level information
products	Product categories
SalesPerson	Salesperson information
Shipment	Shipment and delivery status
shipments	Shipment details by product/person
Status	Delivery status table
Table6	Supporting dataset
📁 Project Structure
📦 Sales-Analytics-Dashboard
 ┣ 📁 Data              # Raw and clean dataset files
 ┣ 📁 PBIX              # Power BI project files
 ┣ 📄 README.md         # Project documentation
 ┗ 📄 dashboard.pbix     # Final Power BI dashboard file

🔧 Requirements

To view or edit the dashboard, install:

Microsoft Power BI Desktop (Latest Version)
Download: https://powerbi.microsoft.com/

📥 How to Use

Clone the repository:

git clone https://github.com/your-username/sales-analytics-dashboard.git


Open the .pbix file using Power BI Desktop.

Connect or replace data sources if needed.

Explore, filter, and interact with the visuals to gain insights.

🎯 Key Insights You Can Get

Daily sales performance

Regional sales strengths

Best-selling product categories

Salesperson productivity

Delivery performance and shipment patterns

📌 Notes

The map visual used may be deprecated soon—consider updating to the new Power BI map visual.

Some Geo values appear as (Blank) due to missing or incomplete data.
<img width="1356" height="722" alt="image" src="https://github.com/user-attachments/assets/0dced7de-4e15-4bef-a77f-89b0cb267e64" />
