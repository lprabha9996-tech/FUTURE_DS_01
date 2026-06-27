# FUTURE_DS_01

Data Science & Analytics Internship – Future Interns

## Task 1: Business Sales Dashboard from E-Commerce Data

### Objective
The objective of this task is to analyze global e-commerce transaction data and develop an interactive sales dashboard to identify key revenue trends, high-performing items, and geographical behavior to support data-driven business decision-making.

### Dataset
**Online Retail Dataset** *Source: Kaggle* The dataset contains transaction-level information for a UK-based retail business, including unique invoice numbers, product descriptions, quantities sold, transaction dates, and buyer locations.

### Tools & Technologies
* Microsoft Power BI Desktop
* Power Query
* DAX (Data Analysis Expressions)

### Data Preparation
The raw transactional data was thoroughly cleaned and prepared using Power Query through the following steps:
* Filtered out cancelled orders and returns by removing records with negative or zero values in the quantity and price fields.
* Ensured data type integrity across all analytical metrics, specifically formatting the transaction field as a Date/Time value.
* Configured a custom calculation metric for individual transaction row revenue by multiplying item quantities by their unit prices.

### Key Analysis Performed
* Created essential Key Performance Indicators (KPIs) to monitor high-level business health: Total Sales Revenue, Total Volume Sold, and Total Unique Orders.
* Analyzed overall revenue trends across months to pinpoint seasonal retail demand patterns.
* Evaluated international market concentration to understand domestic versus global revenue contributions.
* Identified top individual inventory items acting as primary revenue drivers for the business.

### Key Insights
* **Holiday Sales Peak:** Monthly sales experience an aggressive surge during the holiday season, climbing significantly to an all-time peak of **$1.51M in November**, showing clear retail gift-shopping seasonality.
* **UK Market Dominance:** The United Kingdom heavily anchors the company's transaction volume, single-handedly driving **84.6% ($9.02M)** of all global retail revenue.
* **Hero Product Demand:** The **Regency Cakestand 3 Tier** stands out as the single highest revenue-generating product item, showing strong, sustained consumer interest.

### Deliverable
An interactive Power BI dashboard featuring high-level corporate KPIs, a monthly revenue performance trend line, top product revenue horizontal rankings, global sales distribution slices, and summarized strategic business insights.

### How to View the Dashboard
1. Download the `.pbix` dashboard file directly from this repository.
2. Open the file on your local machine using **Microsoft Power BI Desktop**.
3. Use the interactive **Country Slicer** tool on the dashboard workspace to dynamically filter metrics for specific global markets.

---

### Dashboard Preview
![Dashboard Preview](YOUR_UPLOADED_IMAGE_NAME.png)
*(Note: Change 'YOUR_UPLOADED_IMAGE_NAME.png' to the exact name of the screenshot file you uploaded to this folder, like 'image_f56ce9.png')*
