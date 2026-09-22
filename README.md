


# Sales & Profit Dashboard

### Dashboard Link : https://public.tableau.com/app/profile/nilam.salunkhhe/viz/SalesProfitTableau/Dashboard1?publish=yes

## Problem Statement

This dashboard helps a retail superstore business understand its sales performance, profitability, and operational shipping costs across different regions, product categories, states, and order trends. 

Through visual breakdowns, key decision-makers can identify high-performing regions and product lines, analyze order volume fluctuations across months, and locate specific states generating maximum profit. It also provides insights into shipping costs per region, enabling management to evaluate logistical efficiency alongside overall revenue generation.

---

### Steps followed 

- Step 1 : Load data into Tableau Desktop, dataset is an Excel file named `Sample - Superstore Sales (Excel).xls`.
- Step 2 : Verify data types, relationships, and clean fields across orders data.
- Step 3 : Global filters (Slicers) were added at the top for three fields: "Ship Mode", "Customer Segment", and a range slider for "Count of Orders".
- Step 4 : A Line Chart visual was created for "Order By Month" to track order volumes across various months (e.g., January, April, May, July, October, December).
- Step 5 : A visual was created for "Sales by product category" showing sales values for key categories using circle indicators:
  - Furniture: $5,178,591
  - Technology: $5,984,248
- Step 6 : An Area chart was added to represent "Sales by Region" showing total sales distributed across Central, East, South, and West.
- Step 7 : A horizontal bar chart visual was added for "Profit By States" to represent profit contributions across different states (e.g., California, Illinois, Florida, Alabama, etc.).
- Step 8 : A segmented matrix visual was added for "Sales, profit & shipping cost" displaying Sales, Profit, and Shipping Cost metrics across South, East, West, and Central regions.
- Step 9 : In the dashboard design view, headers, text cards, background containers, and color coding were adjusted to structure the final layout.

---

# Snapshot of Dashboard (Tableau)

![Dashboard_Snapshot]
<img width="1654" height="843" alt="dashboard ss" src="https://github.com/user-attachments/assets/3afdbe01-dee4-44ef-a52e-08b4595cbcef" />

---

# Insights

A single page dashboard was created on Tableau Desktop.

Following inferences can be drawn from the dashboard;

### [1] Sales, Profit & Shipping Cost by Region

   a) **Central Region:**
      - Total Sales = $4,699,167
      - Total Profit = $481,891
      - Shipping Cost = $35,394

   b) **East Region:**
      - Total Sales = $3,416,466
      - Total Profit = $317,852
      - Shipping Cost = $25,793

   c) **West Region:**
      - Total Sales = $3,649,748
      - Total Profit = $299,518
      - Shipping Cost = $24,918

   d) **South Region:**
      - Total Sales = $3,150,219
      - Total Profit = $422,507
      - Shipping Cost = $21,726

   thus, Central region generated both the highest overall sales ($4,699,167) and highest profit ($481,891).

### [2] Sales by Product Category

   a) Technology - $5,984,248
   b) Furniture - $5,178,591

   thus, Technology category achieved the highest sales volume.

### [3] Top State Profits

   a) Illinois - $108,532
   b) California - $87,356
   c) Florida - $82,572
   d) Alabama - $53,630
   e) Arkansas - $39,850
   f) Indiana - $33,919
   g) Massachusetts - $30,313

### [4] Order Trend by Month

   - Order volumes hit peak points in May (21,273 / 778 orders) and December (18,241 / 721 orders), while dipping around April (17,270 / 672 orders).
