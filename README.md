# 🏭 SAP S/4HANA Enterprise Blueprint

## NovaTech Steelworks Ltd. — FI | MM | SD Implementation

---

## 📌 Project Overview

This project presents a complete **SAP S/4HANA Enterprise Blueprint** for a fictional manufacturing company, **NovaTech Steelworks Ltd. (NTSL)**.

The objective is to design and configure an integrated ERP system covering three core SAP modules:

* **FI (Financial Accounting)**
* **MM (Materials Management)**
* **SD (Sales & Distribution)**

The blueprint demonstrates how SAP enables **end-to-end business process integration**, automates transactions, and provides real-time financial visibility.

---

## 🎯 Objectives

* Implement a unified ERP system using SAP S/4HANA
* Automate procurement, sales, and financial processes
* Enable real-time integration across departments
* Improve reporting accuracy and operational efficiency
* Simulate real-world enterprise configuration

---

## 🏢 Company Scenario

**NovaTech Steelworks Ltd. (NTSL)** is a mid-sized manufacturing enterprise operating in India with:

* Two plants: **Pune (NT01)** and **Nagpur (NT02)**
* Centralized procurement system
* Nationwide B2B sales network

The company faced issues like:

* Disconnected systems
* Manual processes
* Inventory inaccuracies
* Delayed financial reporting

This project solves these problems using SAP.

---

## ⚙️ Modules Implemented

### 🔹 FI — Financial Accounting

* Company & Company Code configuration
* Chart of Accounts setup
* G/L Accounts, AP & AR
* GST Tax configuration
* Automatic financial postings

---

### 🔹 MM — Materials Management

* Plant & Storage Location setup
* Vendor Master creation
* Procurement cycle implementation
* Inventory management

---

### 🔹 SD — Sales & Distribution

* Sales Organization & Sales Area
* Customer Master data
* Pricing Procedure
* Order-to-Cash process

---

## 🔄 Business Process Flows

### 📦 Procure-to-Pay (P2P)

1. Purchase Requisition (ME51N)
2. Purchase Order (ME21N)
3. Goods Receipt (MIGO)
4. Invoice Verification (MIRO)
5. Vendor Payment (F110)

✔ Automatic FI integration at each step

---

### 💰 Order-to-Cash (O2C)

1. Sales Order (VA01)
2. Delivery (VL01N)
3. Post Goods Issue (VL02N)
4. Billing (VF01)
5. Customer Payment (F-28)

✔ Revenue and accounting postings generated automatically

---

## 🧠 Key Features

* Real-time integration between FI, MM, and SD
* Automated accounting entries (no manual journals)
* Standardized pricing and tax handling (GST)
* Inventory tracking with real-time updates
* Reduced operational delays and errors

---

## 🛠️ Technology Stack

* **ERP Platform:** SAP S/4HANA
* **Interface:** SAP GUI
* **Database:** SAP HANA
* **Modules:** FI, MM, SD

---

## 📸 Screenshots (Included in Project Folder)

The project includes the following SAP screen references:

* SPRO — Enterprise Structure
* ME21N — Purchase Order
* MIGO — Goods Receipt
* VA01 — Sales Order
* VF01 — Billing
* MIRO — Invoice Verification

---

## 📁 Project Structure

```
NovaTech-SAP-Blueprint/
│
├── report/
│   └── Final_Report.pdf
│
├── screenshots/
│   ├── SPRO.png
│   ├── ME21N.png
│   ├── MIGO.png
│   ├── VA01.png
│   ├── VF01.png
│   └── MIRO.png
│
├── docs/
│   └── Blueprint_Notes.docx (optional)
│
└── README.md
```

---

## ▶️ How to Use / Understand the Project

Since SAP access may not be available:

1. Read the **Final_Report.pdf**
2. Follow the **P2P process flow** step-by-step
3. Observe how each transaction integrates with FI
4. Review screenshots for visual understanding

---

## 🎓 Viva Preparation Tips

* Understand **integration points (MM → FI, SD → FI)**
* Be able to explain:

  * GR/IR concept
  * Pricing procedure
  * Automatic account determination
* Focus on **real-world application** rather than memorization

---

## 🚀 Future Enhancements

* Add **SAP PP (Production Planning)**
* Implement **SAP Fiori (modern UI)**
* Integrate **SAP Analytics Cloud**
* Extend to **HR module (HCM)**

---

## 📌 Conclusion

This project demonstrates how SAP S/4HANA can transform a manufacturing enterprise by integrating finance, procurement, and sales into a single system. The blueprint reflects a realistic implementation approach and highlights SAP’s capability to automate and optimize business operations.

---

## ⚠️ Disclaimer

This is an academic project.
All company names, data, and configurations are fictional and created for learning purposes.

---
