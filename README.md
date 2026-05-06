# 📈 Amazon Retail Sales Performance & Profitability Analysis
### A Business Analyst Case Study

---

## 📌 Business Problem Statement

A retail e-commerce business (Amazon-style) was generating strong revenue but struggling with **inconsistent profit margins across product categories and regions**. Leadership needed clarity on *where* money was being made, *where* it was being lost, and *what* actions could fix it.

**As a Business Analyst, the goal was to:**
- Identify loss-making products and categories draining profitability
- Pinpoint underperforming regions and diagnose root causes
- Surface high-value customer segments worth retaining
- Deliver a decision-ready dashboard for business stakeholders

---

## 👥 Stakeholder Map

| Stakeholder | Role | Interest in This Analysis |
|---|---|---|
| Sales Leadership | Primary | Revenue & profitability trends |
| Category Managers | Primary | Product-level performance |
| Regional Operations | Secondary | Regional efficiency gaps |
| Finance Team | Secondary | Margin optimization |
| Marketing Team | Supporting | High-value customer targeting |

---

## 🛠️ Tools & Tech Stack

| Purpose | Tool |
|---|---|
| Data Source | Excel Dataset (Retail Sales Data) |
| Data Cleaning & Transformation | Power Query |
| KPI Modeling | DAX (Data Analysis Expressions) |
| Visualization & Reporting | Power BI Desktop |

---

## 🧠 Data Preparation & Challenges

- **Data Cleaning:** Removed duplicates, handled nulls, standardized date and category fields
- **DAX Modeling:** Built calculated measures for Profit Margin %, MoM Growth, and Customer Revenue Share
- **Segmentation Logic:** Classified customers into high/medium/low value tiers based on total spend
- **Time Intelligence:** Created rolling sales trends using DAX time functions for MoM and QoQ analysis

---

## 📊 Dashboard Preview

![Sales Dashboard](Dashboard.png)

---

## 📈 Key Business Insights

### 1. 🔴 Furniture Category — High Sales, Negative Profit
> **Finding:** Furniture (especially Chairs and Tables) showed strong sales volume but consistently negative or near-zero profit margins.
>
> **Business Impact:** Pricing strategy and supplier costs need urgent review. Continuing current trajectory erodes overall profitability.

### 2. 🟢 Technology — Star Performer
> **Finding:** Technology emerged as the most profitable category with healthy margins across sub-categories like Phones and Accessories.
>
> **Business Impact:** Increased marketing investment in Technology could yield the highest ROI.

### 3. 🟠 Central Region — Operational Inefficiency
> **Finding:** Central region had comparatively lower profitability despite reasonable sales volume.
>
> **Business Impact:** Logistics costs or discount strategies in this region likely require optimization.

### 4. 🔵 Q4 Seasonal Spike
> **Finding:** Sales showed consistent spikes during Q4, likely driven by festive and holiday demand.
>
> **Business Impact:** Demand forecasting and inventory planning should be built around Q4 peaks.

### 5. 🟡 High-Value Customer Concentration
> **Finding:** A small group of customers contributed disproportionately to total revenue.
>
> **Business Impact:** No formal retention or loyalty strategy exists for these customers — a major risk.

---

## ✅ Business Recommendations

| Priority | Recommendation | Expected Impact |
|---|---|---|
| 🔴 High | Revise pricing strategy for Furniture — especially Chairs & Tables | Restore positive margin in loss-making sub-categories |
| 🔴 High | Launch VIP retention program for top 10% customers | Reduce churn risk on highest-revenue accounts |
| 🟡 Medium | Increase marketing budget for Technology category | Maximize returns from highest-margin category |
| 🟡 Medium | Audit Central region logistics and discount policies | Improve regional profitability |
| 🟢 Low | Build Q4 demand forecast model for inventory planning | Reduce stockouts and overstock costs |

---

## 📋 BA Artifacts Produced

- ✅ Power BI Interactive Dashboard (.pbix)
- ✅ Cleaned Sales Dataset (Excel)
- ✅ DAX Measures Documentation
- ✅ Stakeholder Analysis
- ✅ Recommendations Summary

---

## 🚀 How to View the Dashboard

1. Download the `Sales Analytics Dashboard.pbix` file from this repository
2. Open using **Power BI Desktop** (free download)
3. Use filters to explore by Region, Category, and Time Period
4. KPI cards show real-time Total Sales, Profit, Orders, and Profit Margin

---

## 💡 Key Learnings & BA Skills Demonstrated

- **Stakeholder Analysis** — Mapped business users and their reporting needs
- **KPI Definition** — Defined and built measurable business metrics using DAX
- **Root Cause Analysis** — Diagnosed why Furniture profits were negative
- **Data Storytelling** — Translated dashboard numbers into business narratives
- **Prioritized Recommendations** — Ranked actions by business impact and feasibility

---

## 👤 About

**Shrutik Pandey** | Aspiring Business Analyst
📧 Connect on [LinkedIn](https://linkedin.com/in/shrutikumaripandey) | 🌐 [Portfolio](https://shrutikpandey.github.io)

---

*This project was built as part of a BA portfolio to demonstrate end-to-end business analysis — from raw data to boardroom-ready insights.*
