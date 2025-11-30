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
```
## 📊 Visuals & Insights

### 🔹 Summary Page
- **Good Loan Issued:** 86.2%  
- **Bad Loan Issued:** 13.8%  
- **Total Loan Applications:** 38.6K  
- **Total Funded Amount:** $436M  
- **Total Amount Received:** $473M  
- **Average Interest Rate:** 12%  
- **Average DTI:** 13.3%  

---

### 🔹 Overview Page
- Total loan applications by month (Jan–Dec)
- Loan applications by state (US map)
- Loan applications by term (36 vs 60 months)
- Loan applications by purpose  
  (credit card, debt consolidation, home improvement, etc.)
- Loan applications by employment length  
  (1 year, 2 years… 10+ years)
- Home ownership loan comparison  
  (Rent vs Mortgage vs Own)

---

### 🔹 Details Page
A complete loan-level table containing:
- Loan ID  
- Purpose  
- Home Ownership  
- Grade/Sub-grade  
- Issue Date  
- Funded Amount  
- Interest Rate  
- Installment  
- Total Amount Received  

---

## 🎨 Dashboard Design
- Clean, modern layout with a **green financial theme**  
- Easy navigation buttons (Summary, Overview, Details)  
- Slicers for:  
  - State  
  - Grade  
  - Purpose  
  - Good/Bad Loan  
  - Employment Length  
- Consistent typography and high-contrast visuals for

![Summary] ![Image](https://github.com/user-attachments/assets/d37cbcc0-aea8-4097-ac81-12e2d2c03cb7)
![Overview] ![Image](https://github.com/user-attachments/assets/7908244a-3019-424f-8fa3-37d23ef6122e)
![Details] ![Image](https://github.com/user-attachments/assets/62e905db-9cf5-480c-b7be-4814e896927d)


