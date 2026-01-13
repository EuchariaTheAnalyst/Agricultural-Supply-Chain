
# West Africa Agricultural Supply Chain Insights Dashboard
**Excel**

---

## Project Overview

This project analyzes agricultural supply chain performance across West Africa from 2021 to 2025, focusing on how logistics costs and storage losses impact profitability.

Despite increasing agricultural output, many agribusinesses in the region struggle with:

- Rising transportation costs
- Significant post-harvest storage losses
- Shrinking profit margins despite high revenue
- Infrastructure-related inefficiencies

The goal of this analysis is not just to report profits, but to understand where value is lost across the supply chain and why.

To achieve this, a three-page Excel dashboard was designed, with each page answering a distinct layer of the business problem:

1. **Overview** – Regional performance and profitability summary
2. **Crop Performance** – Revenue, profit, and loss comparison by crop
3. **Logistics Analysis** – Cost, distance, transport mode, and infrastructure impact

---

## Problem Statement

Agriculture plays a critical role in West Africa’s economy, yet many agribusinesses experience low realized profit despite strong production output.

Key operational challenges include:

- High transportation costs across long distances
- Significant post-harvest storage losses
- Poor road conditions affecting delivery efficiency
- Limited visibility into how logistics choices impact profitability
- Fragmented reporting that focuses on revenue but ignores loss impact

Without a centralized analytical view, decision-makers struggle to identify where value leaks occur and which operational improvements would yield the highest returns.

---

## Objectives

The objective of this project was to design an interactive Excel dashboard that integrates production, cost, logistics, and loss data to:

- Measure total revenue and profit after storage loss
- Quantify the financial impact of storage loss  percentages
- Compare crop-level performance beyond revenue alone
- Analyze logistics efficiency across transport modes and infrastructure conditions
- Track transport cost trends over time (2021–2025)
- Support data-driven decisions in agricultural logistics and planning

---

## Dataset

The dataset represents agricultural supply chain activities across West Africa from 2021 to 2025.

Each record captures:

- Country
- Crop
- Year
- Season
- Transport Mode
- Road Condition
- Distance (km)
- Input Cost
- Transport Cost
- Storage Loss (%)
- Revenue

Dataset Size: 5,000 records

Region: West Africa

Format: Excel (numeric values stored as numbers)

---

##  Data Preparation & Modeling

The project followed a structured workflow using Excel Pivot Tables, Pivot Charts, formulas, and slicers.
### Step 1.  Data cleaning and Preparation

- Validated numeric fields (costs, revenue, loss percentages)
- Ensured no duplicate or blank rows
- Confirmed correct percentage calculations
- Standardized year and category fields 

### Step 2: Calculations & Metrics

Key calculated fields included:

**Loss Value**
```DAX
Loss Value = Profit Before Loss × Storage Loss %
```

**Profit After Loss**
```DAX
Profit After Loss = Profit Before Loss − Loss Value
```

**Profit Margin (%)**
```DAX
Profit Margin =
(Profit After Loss / Revenue) × 100

```
All calculations were validated at row level before aggregation.

### Step 3: Dashboard Design & Interactivity

- Built dashboards using Pivot Charts and Pivot Tables
- Added slicers for Country, Crop, Year, Transport Mode, and Road Condition


---

## Dashboard Analysis

1.  **Overview — Regional Performance Summary**

<img width="736" height="390" alt="Image" src="https://github.com/user-attachments/assets/defd77b1-7f8f-4fd4-80b4-864663ddd47e" />

---

### Purpose

This page provides a high-level view of agricultural profitability across West Africa, summarizing revenue generation, realized profit after storage loss, and overall efficiency.

### KPIs Interpreted

- Total Revenue reflects the scale of agricultural activity across the region.
- Total Profit After Loss shows how much value remains after storage inefficiencies are accounted for.
- Average Storage Loss (%) highlights how post-harvest handling reduces potential earnings.
- Average Profit Margin (%) measures overall efficiency, not just output volume.

### Visual Analysis

