# 💊 OnyxPharm Global — Pharmaceutical Sales Dashboard
### OnyxData X ZoomCharts Challenge | Power BI

[![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)](https://app.powerbi.com/view?r=eyJrIjoiMjJkN2EwMDMtYjgyYy00MGY2LTgxODQtNjU2MzE2Y2Q1ODcyIiwidCI6IjI1NzYyMjUxLTdhYTktNGM3Mi05MDVmLTM5YmYwMjZhOGE4NCIsImMiOjN9)
![Data Analytics](https://img.shields.io/badge/Data%20Analytics-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)

---

## 📌 Introduction


This project focuses on **120 pharmacy stores** operating across multiple European countries under the brand **ONYXPHARM GLOBAL**. While the chain appeared to be performing well, leadership lacked a unified view of what was truly driving results. Revenue figures existed, promotions were running, and stores were active — but performance insights were fragmented across regions and management levels.

Some countries were growing faster than others. Certain pharmacies were busy but not necessarily profitable. Promotions generated sales, but their true impact on margins remained unclear. Decision-makers needed clarity, not just numbers.

Built as part of the **OnyxData X ZoomCharts Power BI Challenge**, this dashboard was designed to bridge that gap. It provides an integrated, drill-down view from country-level performance to individual pharmacy analysis, highlighting profitability drivers, promotional effectiveness, and operational inconsistencies.

The result is a centralized performance lens that transforms scattered data into actionable insight.

---

## 🎯 Project Objectives

- How are revenue, profit, cost, and quantity performing across all pharmacy locations?
- Which countries, cities, and individual pharmacies are driving the most value?
- How does performance differ between urban, suburban, and rural pharmacy types?
- Are promotional strategies actually contributing to profitability?
- Which products are selling in high volumes but delivering low margins?
- What seasonal demand patterns exist, and how can they inform better planning decisions?
- How can performance be traced from country level all the way down tO individual pharmacies and products?

---

## 🗂️ About the Dataset

The dataset consisted of **4 tables** provided as part of the OnyxData challenge:

| Table | Description |
|---|---|
| Table 1 | `FactSales` |
| Table 2 | `DimProduct` |
| Table 3 | `DimPharmacy` |
| Table 4 | `DimDate` |

- **Time Period:** `[2024 to 2025]`
- **Total Records:** `[62,000 plus rows of data]`
- **Scope:** 120 pharmacies across 8 European countries
- **Source:** OnyxData X ZoomCharts Challenge dataset

---

## 🔧 Data Preparation

All data preparation was performed within **Power BI (Power Query)**:

- `Removed null and duplicate records`
- `Standardized country and city name formatting`
- `Created a calendar/date table for time intelligence`
- `Established relationships between the 4 tables in the data model`
- `Created calculated columns for profit margin and cost ratio`

---

## 📊 Dashboard Pages & Insights

### 1. Overview
High-level performance summary across all 120 pharmacies for 2024 vs 2025.

![Overview Page](images/overview.png)

**Key Metrics:**
| Metric | Value | YOY Change |
|---|---|---|
| Total Revenue | 4.41M | ▲ 4.4% |
| Total Profit | 1.24M | ▲ 4.9% |
| Total Cost | 3.17M | ▲ 4.2% |
| Total Quantity | 228K | ▲ 4.7% |

**Insights:**
- Quantity peaked in **May**, suggesting a strong seasonal demand spike mid-year, with a solid recovery through Q4
- **Germany, Italy, and France** are the top three countries by sales volume
- **OTC and Personal Care** are the dominant product categories, indicating strong consumer-driven demand outside of prescription channels
- All four KPIs grew year-over-year, with **profit growing faster than cost** — a positive signal for margin health

---

### 2. Location & Pharmacy Overview
Geographical and pharmacy-level performance analysis across urban, suburban, and rural locations.

![Location Page](images/location.png)

**Insights:**
- **Urban pharmacies** (50 locations) lead profitability at **42%** of total profit
- **Suburban pharmacies** (47 locations) contribute **39%**, while **Rural pharmacies** (23 locations) contribute **19%**
- **92.68%** of total profit is generated from **non-promotional sales**, suggesting current discounting strategies have minimal positive impact
- Top revenue-generating cities are **Milan, Hamburg, and Utrecht**
- The geographic map reveals revenue concentration in Western and Central Europe, with notable profit clusters in the Netherlands and Belgium

---

### 3. Product Overview
Category, brand, and product-level profitability breakdown.

![Product Page](images/product.png)

**Insights:**
- **Prescription** is the most profitable category at **315K**, followed by **Wellness at 297K**
- **AntiBioX** is the top-performing brand, with **AntiBioX Corticosteroids** leading at the product level
- The **profitability vs. sales volume scatter** reveals a cluster of high-volume, low-margin products — a key optimization opportunity
- **Medical Devices** trail all other categories in both profit and volume
- The decomposition tree enables drill-down from category → brand → product level

---

## 💡 Recommendations

1. **Reassess promotional strategy** — With over 92% of profit coming from non-promotional sales, current discounting delivers minimal return. A targeted, data-driven promo strategy tied to specific products or periods would be more effective.

2. **Focus growth investment on urban locations** — Urban pharmacies generate the highest profit per location. Expanding or upgrading urban sites is likely to yield the strongest ROI.

3. **Address high-volume, low-margin products** — Renegotiating supplier terms or adjusting pricing on these SKUs could meaningfully improve overall profitability.

4. **Capitalize on seasonal peaks** — The May spike and Q4 recovery suggest predictable demand cycles. Better inventory planning around these periods can reduce costs and improve service levels.

5. **Invest in rural pharmacy performance** — Rural locations contribute only 19% of profit. Targeted product mix optimization or operational improvements could unlock untapped value.

6. **Double down on Prescription and Wellness** — These two categories drive the most profit and should be prioritized in assortment planning and supplier negotiations.

---

## ✅ Conclusion

The OnyxPharm Global dashboard delivers a multi-layered view of pharmacy performance — from high-level KPIs down to individual products and locations. The analysis reveals a business growing consistently year-over-year, but with clear opportunities to sharpen its promotional strategy, address low-margin products, and better leverage performance differences across location types. These insights provide a strong foundation for more targeted, data-driven decision-making across commercial and operational functions.

---

## 📁 Repository Structure

```
OnyxPharm-Global-Dashboard/
│
├── README.md
├── OnyxPharm_Global.pbix       # Power BI report file
└── images/
    ├── overview.png
    ├── location.png
    └── product.png
```

---

## 🚀 How to Use

1. Clone or download this repository
2. Open `OnyxPharm_Global.pbix` in **Power BI Desktop**
3. Use the **2024 / 2025 toggle** to switch between years
4. Use the **metric tabs** (Total Cost, Total Profit, Total Quantity, Total Revenue) to explore different KPIs
5. Drill into any visual for pharmacy-level or product-level detail

---

## 👤 Author

**Joshua Achire**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue?style=flat&logo=linkedin)](https://www.linkedin.com/in/joshua-achire)

---

*Built for the OnyxData X ZoomCharts Power BI Challenge*
