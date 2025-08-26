# 📊 Project Portfolio Dashboard (Power BI)

## What
This repository contains an example **Power BI dashboard** that helps **company executives monitor and analyze the implementation of a project portfolio**. It is special because it consolidates project performance data (deadlines, costs, tasks, and resource allocation) into one place and provides multiple analytical views:

- **Main**: Portfolio overview with deviations in time, cost, and execution. High-level tasks are also displayed with deviation metrics.
<img src="/images/Main.jpg" alt="Portfolio overview with deviations in time, cost, and execution" width="100%">
 
- **S-Curve**: A chart to evaluate project implementation efficiency.
<img src="/images/S-Curve.jpg" alt="Portfolio overview with deviations in time, cost, and execution" width="100%">

- **Details**: Tables with deliverable readiness and current project tasks, useful for tracking overdue items.
  
<img src="/images/Details.jpg" alt="Portfolio overview with deviations in time, cost, and execution" width="100%">

- **Months**: Tasks from past, current, and upcoming months to assess planning and execution quality.
  
<img src="/images/Months.jpg" alt="Portfolio overview with deviations in time, cost, and execution" width="100%">

- **Costs**: Project costs broken down by resource types and task categories.
  
<img src="/images/Costs.jpg" alt="Portfolio overview with deviations in time, cost, and execution" width="100%">

The dashboard uses project data from the **MS Project Online server**.

---

## Why
This dashboard is designed as a **practical tool for executives** to:
- Control and analyze project portfolio performance.  
- Identify risks in deadlines, budgets, and deliverables.  
- Demonstrate the use of **Power BI for portfolio management reporting**.  

It can also serve as an example for teams learning how to build **multi-page, data-driven dashboards in Power BI**.

---

## Limitation
⚠️ Please note:
- The **Power BI file (.pbix)** is a binary and cannot be viewed directly on GitHub.  
- You will need a **Power BI Desktop (free) or Power BI Pro** instance to open and interact with the dashboard.  
- To connect to your own data, update the `Path` parameter in **Power Query Editor** with your MS Project Online server address.  

---

## How to Run

<img src="/images/Connection.jpg" alt="Connection MS Project Online and MS Power BI" width="100%">

1. Install **Microsoft Power BI Desktop** and log in with your account.  
2. Open the `.pbix` dashboard file.  
3. In Power BI, go to **Data → Get Data → Launch Power Query Editor**.  
4. Replace the sample server link: "htps://studyoberemokii.sharepoint.com/sites/ru/"
   with your own MS Project Online server address.  
5. In the **Home** menu, click **Refresh Preview**.  
6. Adjust portfolio and portfolio types in the **Projects** table, responsible groups in the **Tasks** table, and resource groups in the **Resources** table.  
7. In the **Home** menu, click **Close & Apply**.  

---

