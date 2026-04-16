# Pharmacy Sales Analytics Dashboard | Qlik Sense

## 📌 Project Overview

This project is an interactive **Qlik Sense Sales Analytics Dashboard** built using pharmacy retail transaction data. The dashboard provides actionable insights into sales performance, branch efficiency, medicine demand, customer demographics, and payment behavior.

The goal of this project is to demonstrate practical skills in:

- Qlik Sense Dashboard Development  
- Qlik Data Modeling  
- Data Load Script Development  
- Set Analysis  
- KPI Reporting  
- Business Intelligence Storytelling  

---

## 🏥 Business Use Case

Pharmacy management teams require a centralized analytics solution to monitor business performance across multiple branches.

This dashboard helps answer:

- Which branches generate the highest revenue?
- What are the top-selling medicines?
- Which payment methods are most used?
- How do customer age and gender impact sales?
- Which provinces have the highest demand?
- How are monthly sales trending?

---

## 📂 Dataset Used

The project uses pharmacy transaction-level sales data.

### Key Columns:

- Transaction_ID  
- Transaction_Date  
- Branch_ID  
- Branch_Name  
- District  
- Province  
- Payment_Method  
- Customer_Gender  
- Customer_Age  
- Customer_City  
- Medicine_ID  
- Medicine_Name  
- Generic_Name  
- Medicine_Category  
- Dosage_Form  
- Strength_mg  
- Pack_Size  
- Supplier_Name  
- Prescription_Required  
- Batch_No  
- Expiry_Date  
- Quantity  
- Unit_Price_LKR  
- Discount_Rate  
- Line_Total_LKR  
- Year  
- Month  

---

## 🏗 Solution Architecture

```text
CSV / Excel Source Files
        ↓
Qlik Load Script
        ↓
Data Cleaning & Transformations
        ↓
Qlik Data Model
        ↓
Interactive Dashboards
