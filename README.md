# Contribution of Coal Industry to Economic Growth in Jharia Block

## 📌 Project Overview
This project presents an empirical case study and data analysis on the role of the coal mining industry in Dhanbad district, Jharkhand, focusing on the Jharia coalfield region. Dhanbad, recognized as the "Coal Capital of India," serves as the core hub for high-grade coking coal vital for India's steel and thermal power industries. 

The analysis investigates multi-year production output trends, mine-level operational variations, direct state fiscal contributions (Royalty and DMFT collections), and the socio-environmental external costs (air pollution and mine hazards) associated with mining operations.

---

## 🎯 Objectives
- Assess Jharkhand's raw coal production trends and national market share from 2012 to 2022.
- Evaluate the operational scale, dispersion, and capacity of individual producing coal mines across the Jharia Coalfield.
- Analyze state fiscal revenue trends generated through Coal Royalties and the District Mineral Foundation Trust (DMFT) between 2017 and 2023.
- Measure the correlation between physical coal extraction volumes and fiscal revenues collected.
- Examine environmental trade-offs, focusing on ambient winter particulate matter concentrations ($PM_{10}$ and $PM_{2.5}$) and mine safety challenges.

---

## 🛠️ Tools & Methodology
- **Research Design:** Descriptive and empirical case study combining secondary institutional data with qualitative field observations.
- **Statistical Tools & Techniques:** Computed descriptive statistics (**Mean**, **Median**, **Standard Deviation**, and **Min–Max Range**) to evaluate operational skewness across mines, and applied **Pearson Correlation Analysis ($r$)**.
- **Data Analysis & Processing:** **Microsoft Excel** (data cleaning, metric computation, descriptive statistics, and correlation analysis).
- **Documentation & Report Design:** **Microsoft Word** (document structuring, typography, visual layouts, and publication formatting).
- **AI Research & Synthesis Assistant:** Google NotebookLM (source analysis, conceptual roadmaps, and section synthesis).
- **Data Sources:** 
  - Coal Controller's Organization (Ministry of Coal, Government of India)
  - Coal India Limited (CIL) & Bharat Coking Coal Limited (BCCL)
  - CEIC Data & Ministry of Coal Reports
  - Jharkhand State Pollution Control Board (JSPCB)

---

## 📊 Key Findings & Insights

### 1. Production Output vs. National Share (2012–2022)
- Jharkhand's raw coal production increased from **111.27 MT** (2012–13) to **130.10 MT** (2021–22), reaching a peak of **134.67 MT** in 2018–19.
- Despite absolute growth, Jharkhand's national production share declined steadily from **20.00%** to **16.72%** over the decade, reflecting accelerated production expansion in other states such as Madhya Pradesh.

### 2. Mine-Level Production Skewness (Jharia Coalfield)
- **Mean Output:** 1.12 MT per mine
- **Median Output:** 0.56 MT per mine
- **Standard Deviation:** 1.45 MT (indicating wide operational variance)
- **Distribution:** Production across 15 key operations spans from **0.005 MT** to **5.36 MT**. A small number of large operations (such as Amalgamated BOCP at 5.36 MT, AMP Colliery at 4.86 MT, and NTST-Jeenagora at 4.77 MT) drive the bulk of total output, pulling the average well above the median.

### 3. State Fiscal Revenue & DMFT Contributions (2017–2023)
- From 2017 to 2023, the coal sector generated **₹21,912.95 Crores** in Coal Royalties and **₹6,077.78 Crores** for the District Mineral Foundation Trust (DMFT).
- Following a decline during FY 2020–21 (₹2,879.95 Cr), royalties rebounded sharply by 63% to reach **₹4,704.14 Crores** in 2022–23, with DMFT collections reaching **₹1,384.32 Crores**.

