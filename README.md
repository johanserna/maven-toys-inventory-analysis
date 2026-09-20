# 📦 Maven Toys — Inventory & Replenishment Analysis

Power BI portfolio project built with **synthetic retail data** to simulate a real inventory and replenishment problem.

> **What products should be replenished, in which stores, and how many units should be ordered?**

![Dashboard Overview](images/overview.png)

## 🎯 Business Problem

For this fictional retail scenario, sales, product, store and inventory data were created to simulate a common business challenge: identifying **where stock shortages could occur and what should be replenished first**.

I built a Power BI solution that transforms this data into inventory and replenishment recommendations.

**Sales Files → Power Query → Data Model → DAX → Dashboard**

Using recent sales and current stock, the report estimates:

- Average daily demand
- Inventory coverage
- Reorder point
- Target stock
- Suggested order quantity

The scenario assumes **7 days of delivery time, 3 days of safety reserve and 14 additional days of coverage**.

## 📊 Dashboard Overview

The main dashboard shows where inventory pressure is concentrated and which stores require the largest replenishment orders.

![Dashboard Overview](images/overview.png)

## 🚨 Replenishment Priorities

Products are prioritized according to their inventory situation:

**Out of Stock → Urgent → Replenish**

This helps identify which products require immediate attention and how many units should be ordered.

![Replenishment Center](images/centro_reposicion_1.png)

## 🔎 Product Detail

Users can drill through to a specific product and store to understand **why a replenishment order is being recommended**.

The detailed view compares:

- Current stock
- Recent sales
- Average daily demand
- Inventory coverage
- Reorder point
- Target stock
- Suggested order quantity

![Product Detail](images/detalle_producto_tienda_1.png)

## 🔄 Data Preparation

Sales files were consolidated and cleaned using **Power Query** and then connected with product, store and inventory information in Power BI.

The workflow allows new sales files to be incorporated through a refresh instead of rebuilding the analysis manually.

## 🛠️ Tools

**Power BI · Power Query · DAX · Data Modeling · Excel/CSV**

## 📁 Power BI File

`Maven_Toys_Inventory_Analysis.pbix`

---

### About

This is a **fictional portfolio project built with synthetic data**.

Maven Toys is used as a simulated retail business to demonstrate how Power BI, Power Query and DAX can transform operational data into practical inventory and replenishment decisions.
