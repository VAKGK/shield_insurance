# 🛡️ Shield Insurance Power BI Project

### **Daily Growth & Policy Trend Analysis**

[![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=power-bi&logoColor=black)](https://powerbi.microsoft.com/)
[![Data Analytics](https://img.shields.io/badge/Data%20Analytics-005C84?style=for-the-badge&logo=google-analytics&logoColor=white)]()
[![Status](https://img.shields.io/badge/Status-Completed-success?style=for-the-badge)]()

---

## 📖 Overview

**Insurance is a fast-moving industry where daily trends matter.** This project was designed for **Shield Insurance** to provide real-time visibility into their growth metrics.

The primary objective was to move beyond static reporting and create a dynamic dashboard that tracks **daily revenue and customer growth rates**. By monitoring these fluctuations alongside month-over-month policy changes, the management team can now identify trends immediately and spot areas for operational improvement.

> *"From monthly summaries to daily actionable insights."*

---

## 🎯 Key Metrics Tracked

To gauge the pulse of the business, I focused on four critical growth indicators:

* **📅 RPM (Revenue Per Month):** The total revenue generated within a specific month, allowing for MoM comparisons.
* **👥 CPM (Customer Per Month):** The total count of new customers acquired within a specific month.
* **📈 DCG (Daily Customer Growth):** A granular metric tracking the percentage increase/decrease in the customer base day-over-day.
* **💰 DRG (Daily Revenue Growth):** A granular metric tracking the daily velocity of revenue generation.

---

## ⚙️ The Workflow

The solution involves transforming raw daily transaction data into growth trends.

```mermaid
graph TD;
    A["📂 Daily Insurance Data\n(Policies, Premiums)"] -->|Import| B{"⚙️ Power BI\nData Transformation"};
    B -->|Time Intelligence| C["🗓️ Date Table & Period Analysis\n(MoM, DoD Logic)"];
    C -->|DAX Measures| D["🧮 KPI Engine\n(RPM, CPM, DCG, DRG)"];
    D -->|Visualization| E["🛡️ Shield Dashboard\nGrowth Monitor"];

    style A fill:#f9f,stroke:#333,stroke-width:2px
    style C fill:#bbf,stroke:#333,stroke-width:2px
    style E fill:#bfb,stroke:#333,stroke-width:2px
