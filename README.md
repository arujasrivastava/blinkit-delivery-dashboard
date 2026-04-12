# 📊 Blinkit Delivery Analytics Dashboard

## 🎯 Project Overview

An end-to-end Excel analytics solution analyzing **5,000 Blinkit delivery orders** to identify operational inefficiencies, optimize capacity planning, and uncover revenue opportunities.

This project demonstrates data transformation, multi-dimensional analysis, advanced visualization, and strategic business recommendations.

## 📊 Dashboard Preview
![Dashboard](./screenshots/blinkit_dashboard_1.png)
![Dashboard View 2](./screenshots/blinkit_dashboard_2.png)

---

## 📈 Key Insights Discovered

✅ **50% demand concentration** in morning hours (6 AM - 12 PM) vs only 12% at night  
✅ **Premium customer segment identified** at 11 AM with ₹2,407 AOV (9% above average)  
✅ **Wednesday & Sunday** experience peak orders AND peak delays (capacity constraints)  
✅ **₹33.7L revenue at risk** from delayed orders requiring intervention  

---

## 🛠️ Tools & Technologies

- **Microsoft Excel** (Primary tool)
  - Pivot Tables for multi-dimensional analysis
  - Advanced formulas (COUNTIFS, SUMIFS, table references)
  - Dual-axis combo charts
  - Conditional formatting
  - Data validation
- **Power Query** (Data transformation)
- **Data Visualization** (5 charts)
- **Business Analysis** (Strategic recommendations)

---

## 📊 Dashboard Features

### KPI Cards
![KPI Cards](./screenshots/Kpi_cards.png)

- **Total Orders:** 5,000
- **Total Revenue:** ₹1.10 Crores
- **On-Time Delivery Rate:** 69%
- **Average Order Value:** ₹2,202

### Visualizations

1. **Payment Method Distribution** - Donut chart showing equal split across Card/Cash/UPI/Wallet
2. **Delivery Performance** - Dual-axis combo chart tracking SLA compliance and revenue impact
3. **Weekly Order Pattern** - Stacked column chart highlighting Wednesday & Sunday peaks
4. **Time Period Analysis** - Customer tier distribution across morning/afternoon/evening/night
5. **Hourly Pattern** - Dual-axis chart showing volume and AOV relationship across 24 hours

---

## 🔍 Methodology

### 1. Data Transformation
- Created calculated fields: SLA status, order hour, time period, day of week, value tier
- Categorized deliveries into 4 tiers: Before Time, On Time, Minor Delay, Major Delay
- Segmented customers into value tiers: Low (<₹1K), Medium (₹1K-2.5K), High (₹2.5K-4K), Premium (₹4K+)

### 2. Analysis Approach
- **Temporal Analysis:** Hourly, daily, and time-period patterns
- **Customer Segmentation:** value tier analysis
- **Operational Metrics:** SLA performance, delay quantification
- **Revenue Impact:** Quantified revenue at risk from service issues

