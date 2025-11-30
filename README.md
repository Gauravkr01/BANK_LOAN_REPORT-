# 🏦 Bank Loan Report – Power BI Dashboard

## 🔗 Dashboard Link  
https://app.powerbi.com/links/fsf6gfsvLa?ctid=6dfff3c8-32df-4c6c-9e01-5dad747e0a22&pbi_source=linkShare

---

## 📌 Project Overview

This Power BI dashboard provides a comprehensive analysis of bank loan applications, funded amounts, received amounts, interest rates, and borrower profiles.  
It helps the bank monitor loan performance, identify trends, evaluate risk, and support data-driven decision-making through interactive visuals.

The report consists of **three pages**:
- **Summary**
- **Overview**
- **Details**

---

## 🎯 Key Objectives

- Track total loan applications and month-over-month changes  
- Analyze funded vs. received amounts  
- Monitor average interest rate and debt-to-income ratio  
- Compare good vs. bad loans  
- Understand loan distribution across states, purposes, terms, and employment length  
- Provide detailed loan-level data for drill-down analysis  

---

## 🛠️ Steps Followed

### **1️⃣ Data Loading**
- Loaded the bank loan dataset into Power BI Desktop.

### **2️⃣ Data Cleaning – Power Query**
- Checked column profiling, data types, and missing values.
- Corrected data inconsistencies and applied formatting.

### **3️⃣ Data Transformation**
Created calculated columns such as:
- **Loan Status Group (Good / Bad Loan)**
- **Employment Length Category**
- **DTI/Interest Formatting**
- **Month Name for Time Series Charts**

### **4️⃣ DAX Measures**
Built dynamic measures including:

- **Total Loan Applications**
- **Total Funded Amount**
- **Total Amount Received**
- **MTD Funded Amount**
- **MoM Growth %**
- **Average Interest Rate**
- **Average DTI**
- **Good Loan %**
- **Bad Loan %**

Example:
```DAX
Total Loan Applications = COUNT(Loans[ID])
