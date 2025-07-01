# 🏥 Medical Claims Accounts Receivable Dashboard

This Power BI report provides a comprehensive view of medical claims receivables, helping healthcare finance teams monitor outstanding balances, overdue trends, and payment timelines.

---

## 📊 Key Performance Indicators (KPIs)

The top section of the dashboard showcases the following KPIs:

- **Balance Amount**: Total outstanding claims balance
- **Within Due Amount**: Balance amount not yet overdue
- **Over Due Amount**: Total amount that has passed its due date
- **Over Due Percentage**: Share of overdue claims relative to the total balance
- **Days Sales Outstanding (DSO)**: Average number of days it takes to collect payment after a service is billed

---

## 📈 Visualizations

### 1. 📉 Age Analysis of Due Balance – *Column Chart*
- Shows the distribution of due balances across aging brackets (e.g., 0-30, 31-60, 61-90, 90+ days).
- Highlights where the bulk of receivables are concentrated.

### 2. 🧾 Claim Status – *Donut Chart*
- Displays the proportion of claims by status: Pending, Paid, Denied, Under Review, etc.

### 3. 💰 Actual vs Estimated Cash Flow – *Cluster Column Chart*
- Compares actual cash inflows with estimated forecasts.
- Helps monitor prediction accuracy and spot shortfalls.

### 4. 📆 Monthly Trend – *Line and Stacked Column Chart*
- Tracks **Within Due**, **Over Due**, and **Billed Amounts** month-over-month.
- Offers both trend and breakdown visibility.

### 5. 🔝 Top 10 Procedures by Over Due Amount – *Matrix*
Displays detailed metrics per procedure:
| Procedure Code | Balance Amount | Within Due Amount | Over Due Amount | Over Due % |
|----------------|----------------|--------------------|------------------|-------------|
| XYZ123         | $10,000        | $2,000             | $8,000           | 80%         |

---

## 📁 Files Included

- `MedicalClaimsARDashboard.pbix` – Power BI report file
- `README.md` – This documentation
- *(Optional)* Report screenshots or mockups

---

## 💡 Usage

1. Open the `.pbix` file using Power BI Desktop.
2. Connect to your data source (or use the sample data embedded).
3. Refresh the report to update visualizations.
4. Publish to Power BI Service or share securely.

---

## 🔐 Note

Ensure that patient-identifiable data (PHI) is anonymized or removed before sharing or publishing this dashboard externally to comply with **HIPAA** or relevant privacy regulations.

---

## 📬 Contact

For questions, contributions, or enhancements, feel free to open an issue or pull request.

