# Phase 8: Reporting & Dashboard (Final Setup)  

This phase provides management visibility into revenue, approvals, and payments through reports and dashboards in **RevenueOpsApp**.  

---

## Step 1 — Reports  

### Discount Approvals Report  
- **Action:** Group Discount Approvals by **Status**.  
- **Details:** Show totals for each status (Pending, Approved, Rejected).  
- **Screenshot:**  
  ![Discount Approvals Report](./screenshots/08a_discount_report.JPG)  

### Invoices Report  
- **Action:** Group Invoices by **Status** (Draft, Sent, Paid).  
- **Details:** Summarize **Invoice Amount** for total revenue.  
- **Screenshot:**  
  ![Invoices Report](./screenshots/08b_invoice_report.JPG)  

### Payments Report  
- **Action:** Group Payments by **Payment Mode** (Cash, Card, Online).  
- **Details:** Show amounts per mode.  
- **Screenshot:**  
  ![Payments Report](./screenshots/08c_payment_report.JPG)  

---

## Step 2 — Dashboard  

- **Add Components:**  
  - **Pie Chart → Discount Approvals by Status**  
    - Source: Discount Approvals Report  
    - Value: Record Count  

  - **Bar Chart → Invoices by Status**  
    - Source: Invoices Report  
    - Value: Record Count  

  - **KPI / Metric → Total Revenue**  
    - Source: Invoices Report  
    - Value: Sum of Invoice Amount  

- **Customize Titles & Layout:**  
  - Pie Chart: Discount Approvals by Status  
  - Bar Chart: Invoices by Status  
  - KPI: Total Revenue  

- **Save Dashboard:**  
  - Name: **RevenueOps Dashboard**  
- **Screenshot:**  
  ![Dashboard Setup](./screenshots/08d_dashboard.JPG)  

---

✅ **End of Phase 8 Documentation**  
