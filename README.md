## sales-analysis
## 📌 Project Overview

This project presents a *complete sales performance analysis* for *Cordial Life Sciences*, a pharmaceutical distribution company. The analysis covers January 2026 sales data — tracking revenue, profit, and margin performance across products, customers, and distribution partners.

The end deliverable is an *interactive Power BI dashboard* built on cleaned Excel data, designed to give business stakeholders fast, actionable answers to performance questions.

| | |
|---|---|
| *Company* | Cordial Life Sciences (Pharma Distribution) |
| *Period* | January 2026 |
| *Data Source* | Internal sales transaction records |
| *Output* | Interactive Power BI Dashboard |
| *Audience* | Sales Manager, Business Head |

---

## 🎯 Business Problem

> "Our sales numbers look healthy — but where is the profit going?"

Despite generating *₹2.29 Million in monthly revenue, Cordial Life Sciences recorded a profit of just *₹23,000** — a margin of *1%. The pharmaceutical industry typically benchmarks at **10–20% net profit margin*.

This analysis was initiated to answer three critical questions:

1. *Why is the profit margin critically low* despite strong sales volume?
2. *Which products, customers, and partners* are driving vs. draining profitability?
3. *What corrective actions* can be taken to improve margin in the next quarter?

---

## 📊 Key Metrics at a Glance

| KPI | Actual | Target | Status |
|---|---|---|---|
| 💰 Total Sales | ₹2.29 Million | ₹2.52 Million | 🔴 9.1% below target |
| 💵 Total Profit | ₹23,000 | — | 🔴 Critically low |
| 📉 Profit Margin | 1% | 10–15% (industry avg.) | 🔴 14x below benchmark |
| 📦 Top Category | Tablets | — | 🟢 Highest profit contributor |
| 🏢 Top Partner | Vasu Pharma | — | 🟢 Highest revenue contributor |
| 📅 Peak Sales Period | Month-end | Consistent | 🟡 Reactive selling pattern |

> ⚠️ *Key Alert:* A 1% profit margin on ₹2.29M revenue means the business is barely breaking even. Every cost increase or discount given directly threatens viability.

---

## 🛠️ Tools & Technologies

| Tool | Version | Purpose |
|---|---|---|
| *Microsoft Excel* | 2021 | Raw data storage, data cleaning, pivot analysis |
| *Power BI Desktop* | Feb 2026 | Dashboard design, DAX measures, interactive visuals |

*Excel techniques used:* Data validation, VLOOKUP, Pivot Tables, conditional formatting, deduplication

*Power BI techniques used:* Data modeling, DAX (calculated columns & measures), KPI cards, slicers, bar/column/line charts, drill-through filters

---

## 🔄 Data Workflow

Raw Sales Data (Excel)
        │
        ▼
┌─────────────────────┐
│   DATA CLEANING     │  → Remove duplicates, fix nulls,
│   (Excel)           │    standardize product names & dates
└─────────────────────┘
        │
        ▼
┌─────────────────────┐
│   DATA MODELING     │  → Build relationships, create
│   (Power BI)        │    calculated columns (margin %, gap)
└─────────────────────┘
        │
        ▼


┌─────────────────────┐
│   DAX MEASURES      │  → Total Sales, Total Profit,
│   (Power BI)        │    Profit Margin %, Target vs Actual
└─────────────────────┘
        │
        ▼

        
┌─────────────────────┐
│  DASHBOARD &        │  → KPI cards, category breakdown,
│  VISUALIZATION      │    company analysis, trend charts
└─────────────────────┘
        │
        ▼

        
   Business Insights & Recommendations


---

## 🔍 Key Insights & Findings

### 1. 📉 Structural Profit Margin Problem

The *1% profit margin* is not a sales problem — it's a *cost structure problem*. High cost of goods sold (COGS) or excessive discounting to distributors is eroding margin before it reaches the bottom line. This pattern is common when companies prioritize volume over value.

*Impact:* At current margins, a 1% increase in COGS would wipe out all profit entirely.

---

### 2. 💊 Tablets: High Revenue, Low Yield

Tablets are the *highest-selling and highest-profit category in absolute terms*, but the ratio tells a different story — top-selling tablets are NOT generating proportional margins. This strongly suggests:
- *Discount leakage* on high-volume SKUs
- Bulk orders from distributors at near-cost pricing
- Possible *pricing strategy misalignment* on bestsellers

*Opportunity:* A 3–5% price correction on top 10 tablet SKUs could significantly boost margin without impacting volume.

---

### 3. 🏢 Partner Concentration Risk — Vasu Pharma

*Vasu Pharma* is the single largest revenue contributor, creating a *dependency risk*. If Vasu Pharma reduces orders, total company revenue drops materially. Other distribution partners are significantly underperforming their potential.

*Opportunity:* Structured growth programs for Tier 2 partners could reduce dependency and grow total revenue by 15–20%.

---

### 4. 📅 Month-End Sales Spike — Reactive Selling

Sales volume spikes sharply at *month-end*, then drops in the first 2–3 weeks. This reactive pattern indicates:
- Sales reps are chasing *end-of-month targets* rather than pipeline building
- Customers are delaying orders, knowing reps will offer discounts to close month
- This behavior *compresses margins* further as last-minute deals include extra discounts

*Opportunity:* Weekly micro-targets with no end-of-month special pricing would normalize margins.

---

### 5. 👥 Bottom-Tier Customer Drain

A segment of small/intermediary customers are purchasing in low volumes but consuming *disproportionate service resources* (delivery, credit, account management). These customers may be *margin-negative* when fully costed.

*Opportunity:* Introduce a *minimum order value policy* or shift bottom-tier customers to a self-service model.
## ✅ Recommendations

| Priority | Action | Expected Impact |
|---|---|---|
| 🔴 *Critical* | Conduct full COGS audit on top 20 SKUs | Identify 5–8% cost reduction opportunity |
| 🔴 *Critical* | Remove blanket discounting for high-volume orders | Recover 2–3% margin immediately |
| 🟡 *High* | Introduce weekly sales targets for reps | Eliminate month-end spike, normalize margins |
| 🟡 *High* | Launch Tier 2 partner growth incentive program | Reduce Vasu Pharma dependency, +15% revenue |
| 🟢 *Medium* | Set minimum order value for small customers | Reduce service cost on low-yield accounts |
| 🟢 *Medium* | Re-price top 10 tablet SKUs by 3–5% | Direct margin improvement on best-sellers |

---

## 📸 Dashboard Preview
<img width="1536" height="865" alt="image" src="https://github.com/user-attachments/assets/b375a17b-7a88-4960-b058-5eccd26403b6" />


The Power BI dashboard includes:
- *KPI Cards* — Total Sales, Profit, Margin %, vs Target
- *Category Breakdown* — Sales & profit by product type (tablets, capsules, syrups, etc.)
- *Company Performance* — Sales contribution by distribution partner
- *Time Trend* — Daily/weekly sales pattern to identify the month-end spike
- *Customer Analysis* — Top customers by revenue and margin contribution

---




## 🧠 Skills Demonstrated


Data Analysis          ████████████████████  Excel Pivot Tables, Data Cleaning
Business Intelligence  ████████████████████  Power BI Dashboard Design
DAX / Formulas         ████████████░░░░░░░░  Calculated Measures, KPI Logic
Data Storytelling      ████████████████████  Insight → Recommendation Pipeline
Domain Knowledge       ████████████░░░░░░░░  Pharma Sales, Distribution Models
Problem Framing        ████████████████████  Root Cause Analysis, Business Lens



 














