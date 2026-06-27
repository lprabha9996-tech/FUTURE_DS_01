# E-Commerce Sales Performance Dashboard

## Project Overview
I built this interactive Power BI dashboard as part of my Data Science & Analytics Internship. The goal was to take a massive, messy raw dataset of over 500,000 global e-commerce transactions and turn it into a clean, professional tool that a business owner could use to make data-driven decisions.

This dashboard answers critical business questions:
* When do sales peak during the year?
* Which specific items bring in the most money?
* Where are our most valuable customers located globally?

---

## Final Dashboard Look
Here is a look at the final dashboard design I created:

![Dashboard Preview](YOUR_UPLOADED_IMAGE_NAME.png)
*(Note: Change 'YOUR_UPLOADED_IMAGE_NAME.png' to the exact name of the screenshot file you uploaded, like 'dashboard.png')*

---

## The Core Numbers (KPIs)
After cleaning out cancellations and missing entries, here is what the business achieved overall:
* **Total Sales Revenue:** $10.67 Million
* **Total Volume Sold:** 5.58 Million individual items
* **Total Orders Processed:** 19,960 unique transactions

---

## Sweet & Short Business Insights

* **Holiday Sales Peak:** Monthly revenue spikes dramatically in November at **$1.51M** due to strong holiday gift-shopping demand. 
  * *Recommendation:* Optimize supply chain and warehouse inventory starting in late Q3 to prevent running out of stock during the holiday rush.
* **UK Market Leader:** The United Kingdom heavily dominates transactions, accounting for **84.6% ($9.02M)** of total global sales. 
  * *Recommendation:* Launch targeted digital ad campaigns in growing secondary markets like the Netherlands and Germany to diversify the business's country risk.
* **Top Hero Product:** The **Regency Cakestand 3 Tier** is the single highest organic revenue-generating item in the inventory, reflecting consistent and massive customer demand.

---

## Tech & Tools I Used
* **Microsoft Power BI:** Used for data modeling, designing layouts, and creating interactive visuals.
* **Power Query:** Cleansed the raw dataset by removing orders with negative values (cancellations), filtering out null IDs, and ensuring correct data types.
* **DAX Formulas:** Wrote a custom expression to map out the accurate count of unique invoices (`DISTINCTCOUNT`) and built calculated columns to evaluate total individual row revenue (`Quantity * UnitPrice`).

---

## How to Interact with My Project
1. Download the `.pbix` file from the file list above.
2. Open it up using **Microsoft Power BI Desktop** (free to download).
3. Try clicking on the **Country Slicer** on the right side! The entire dashboard (the cards, trends, and charts) will instantly filter to show you data for just that specific country.
