# Pharmaceutical Inventory Optimization & Financial Risk Analysis

## Project Overview
Efficient inventory management is critical in pharmaceutical warehouses due to product sensitivity, strict expiration constraints, and high financial risk exposure. This project delivers an end-to-end data analytics solution that uncovers a critical operational paradox: **High sales volume masking a negative net profit due to severe inventory holding costs and waste leakage.**

By implementing a robust Star Schema data model and an interactive Power BI dashboard, this project transitions warehouse operations from reactive stock management to proactive financial optimization.

---

## Interactive Dashboards
| 1. Performance Overview | 2. Profit & Financial Performance |
|---|---|
| ![Overview](https://github.com/hend55-hub/Project-BI-/blob/main/overview.jpg) | ![Financial](https://github.com/hend55-hub/Project-BI-/blob/main/financial.jpg) |

| 3. Stock & Inventory Insights | 4. Risk & Inventory Control |
|---|---|
| ![Inventory](https://github.com/hend55-hub/Project-BI-/blob/main/inventory.jpg) | ![Risk](https://github.com/hend55-hub/Project-BI-/blob/main/Risk.jpg) |

---

## Tech Stack & Data Architecture
- **Data Modeling:** Star Schema (4 Fact Tables, 3 Dimension Tables).
- **Analytics Tool:** Power BI / Power Query.
- **Advanced Frameworks:** ABC Inventory Classification, FEFO (First-Expiry-First-Out) Strategy, and Time Intelligence Analysis (MoM, QoQ, YoY).

### Data Model Structure:
- **Fact Tables:** `Fact_Sales`, `Fact_Purchases`, `Fact_Inventory`, `Fact_Waste`.
- **Dimension Tables:** `Dim_Product`, `Dim_Supplier`, `Dim_Date`.

---

## Key Findings (The Reality of the Data)
- **The Profitability Paradox:** The business generates a massive **$185.94M in Total Sales** with a strong **25.88% Gross Margin ($48.11M)**. However, the **Net Profit is NEGATIVE (-$27.16M)** due to astronomical holding and waste costs.
- **The Waste Leakage:** Total waste loss reached **$56.41M across 10,000 incidents**. 
  - **34% ($19.18M)** is driven by **Cold Chain Failures** (Temperature issues).
  - **33.09% ($18.66M)** is caused by **Damaged goods** during handling.
  - **32.91% ($18.56M)** is lost to **Expired stock**.
- **Critical Categories:** **Therapeutic Tools** and **Sensitive/High Risk** items generate the most revenue but act as the primary risk zones, with **Morphine Sulfate** being the top-risk product.
- **Supply Chain Bottlenecks:** High-risk suppliers (e.g., Group 392, Group 45) exhibit prolonged lead times, forcing the warehouse to overstock, which inadvertently drives up the **30.33% Expiry Rate**.

---

## Actionable Business Recommendations
1. **Cold Chain Overhaul:** Deploy IoT temperature sensors in storage facilities and distribution trucks to prevent the $19.18M loss from Cold Chain Failures.
2. **Storage Handling Standardization:** Revamp storage stacking guidelines for *Therapeutic Tools* to mitigate the $18.66M damage loss.
3. **Automated Expiry Alerts:** Establish a 90-day automated push notification system for nearing-expiry products to trigger early promotional sales and clear stock.
4. **Dynamic Reordering & Supplier Renegotiation:** Transition from fixed ordering to dynamic reorder points based on dynamic lead times, reducing dependence on high-lead-time suppliers.

---
