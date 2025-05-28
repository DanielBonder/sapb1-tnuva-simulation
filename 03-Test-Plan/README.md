# ✅ ERP Test Plan for Payroll and Purchasing Processes

This assignment presents a detailed **test plan** for verifying ERP system behavior in two core business processes at **Tnuva**:  
**1. Employee Time and Payroll Management**  
**2. Procurement and Purchasing Approval**

---

## 🎯 Objective

To define and validate realistic test scenarios for ERP implementation using structured system testing, based on previously modeled business processes (BPMN & EPC).  
The test plan includes:
- Normal operational flows (positive test cases)
- Edge and error cases (negative test cases)
- Expected system behavior and validations

---

## 🔍 Tested Processes

### 🧾 1. Payroll and Attendance Reporting
- Clock-in/out tracking
- Verification of legitimate hours
- Payslip calculation including bonuses and deductions
- System alerts for anomalies (e.g., >24 hours workday)
- Audit logging and data correction flows

### 🛒 2. Procurement Request and Approval
- Employee submits request based on working hours
- Approval and calculation of procurement totals
- Validation of items, pricing, and payment terms
- System updates with procurement documents

---

## 🧪 Sample Test Scenarios

| Type       | Description                                       |
|------------|---------------------------------------------------|
| ✔️ Positive | Employee reports shift correctly, payslip generated |
| ⚠️ Negative | Overreporting hours → system flags and prompts correction |
| ✔️ Positive | Procurement request approved with valid items    |
| ⚠️ Negative | Invalid shift → procurement rejected automatically |

Each scenario includes:
- Input conditions  
- Triggering events  
- Expected system response  
- Verification of data in the database  

---

## 📄 Included File

| File Name                   | Description                             |
|----------------------------|-----------------------------------------|
| `ERP_Tnuva_Test_Plan.pdf`  | Full ERP test plan document in Hebrew   |

---

## 🧠 Authors

Daniel Bonder, Yossi Chen-Baadash  
Tel-Hai College, 2024

---

> 📌 This test plan serves as a foundation for validating ERP workflows and ensuring system reliability under various scenarios prior to go-live.
