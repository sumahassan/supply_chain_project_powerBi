# 🚚 Supply Chain Analytics for  AtliQ Mart (Power BI)

## 🧰 Tools and Technologies

| Tool | Purpose |
|------|----------|
| **Power Bi** |Interactive dashboard creation and data visualization|
| **Power Query** | Data transformation |
| **DAX** | Calculated measures and KPI creation |
| **CSV Files** | Data storage and import/export |

---
AtliQ Mart is a growing **FMCG manufacturer headquartered in Gujarat, India**, currently operating in **Surat, Ahmedabad, and Vadodara**.  
The company plans to expand into Tier 1 cities but is facing **service-level issues** — several key customers have not renewed contracts due to **late deliveries** and **incomplete orders**.

This project aims to address these issues by building a **Power BI dashboard** to track delivery service performance **daily** and enable the management team to **identify and resolve service gaps quickly**.

---

## 🩺 **Introduction**

AtliQ Mart’s management identified recurring service-level challenges due to inconsistent product delivery.  
This project builds an interactive Power BI dashboard to **monitor On-Time, In-Full, and OTIF delivery metrics** and perform **gap analysis** against customer-specific targets.

---

## 🎯 **Project Objective**

- Track **On-time delivery (OT%)**, **In-full delivery (IF%)**, and **On-time In-full delivery (OTIF%)** at a **daily level**.  
- Compare **actual service levels** against **target thresholds** for each customer.  
- Identify **customers and products** with repeated service-level issues.  
- Provide actionable insights to **improve service quality** before expanding to new markets.  

---

## 📌 **Key Metrics**

| Metric | Description |
|--------|-------------|
| **On-time (OT%)** | % of orders delivered within the promised delivery date. |
| **In-full (IF%)** | % of orders delivered with the complete quantity requested. |
| **On-time In-full (OTIF%)** | % of orders delivered both on-time and in-full. |
| **Line Fill Rate (LIFR%)** | % of order lines shipped out of total order lines placed. |
| **Volume Fill Rate (VOFR%)** | % of total quantity shipped vs. total quantity placed per customer. |
| **Target Service Level** | Customer-specific SLA target by city. |
| **Gap Analysis** | Difference between actual service level and target. |

---

## 🗂️ **Data Structure**

The AtliQ Mart supply chain dataset contains **2 fact tables** and **4 dimension tables**:

- **Fact Tables:**  
  - `order_lines`  
  - `order_aggregate`

- **Dimension Tables:**  
  - `customer`  
  - `product`  
  - `date`  
  - `target_orders`

![Image alt
](https://github.com/sumahassan/supply_chain_project_powerBi/blob/c13b892ca4962e5ef3c9da79ba932e62b57f3ed6/Data%20Structure.png)

Prior to beginning the analysis, a variety of checks were conducted for quality control and familiarity of dataset. Later data model was created.

---

## 📊 Dashboard Views
1. **Overall Performance**
   - OT %, IF %, OTIF % across all customers
   - Regional performance comparision (Surat, Ahmedabad, Vadodara)

2. **Customer and Product Analysis**
   - Daily OT, IF, and OTIF % by customer
   - Service level actual vs target
   - Product category Performance
     
3. **Service Level Trends**
   - Trend of OT%, IF%, OTIF%,VOFR%, LIFR%  over time
   - Monthly and city-wise performance insights
   
![image alt](https://github.com/sumahassan/supply_chain_project_powerBi/blob/054ced2bdde52ac8cac46a70e2321459021dce3a/Supply%20Chain%20-%20Power%20Bi%20Dashboard%20Image.png)
---

## 🔍 Key Insights
- The key service metrics — **OT%, IF%, and OTIF%** — are **below target levels**.
- **OTIF% performance** in **all three cities** is **30% or lower**, which is a major concern.
- From the product-wise analysis, the **Dairy category** has the **highest order volume** but only a **66% line fill rate**, possibly due to limited production capacity.
- In customer performance, **Lotus Mart, Acclaimed Stores, and Coolblue** placed the most orders but also had the **highest delays in delivery**.
- The **overall performance** trend shows **no significant improvement** in any of the key metrics over the past few months.
  
---
