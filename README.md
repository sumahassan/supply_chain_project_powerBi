# 🚚 AtliQ Mart Supply Chain Analytics (Power BI)

AtliQ Mart is a growing FMCG manufacturer headquartered in Gujarat, India, currently operating in Surat, Ahmedabad, and Vadodara.  
The company plans to expand into Tier 1 cities but is facing **service-level issues** — some customers have not renewed contracts due to **late deliveries** and **incomplete orders**.  

This project address this issue and build a **Power BI dashboard** to track delivery service levels daily and ensure issues are identified and resolved quickly.

---

## 🎯 Project Objective
- Track **On-time delivery (OT %)**, **In-full delivery (IF %)**, and **On-time In-full delivery (OTIF %)** at a daily level.  
- Compare actual service levels against **target thresholds** set for each customer.  
- Identify **customers/products with repeated issues** to improve service quality before expanding to new markets.

---

## 📌 Key Metrics
- **On-time (OT %)** → % of orders delivered within the promised delivery date.  
- **In-full (IF %)** → % of orders delivered with the complete quantity requested.  
- **On-time In-full (OTIF %)** → % of orders delivered both on-time and in-full.
- **Line-fill-rate (LIFR %)** → % of Lines of orders shipped out of lines of order placed.
- **Volume-fill-rate (VOFR %)** → % of total quantity shipped vs total quantity placed per customer.
- **Target Service Level** → Customer-specific service level agreements split by cities.  
- **Gap Analysis** → Difference between actual service level and target.

---

## 🗂️ Data Structure
Atliq Mart supply chain data consist of 2 fact tables and 4 dimention tables: order lines table, order aggregate table, customer table, product table, date table, target orders table.

![Image alt
](https://github.com/sumahassan/supply_chain_project_powerBi/blob/c13b892ca4962e5ef3c9da79ba932e62b57f3ed6/Data%20Structure.png)

Prior to beginning the analysis, a variety of checks were conducted for quality control and familiarity of dataset. Later data model was created.

---

## 📊 Dashboard Views
1. **Overall Performance**
   - OT %, IF %, OTIF % across all customers
   - Regional performance (Surat, Ahmedabad, Vadodara)

2. **Customer and Product Level Analysis**
   - Daily OT, IF, and OTIF % by customer
   - Customer service level actual vs target
   - Service level by product category
     
3. **Service Level Analysis**
   - Trend of service levels over time
   
![image alt](https://github.com/sumahassan/supply_chain_project_powerBi/blob/054ced2bdde52ac8cac46a70e2321459021dce3a/Supply%20Chain%20-%20Power%20Bi%20Dashboard%20Image.png)
---

## 🔍 Key Insights
- The key service metrics — OT%, IF%, and OTIF% — are below target levels.
- OTIF% performance in all three cities is 30% or lower, which is a major concern.
- From the product-wise analysis, the Dairy category has the highest order volume but only a 66% line fill rate, possibly due to limited production capacity.
- In customer performance, Lotus Mart, Acclaimed Stores, and Coolblue placed the most orders but also had the highest delays in delivery.
- The overall performance trend shows no significant improvement in any of the key metrics over the past few months.
  
---
