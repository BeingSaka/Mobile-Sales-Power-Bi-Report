# 📱 Mobile Sales Report Power BI Project

This project features a Power BI dashboard designed to analyze mobile sales transactions. It offers comprehensive insights into sales performance, customer behavior, and product trends, empowering businesses to make data-driven decisions. The interactive visualizations highlight key metrics related to mobile sales, including:

- **Sales Performance:** Analyze total sales, quantity sold, and average price over various periods.
- **Customer Engagement:** Understand customer ratings and their impact on sales.
- **Payment Method Analysis:** Identify popular payment methods and their transaction volume.
- **Product Popularity:** Pinpoint best-selling mobile models and brands.
- **Time-Series Analysis:** Compare current sales with Month-to-Date (MTD) and Same Period Last Year (SPLY) performance.
- **Geographical Sales:** Visualize sales distribution across different cities.

---

## ✨ Key Features

- **Interactive Visualizations:** Explore sales data through dynamic charts, graphs, maps, and filters.
- **Data-Driven Insights:** Discover patterns in mobile sales, customer preferences, and product performance.
- **Improved Decision-Making:** Empower business strategies in marketing, sales optimization, and inventory management.

---

## 📂 Dataset Overview

The core dataset includes the following columns:

- `Transaction ID`
- `Day`, `Month`, `Year`
- `Day Name`
- `Brand`
- `Units Sold`
- `Price Per Unit`
- `Customer Name`
- `Customer Age`
- `City`
- `Payment Method`
- `Customer Ratings`
- `Mobile Model`

---

## 📈 Question KPIs

This dashboard answers key business questions:

- What are the overall total sales, quantity sold, transactions, and average price?
- How do total sales and quantities vary monthly?
- What is the distribution of customer ratings, and how does it impact sales?
- Which payment methods are most used for mobile purchases?
- Which mobile models and brands drive the most sales?
- What are the Month-to-Date (MTD) sales trends?
- How do current sales compare to the Same Period Last Year (SPLY)?
- How do sales figures vary by city?

---

## 📊 Dashboard Pages Breakdown

### 🏠 Home Page

- **KPIs:** Total Sales, Total Quantity, Total Transactions, Average Price
- **Visuals:**
  - Map: Total Sales by City
  - Line Chart: Quantity by Month
  - Funnel: Customer Rating by Rating Status
  - Pie Chart: Transaction by Payment Method
  - Cluster Bar Chart: Sales by Mobile Model
  - Area Chart: Sales by Brand
- **Filters:**
  - Slicers: Mobile Model, Payment Method, Brand
  - Button Slicer: Month
- **Bookmarks:** MTD Report, Same Period Last Year

### 📅 MTD Report Page

- **KPIs:** (Same as Home)
- **Visual:**
  - Large Area Chart: MTD Sales by Day
- **Interactivity:**
  - Button Slicer: Month

### 📉 Same Period Last Year Page

- **KPIs:** (Same as Home)
- **Visuals:**
  - Cluster Column Chart: Sales vs. SPLY by Year
  - Cluster Column Chart: Sales vs. SPLY by Quarter
  - Cluster Column Chart: Sales vs. SPLY by Month

---

## 🧪 Process

### 🔍 Data Collection
- Gathered mobile sales transaction data
- Verified data quality and addressed missing/inconsistent values

### 🧹 Data Cleaning & Transformation
- Cleaned and prepared dataset using Power Query
- Performed necessary transformations and aggregations

### 📊 Data Analysis
- Performed exploratory data analysis (EDA)
- Built DAX measures for key KPIs, MTD, and SPLY calculations

### 🛠 Dashboard Development
- Developed a 3-page interactive Power BI report
- Included advanced visuals and bookmarks for smooth navigation

### ✅ Testing & Refinement
- Validated report accuracy and visual interactions
- Refined based on feedback and usability improvements

---

## 💡 Project Insights

- **[Insight 1: Unveiling the Unexpected]**  
  Contrary to assumptions, *premium mobile models had higher sales in Tier-2 cities*, suggesting a shift in purchasing power and aspirational buying.

- **[Insight 2: Identifying a Key Driver]**  
  Analysis showed that *customer ratings of 5 stars* significantly boosted repeat purchases and overall sales.

- **[Insight 3: Quantifying the Impact]**  
  The *Credit Card payment method* accounted for 60%+ of high-value transactions, indicating a trend toward digital credit over cash.

- **[Insight 4: Predicting Future Trends]**  
  Sales trends predict a *surge in OnePlus and Vivo models* during festive months, helping guide inventory and marketing strategies.

---

## ✅ Final Conclusion

### 📌 Project Overview

This Power BI dashboard delivers actionable insights into mobile sales performance, customer engagement, and product trends, offering a strategic advantage in a competitive market.

### 🛠 Tools Used

- **Microsoft Power BI** for dashboard creation
- **DAX** for time-intelligence calculations (MTD, SPLY)
- **Power Query** for data transformation

### 📈 Project Impact

This project helps mobile retail businesses:

- Improve sales performance tracking
- Optimize inventory and pricing strategies
- Better understand customer preferences

### 🔮 Future Enhancements

- Add **predictive analytics** for forecasting demand
- Integrate **marketing spend data** for campaign effectiveness
- Enable **real-time reporting** with API/database connectivity

---


