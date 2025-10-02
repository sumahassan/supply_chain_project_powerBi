# 🚚 AtliQ Mart Supply Chain Analytics (Power BI)

AtliQ Mart is a growing FMCG manufacturer headquartered in Gujarat, India, currently operating in Surat, Ahmedabad, and Vadodara.  
The company plans to expand into Tier 1 cities but is facing **service-level issues** — some customers have not renewed contracts due to **late deliveries** and **incomplete orders**.  

To address this, the Supply Chain Analytics team built a **Power BI dashboard** to track delivery service levels daily and ensure issues are identified and resolved quickly.

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
- **Target Service Level** → Customer-specific service level agreements (SLA).  
- **Gap Analysis** → Difference between actual service level and target.

---

## 🗂️ Dataset (Sample Structure)
You can simulate/prepare data in Excel/CSV with the following fields:

**Orders Table**
| OrderID | Customer   | City       | OrderDate  | DeliveryDate | PromisedDate | Product       | OrderedQty | DeliveredQty |
|---------|------------|------------|------------|--------------|--------------|---------------|------------|--------------|
| 101     | Customer A | Surat      | 2024-01-05 | 2024-01-07   | 2024-01-07   | Soap          | 100        | 100          |
| 102     | Customer B | Ahmedabad  | 2024-01-08 | 2024-01-10   | 2024-01-09   | Shampoo       | 200        | 180          |
| 103     | Customer C | Vadodara   | 2024-01-09 | 2024-01-09   | 2024-01-09   | Detergent     | 150        | 150          |

**Customer SLA Table**
| Customer   | Target_OT% | Target_IF% | Target_OTIF% |
|------------|------------|------------|--------------|
| Customer A | 95%        | 98%        | 94%          |
| Customer B | 90%        | 95%        | 90%          |
| Customer C | 92%        | 97%        | 91%          |

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

---

## 🚀 Getting Started
### Prerequisites
- Install [Power BI Desktop](https://powerbi.microsoft.com/desktop/)

### Steps
1. Clone this repository  
   ```bash
   git clone https://github.com/your-username/atliq-mart-supplychain.git
   cd atliq-mart-supplychain
