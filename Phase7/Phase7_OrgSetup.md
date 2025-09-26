# Phase 7: Testing & Validation  

This phase validates all automation, triggers, and business rules to ensure end-to-end functionality in the **RevenueOpsApp**.  

---

## Step 1 — Test Discount Approval Trigger  

- **Action:** Created a Quote with a Line Item having Discount > 20%.  
- **Expected Result:** Discount Approval record is automatically created and assigned to the Finance Manager.  
- **Screenshot:**  
  ![Discount Approval Test](./screenshots/07a_discountapproval_test.JPG)  

---

## Step 2 — Approval Process Test  

- **Action:** Logged in as Finance Manager → Opened the Discount Approval record → Approved the request.  
- **Expected Result:** Approval Status updates to **Approved**.  
- **Screenshot:**  
  ![Approval Process Test](./screenshots/07b_approval_test.JPG)  

---

## Step 3 — Validation Rule Test  

- **Action:** Tried creating an Invoice with **Due Date ≤ Invoice Date**.  
- **Expected Result:** Error message appears → *“Due Date must be after Invoice Date”*.  
- **Screenshot:**  
  ![Invoice Validation Test](./screenshots/07c_invoice_validation_test.JPG)  

---

## Step 4 — Invoice + Payment Link Test  

- **Action:** Created an Invoice linked to a Quote.  
- **Expected Result:** Payment record automatically created with:  
  - Amount = Invoice Amount  
  - Payment Date = Invoice Date  
  - Payment Mode = Online  
  - Linked to the Invoice  
- **Screenshot:**  
  ![Invoice Payment Test](./screenshots/07d_invoice_payment_test.JPG)  

---

✅ **End of Phase 7 Documentation**  
