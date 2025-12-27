# Medical Claims Accounts Receivable Dashboard

This Power BI report provides a comprehensive view of medical claims receivables, helping healthcare finance teams monitor outstanding balances, overdue trends, and payment timelines.

**1. The Challenge**

**The Problem:** High month-over-month overdue balances (6+ months) were stalling cash flow. 

**The Cause:** Fragmented data across four systems made it impossible to identify whether delays were caused by insurance denials, patient non-payment, or manual reconciliation lags.

**2. The Solution: Unified Data Architecture**

I engineered a centralized dashboard that bridges the gap between clinical billing and financial posting.

**3. Visual Strategy & Insights**

**Page 1: Executive Operations (The "So What?")**
Focuses on high-level health metrics and identifying the "Big Rocks" slowing down payments.

**Strategic KPIs:** Total Billed vs. Open AR, DSO (Days Sales Outstanding), and % Unpaid.

**Trend Analysis:** A 6-month MoM sparkline comparing Claim Amount vs. Insurance Paid to highlight widening gaps.

**Loss Distribution:** A Donut Chart of Top 5 Denial Reasons and a Stacked Column showing Rejected Amount by Payer Group (Medicare, Commercial, etc.).

**Efficiency Metric:** A 80% Pareto constant line to identify the 20% of procedure codes causing 80% of the rejections.

**Page 2: Tactical Controller (The "Action")**
A self-service drill-through page for the Collections and Claims teams to take immediate action.

**Granular Filters:** Search by Diagnosis Code, Procedure Code, or Patient ID.

**The Worklist:** A detailed table featuring Conditional Formatting for aging claims, allowing staff to prioritize high-value/high-risk recoveries.