### 4. Correlation & Fiscal Decoupling
- **Production vs. Royalty ($r = -0.29$):** Demonstrates a weak negative correlation, confirming that state royalty receipts are more heavily governed by coal grade mix, notified price revisions, and market demand rather than extraction volume alone.
- **Production vs. DMFT ($r = 0.07$):** Indicates a negligible linear relationship, showing that local development fund growth functions independently of year-over-year production shifts due to statutory collection formulas.

### 5. Environmental & Social Externalities
- Winter particulate monitoring across 14 monitoring stations in the Jharia Coalfield indicates that ambient concentrations of both $PM_{10}$ and $PM_{2.5}$ consistently breach National Ambient Air Quality Standards (NAAQS).
- Enduring coal seam fires, land subsidence risks, and displacement continue to impose local socio-economic and public health costs.

---

## 📈 Visualizations Included

| Chart Name | File Location | Key Metric |
| :--- | :--- | :--- |
| **Jharkhand Raw Coal Output vs. National Share** | `assets/jharkhand_raw_coal_output_vs_national_share.png` | 10-Year volume vs. national market share |
| **Top 15 Producing Coal Mines** | `assets/top15_producing_mines_jharia.png` | Mine-level output in Million Tonnes (MT) |
| **Coal Royalty & DMFT Revenue Trends** | `assets/coal_royalty_and_dmft_trends.png` | Fiscal receipts in INR Crores (2017–2023) |

---

## 📁 Repository Structure
```text
├── README.md
├── Jharia_Coal_Industry_Economic_Analysis.pdf
├── data/
│   ├── production_vs_share_2012_2022.csv
│   ├── top15_producing_mines.csv
│   └── coal_royalty_and_dmft_2017_2023.csv
└── assets/
    ├── jharkhand_raw_coal_output_vs_national_share.png
    ├── top15_producing_mines_jharia.png
    └── coal_royalty_and_dmft_trends.png
```
---

## 📊 Preview

### 1. Jharkhand Raw Coal Output vs. National Share (2012–2022)
*A 10-year comparative dual-axis visualization demonstrating rising regional extraction volume alongside a contracting national market share.*

<p align="center">
  <img src="assets/jharkhand_raw_coal_output_vs_national_share.png" alt="Jharkhand Raw Coal Output vs National Share" width="850">
</p>

- **Volume Growth:** Rose from **111.27 MT** in FY 2012–13 to **130.10 MT** in FY 2021–22.
- **National Contraction:** State share declined from **20.00%** down to **16.72%** due to faster capacity additions in competing states.

---

### 2. Mine-Level Production Skewness (Jharia Coalfield)
*Bar chart of the top 15 producing operations in Jharia, illustrating significant output concentration.*

<p align="center">
  <img src="assets/top15_producing_mines_jharia.png" alt="Top 15 Producing Mines Jharia" width="850">
</p>

- **Top Producers:** Led by Amalgamated BOCP (**5.36 MT**), AMP Colliery (**4.86 MT**), and NTST-Jeenagora (**4.77 MT**).
- **Statistical Variance:** Mean output (**1.12 MT**) significantly exceeds median output (**0.56 MT**), driven by a high standard deviation ($\sigma = 1.45$ MT).

---

### 3. Coal Royalty and DMFT Revenue Trends (2017–2023)
*Annual fiscal inflows generated for state revenue and the District Mineral Foundation Trust.*

<p align="center">
  <img src="assets/coal_royalty_and_dmft_trends.png" alt="Coal Royalty and DMFT Revenue Trends" width="850">
</p>

- **Cumulative Inflows:** Over **₹21,912.95 Cr** collected in royalties and **₹6,077.78 Cr** under DMFT mandates.
- **Post-Pandemic Surge:** Strong rebound from a FY 2020–21 low (₹2,879.95 Cr) to a peak of **₹4,704.14 Cr** in FY 2022–23.

---

## 👤 Author
Arnab Sinha  
Website: https://arnabsinha.wuaze.com  
Aspiring Data Analyst