### 3. Visualization Strategy
- Brand-aligned design (Blinkit green #0C831F, yellow #F8CB46)
- Dual-axis charts for multi-metric insights
- Conditional highlighting for key findings (Wednesday/Sunday in green)
- Progressive disclosure: KPIs → Charts → Detailed Insights

---

## 💡 Strategic Recommendations

## 📌 Strategy Snapshot

![Strategies](./screenshots/blinkit_strategies.png)

### 1. Capacity Optimization
- Deploy additional delivery partners on **Wednesday & Sunday** to reduce SLA breaches
- Extend promised delivery windows by **5-10 minutes** on high-volume days

### 2. Demand Redistribution  
- Launch **night-hour promotions** (9 PM - 6 AM) with 10-15% discounts
- Introduce **"Monday Specials"** to redistribute Sunday overflow

### 3. Customer Retention
- Target **11 AM premium customers** (₹2,407 AOV) with loyalty programs
- Implement priority delivery for high-value segments

**Expected Impact:** 12-15% improvement in on-time delivery rate

---

## 📁 File Structure
```
blinkit-delivery-dashboard/
├── Blinkit_Dashboard.xlsx          # Main Excel file with 5 sheets
│   ├── Clean_data                  # Transformed dataset (5,000 rows, 16 columns)
│   ├── Metrics                     # Centralized calculations (7 metrics, 4 KPIs)
│   ├── Pivot Analysis              # 5 pivot tables for multi-dimensional views
│   ├── Dashboard                   # Visual presentation layer
│   └── Strategies                  # Business recommendations
├── screenshots/                    # Dashboard visuals
│   ├── blinkit_dashboard_1.png
|   ├── blinkit_dashboard_2.png
│   ├── kpi_cards.png
│   └── blinkit_strategies.png
```

---

## 📊 Data Dictionary

| Column | Description | Example |
|--------|-------------|---------|
| `order_id` | Unique order identifier | 1961864118 |
| `customer_id` | Unique customer identifier | 30065862 |
| `order_date` | Order timestamp | 2024-07-17 08:34:00 |
| `promised_delivery_time` | Expected delivery time | 2024-07-17 08:52:00 |
| `actual_delivery_time` | Actual delivery time | 2024-07-17 08:47:00 |
| `delivery_status` | Original status | On Time / Slightly Delayed / Significantly Delayed |
| `order_total` | Order value in ₹ | 3197.07 |
| `payment_method` | Payment type | Card / Cash / UPI / Wallet |
| `Total_minutes` | Delay in minutes (negative = early) | -5 |
| `Order_hour` | Hour of day (0-23) | 8 |
| `Order_period` | Time category | Morning / Afternoon / Evening / Night |
| `Order_Day` | Day of week | Monday - Sunday |
| `Order_value_tier` | Customer segment | Low / Medium / High / Premium |
| `SLA status` | Enhanced delivery status | Before Time / On Time / Minor Delay / Major Delay |

---

## 🎓 Skills Demonstrated

✅ **Data Cleaning & Transformation** - Created 6 calculated fields for analysis  
✅ **Excel Proficiency** - Pivot tables, advanced formulas, table references  
✅ **Data Visualization** - 5 charts with dual-axis, conditional formatting  
✅ **Business Analysis** - Translated data into actionable recommendations  
✅ **Dashboard Design** - Brand-aligned UI/UX with visual hierarchy  
✅ **Data Storytelling** - Clear narrative from insights to strategy  

---

## 📝 Dataset Information

- **Source:** Kaggle - Blinkit Orders Dataset
- **Period:** March 2023 - November 2024 (18 months)
- **Records:** 5,000 orders
- **Attributes:** 10 original columns + 6 calculated fields

---

## 🚀 How to Use

1. Download `Blinkit_Project.xlsx`
2. Open in Microsoft Excel (2016 or later recommended)
3. Enable macros if prompted (though this workbook doesn't use any)
4. Navigate to **Dashboard** sheet for main view
5. Explore **Pivot Analysis** sheet for detailed breakdowns
6. View **Strategies** sheet for full recommendations

**Note:** The workbook uses Excel Tables. If you want to update data, paste new rows into `Clean_data` sheet and refresh pivot tables.

---

## 🎯 Project Goals Achieved

✅ Identify operational bottlenecks  
✅ Quantify revenue at risk  
✅ Discover customer behavior patterns  
✅ Provide data-driven recommendations  
✅ Create professional, shareable deliverable  

---

## 📧 Contact

**Aruja Srivastava**  
📧 arujawork@gmail.com 
💼 [[LinkedIn](https://www.linkedin.com/in/aruja-srivastava-5197481b9/)

---

## 📄 License

This project is open source and available for educational purposes. Feel free to fork, modify, and use for learning.

---

## 🙏 Acknowledgments

- Dataset sourced from Kaggle
- Dashboard design inspired by Blinkit's brand guidelines
- Project completed as part of personal portfolio development

---

### ⭐ If you found this project useful, please consider giving it a star!
```
