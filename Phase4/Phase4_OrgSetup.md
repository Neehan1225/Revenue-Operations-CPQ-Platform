# RevenueOpsApp – Phase 4: Automation & Reporting  

In this phase, automation was implemented using approval processes and flows, and custom reports/dashboards were created to analyze Discount Approvals.  

---

### 1. Approval Process – Discount Approval  
- Created an **Approval Process** for Discount Approvals > 20%.  
- Auto-routed such records to the Finance Team for review.  
- Steps:  
  - Entry Criteria: Requested Discount% > 20  
  - Approver: Finance Team Queue  
  - Final Action: Update Approval_Status__c = Approved/Rejected  
- **Screenshot:**  
  ![Approval Process](./screenshots/01_approval_process.JPG)

---

### 2. Flow – Auto Update Approval Status  
- Built a **Record-Triggered Flow** on Discount Approval.  
- If discount ≤ 20%, auto-update status to **Approved**.  
- Eliminates manual approvals for small discounts.  
- **Screenshot:**  
  ![Flow Setup](./screenshots/02_flow_setup.JPG)

---

### 3. Test Flow Execution  
- Created Discount Approvals with discount ≤ 20%.  
- Verified status auto-changes to **Approved**.  
- **Screenshot:**  
  ![Flow Test](./screenshots/03_flow_test.JPG)

---

### 4. Report – Discount Approvals by Status  
- Built a **Custom Report** showing:  
  - Pending Approvals  
  - Approved Approvals  
  - Rejected Approvals  
- Helps management track approval bottlenecks.  
- **Screenshot:**  
  ![Discount Report](./screenshots/04_discount_report.JPG)

---

### 5. Dashboard – Approval Summary  
- Added a **Dashboard** with charts for Discount Approvals.  
- Visualized approval distribution across team members.  
- **Screenshot:**  
  ![Approval Dashboard](./screenshots/05_approval_dashboard.JPG)

---


✅ **End of Phase 4 Documentation**  
