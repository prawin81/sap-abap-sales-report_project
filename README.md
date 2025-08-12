# 📊 ZSALES_REPORT – ABAP Classical Sales Report

## 📌 Description
`ZSALES_REPORT` is an **ABAP Classical Report** that retrieves and displays **Sales Order Data** from SAP's `VBAK` table based on user inputs such as **Sales Organization** and **Date Range**.  
This project demonstrates how to create **Selection Screens**, fetch data using **Open SQL**, and present results in a **classical list format**.  
It is designed as a practical example for **SAP ABAP beginners** and can be extended for real-world sales analytics.

---

## 🎯 Purpose
- To provide a simple yet practical **Sales Reporting** solution in ABAP.
- To demonstrate **Data Dictionary usage** and **Classical Report formatting**.
- To build a base project that can be enhanced into an **ALV Report** in the future.

---

## 🛠 Features
- User-friendly **Selection Screen**:
  - Sales Organization (`VKORG`)
  - From Date (`ERDAT_LOW`)
  - To Date (`ERDAT_HIGH`)
- Fetches data from SAP's **Sales Document Header Table** (`VBAK`).
- Displays results in neat columns with headers.
- Handles **no-data-found** scenarios with a meaningful message.

---

## 🧾 Technical Details
- **Type**: Classical Report  
- **Module**: SD (Sales & Distribution)  
- **Primary Table**: `VBAK`  
- **Concepts Used**:
  - Selection Screen Parameters
  - Internal Tables & Work Areas
  - Data Dictionary
  - Open SQL
  - Classical List Output

---

## 🚀 How to Run
1. Open **SAP GUI** and go to transaction **SE38**.
2. Create a new program with the name `ZSALES_REPORT`.
3. Copy and paste the ABAP code from this repository.
4. Activate the program (`Ctrl + F3`).
5. Execute (`F8`).
6. Enter:
   - **Sales Organization** (e.g., `1000`)
   - **From Date** and **To Date** in YYYY-MM-DD format.
7. View the results in the classical list output.

---

## 📸 Sample Output


---

## 📚 Learning Outcomes
- Creating **Selection Screens** in ABAP.
- Using **Open SQL** to fetch data from SAP tables.
- Formatting output in **Classical Reports**.
- Handling edge cases where no data is found.

---

## 👤 Author
**Prawin Kumar Mandal**  
SAP ABAP Developer | SAP Global Certified – ABAP - Cloud
📌 [LinkedIn](https://linkedin.com/in/prawin89)  
📌 [GitHub](https://github.com/prawin81)

---
