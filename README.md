# Strategic Project Management Analytics Dashboard (Power BI)

## Executive Summary
This project delivers a comprehensive, data-driven **Project Portfolio Dashboard** built using **Power BI**. The dashboard enables Project Management Offices (PMO) and executive leadership to monitor project execution, evaluate financial performance ($874M in total benefits vs. $412M in costs), track department-level progress, and optimize resource allocation across 99 multi-regional projects.

---

## Dashboard Overview
![Project Management Dashboard](Project_Management_Dashboard_Screenshot.png)

---

## Key Business Questions Addressed
1. **Financial Viability:** Are our project portfolios generating an optimal Return on Investment (ROI)?
2. **Operational Efficiency:** Which departments and project phases have the highest completion rates, and where are the bottlenecks?
3. **Managerial Workload & Performance:** How is project management volume distributed among project managers?
4. **Risk & Complexity:** What is the distribution of project complexity (High, Medium, Low) across our regions?
5. **Geographic Strategy:** Where are our active projects concentrated geographically?

---

## Key Metrics & Insights (KPIs)
- **Total Project Benefit:** **$874M** (Measuring the overall economic gain)
- **Total Project Cost:** **$412M** (Tracking global expenditure)
- **Total Projects Handled:** **99 Projects** across multiple sectors
- **Average Project Completion Rate:** **86.14%**
- **Top Performing Department:** **Supply Chain** led in overall completion percentage (21.10%), followed by **Warehouse** (20.12%) and **eCommerce** (17.14%).
- **Geographic Concentration:** The **North Region** accounts for the largest share of total projects (**34.34%**), followed by the **West Region** (**24.24%**).

---

## Tech Stack & Features
- **Business Intelligence Tool:** Microsoft Power BI
- **Data Modeling & DAX:** Custom calculated columns and aggregated measures for financial margins and completion rates.
- **Visuals & Interactivity:**
  - **Decomposition Tree:** For interactive root-cause analysis of completion rates broken down by Department and Phase.
  - **Geospatial Mapping:** Integrated Bing Maps visual for regional project tracking.
  - **Bar & Donut Charts:** For complexity breakdowns and project manager allocation.
  - **Multi-Level Slicers:** Interactive filtering by `Year`, `Status`, `Department`, and `Region`.

---

## Repository Structure
```text
├── Data/                        # Raw or processed dataset files
├── Screenshots/                 # High-resolution dashboard screenshots
├── Project_Management.pbix      # Main Power BI file
└── README.md                    # Project documentation
