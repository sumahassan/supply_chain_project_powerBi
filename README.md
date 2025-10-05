# 🚚 AtliQ Mart Supply Chain Analytics (Power BI)

AtliQ Mart is a growing FMCG manufacturer headquartered in Gujarat, India, currently operating in Surat, Ahmedabad, and Vadodara.  
The company plans to expand into Tier 1 cities but is facing **service-level issues** — some customers have not renewed contracts due to **late deliveries** and **incomplete orders**.  

This project address this issue and build a **Power BI dashboard** to track delivery service levels daily and ensure issues are identified and resolved quickly.

---

## 🎯 Project Objective
- Track **On-time delivery (OT %)**, **In-full delivery (IF %)**, and **On-time In-full delivery (OTIF %)** at a **daily level**.  
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
You can simulate/prepare data in Excel/CSV with the following fields:

![Image alt
](https://github.com/sumahassan/supply_chain_project_powerBi/blob/c13b892ca4962e5ef3c9da79ba932e62b57f3ed6/Data%20Structure.png)
---

## 📊 Dashboard Views
1. **Overall Performance**
   - OT %, IF %, OTIF % across all customers
   - SLA comparison (Actual vs Target)
   - Trend of service levels over time  

2. **Customer-Level Analysis**
   - Daily OT, IF, and OTIF % by customer
   - Customers not meeting SLA targets
   - Repeated service issues  

3. **Product & City Analysis**
   - Service level by Product Category
   - Regional performance (Surat, Ahmedabad, Vadodara)  
![image alt](https://github.com/sumahassan/supply_chain_project_powerBi/blob/main/Supply%20Chain-Power%20Bi%20Dashboard%20Image.png?raw=true)
---

## 🚀 Getting Started
### Prerequisites
- Install [Power BI Desktop](https://powerbi.microsoft.com/desktop/)

### Steps
1. Clone this repository  
   ```bash
   git clone https://github.com/your-username/atliq-mart-supplychain.git
   cd atliq-mart-supplychain
