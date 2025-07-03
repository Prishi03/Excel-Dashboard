# 🧾 Customer Support Ticket Dashboard (Excel)

This project is an **interactive Excel dashboard** designed to visualize and monitor customer support ticket data. It is especially useful for support teams, team leads, and analysts to track KPIs and enhance service performance.



## 📌 Features

- 🎯 **KPIs at a Glance**  
  - Total Tickets  
  - Average Resolution Time  
  - High Priority Tickets  
  - SLA Compliance %  
  - Average Survey Rating  
  - Countries Supported

- 📊 **Charts & Visuals**
  - **Ticket Status Overview**: Donut and Gauge chart showing ticket resolution state.
  - **Agent Productivity**: Clustered bar chart comparing SLA met vs. violated tickets.
  - **SLA Trends**: Line chart for monthly SLA compliance (violated vs. met).
  - **Regional Ticket Spread**: Bar chart by country and Tier level.
  - **Most Critical Topic**: KPI callout from pivoted topic-priority data.

---

## 🧠 Insights Derived

- SLA compliance dropped **from 85% in Jan to 62% in Dec** – a **23% decline**.
- **Germany** reported the **highest Tier 2 issues** (244 tickets).
- **Product Setup** was the most critical issue, with **122 high-priority tickets**.

---

## ⚙️ Excel Functions Used

- `INDEX-MATCH`  
  - To dynamically fetch best and worst performing months.
- `TEXT`, `IFERROR`, `MAX`, `MIN`, `AVERAGE`, `COUNTIFS`,`SUM` 
  - For custom metrics like average resolution time, delays, and counts.
- **Pivot Tables**  
  - For aggregating ticket data by month, agent, and priority.
- **Slicers & Buttons**  
  - Month-based filters and toggle between dashboard and filter pane.
- **Conditional Formatting & Icons**  
  - Used to dynamically color SLA % (Green: >80%, Yellow: 60–80%, Red: <60%).
- **Macros**
  - Reset All Filters: A macro-enabled button clears all slicers at once.
  - Navigation Control: Clicking "Filter Pane" opens a new sheet for detailed filters.

---

## 🧩 Tools Used

- Microsoft Excel (Desktop)

---

## 📁 File Structure

```plaintext
📦 Customer-Support-Dashboard/
 ┣ 📊 Dashboard Sheet
 ┣ 🔧 Pivot Views Sheet
 ┣ 📜 Filter Pane Sheet
 ┣ 📄 Helper Sheet (calculations and backend logic)
 ┗ 📂 Dataset (.xlsx or .csv file)
