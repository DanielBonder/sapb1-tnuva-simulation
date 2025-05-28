# 🔄 Business Process Modeling for Tnuva

This exercise focuses on modeling two central business processes at **Tnuva**, using the industry standards **BPMN** and **EPC**. These models support the ERP design and validation process in the SAP Business One simulation project.

---

## 🎯 Objective

To provide visual representations of operational workflows for:
- **Business clarity** and documentation
- **ERP implementation readiness**
- **Future test planning and automation mapping**

---

## 🧩 Processes Modeled

### 1. 🕒 Employee Time & Payroll Management *(BPMN)*

This process models the employee's full interaction with the attendance and payroll systems—from registration to payslip delivery.

**Key Elements:**
- Employee registration and contract classification (Type A/B)
- Attendance tracking (entry, shift activities, exit)
- Daily hour reporting and monthly summary
- Payroll calculation: base hours, overtime, deductions, bonuses
- Payslip generation and delivery
- Use of **AND/XOR gateways** and data interactions with the database

📎 File: `bpmn.pdf`

---

### 2. 📦 Supply Chain & Manufacturing *(EPC)*

A structured process flow based on **Event-driven Process Chain (EPC)**, covering order-to-delivery operations.

**Stages Include:**
- Order reception
- Material procurement and stock check
- Production and quality assurance
- Packaging and distribution
- Reporting and legal compliance

📎 File: `EPC.pdf`

---

## 📄 Included Files

| File Name      | Description                                      |
|----------------|--------------------------------------------------|
| `bpmn.pdf`     | BPMN diagram of Employee Time & Payroll Process |
| `EPC.pdf`      | EPC diagram of Supply Chain Process             |

---

## 🧠 Authors

Daniel Bonder, Yossi Chen-Baadash  
Tel-Hai College, 2024

---

> 📌 These process diagrams are used in later stages for test scenario creation and system validation, aligning with SAP Business One ERP implementation strategies.