- The country-level revenue and profit comparison shows that revenue concentration does not always align with profitability.
- Some countries dominate total revenue but experience weaker margins due to higher loss rates.
- Other countries generate lower revenue but achieve stronger profit margins through better operational efficiency.

### Insight

The overview analysis confirms that revenue alone is not a reliable indicator of performance. Countries with better loss control and logistics efficiency consistently achieve higher margins, even when total revenue is lower. This establishes efficiency, not scale as a key driver of profitability across the region.

---

2. **Crop Performance Dashboard — Revenue, Profit & Loss by Crop**

<img width="750" height="392" alt="Image" src="https://github.com/user-attachments/assets/baf76f80-266a-470c-858b-b8c53a193b6f" />

---

### Purpose

This page evaluates crop-level performance, focusing on how storage loss and operational efficiency influence profitability beyond gross revenue.

### KPIs Interpreted

- Total Revenue by Crop shows market demand and production scale.
- Profit After Loss captures actual realized earnings.
- Average Storage Loss (%) reveals which crops are most vulnerable to post-harvest deterioration.
- Average Profit Margin (%) measures efficiency per crop.

### Visual Analysis

- High-revenue crops do not consistently rank highest in profit after loss.
- Some crops experience significant profit erosion due to higher storage loss percentages.
- Crops with moderate revenue but lower loss rates often achieve more stable and higher margins.

### Insight

Crop profitability is heavily influenced by storage efficiency, not just demand or price. Focusing solely on revenue can misrepresent performance. Crops with high loss rates represent the largest opportunity for improvement, where better post-harvest management could significantly increase realized profit.

---

3. **Logistics Analysis Dashboard — Cost, Distance & Infrastructure Impact**

<img width="734" height="397" alt="Image" src="https://github.com/user-attachments/assets/c5763b20-26fa-437e-a7d7-ea1743ff0be8" />

---

### Purpose

This page examines how logistics decisions and infrastructure conditions affect agricultural cost efficiency and profitability.

### KPIs & Metrics Interpreted

- Total Transport Cost reflects the operational burden of moving agricultural goods.
- Profit After Loss provides context for evaluating logistics efficiency.
- Loss Percentage by Transport Mode highlights operational risk differences.

### Visual Analysis

- The transport cost trend (2021–2025) shows rising logistics expenses over time, increasing pressure on profit margins.
- The distance vs profit scatter plot indicates that longer transport distances are generally associated with lower profit outcomes.
- Analysis by transport mode shows variation in loss percentages, suggesting that some modes are more efficient than others.
- Road condition vs profit margin reveals that poor infrastructure consistently reduces profitability.

### Insight

Logistics efficiency plays a critical role in agricultural profitability. Rising transport costs, long delivery distances, and poor road conditions collectively erode margins. Optimizing transport mode selection and improving infrastructure quality can significantly reduce losses and improve profit outcomes across the supply chain.

---

## Key Insights

- Storage loss is one of the largest contributors to profit erosion
- Profit after loss is a more reliable performance indicator than revenue
- Transport costs have increased over time, pressuring margins
- Infrastructure quality directly impacts logistics efficiency
- Optimized logistics can offset rising operational costs.

This reinforces the importance of data-driven supply chain optimization in agricultural decision-making.

---

## Recommendations

1. Invest in Post-Harvest Infrastructure:
Reduce loss through better storage and cold-chain systems.

2. Optimize Transport Mode Selection:
Use cost-profit data to prioritize rail or short-distance trucking for certain crops.

3. Infrastructure Development:
Target regions with poor road ratings for road maintenance or alternate routing investments.

4. Seasonal Planning:
Schedule bulk movements during dry seasons where margins are historically stronger.

5. Data-Driven Decision Support:
Integrate such dashboards into policy and private-sector monitoring tools to track logistics efficiency over time.

---

## Conclusion

This Excel dashboard demonstrates that agricultural success is not defined by production volume alone, but by how efficiently crops are stored, transported, and managed across the supply chain.

By integrating logistics, cost, and loss analysis into a unified dashboard, the West Africa Agricultural Supply Chain Insights Dashboard (2021–2025) provides actionable insights to improve profitability, reduce waste, and strengthen agricultural value chains.
