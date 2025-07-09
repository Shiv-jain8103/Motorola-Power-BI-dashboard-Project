# 📊 Motorola Mobile Sales Dashboard – Power BI Project

This project is an interactive Power BI dashboard created to analyze and visualize Motorola mobile phone sales across various cities in India. It provides deep insights into total sales, quantity sold, transactions, customer behavior, and payment trends using visually appealing and dynamic reports.

---

## 🚀 Project Overview

The Motorola Sales Dashboard offers a comprehensive view of mobile sales performance over the year, helping stakeholders make data-driven decisions. It enables filtering by months, cities, payment methods, mobile models, and brands.

### ✅ Key Features

- **Total Sales, Quantity, and Transactions Overview**
- **City-wise Sales Visualization** (Map)
- **Monthly Quantity Trend Line**
- **Customer Ratings Distribution**
- **Sales by Mobile Models & Brands**
- **Sales by Day Name**
- **Payment Method Breakdown** (Pie chart)
- Interactive slicers for:
  - Month
  - Mobile Model
  - Payment Method
  - Brand
  - Day of the Week

---

## 🧠 Tools & Technologies Used

- **Microsoft Power BI Desktop**
- **DAX (Data Analysis Expressions)** for calculated measures and KPIs
- **Power Query** for data cleaning and shaping
- **Custom Visuals** like map, line chart, bar chart, pie chart

---

## 🧮 DAX Measures Included

- `Total Sales = SUM(Sales[Amount])`
- `Total Quantity = SUM(Sales[Quantity])`
- `Total Transactions = COUNTROWS(Sales)`
- `Average Sales = [Total Sales] / [Total Transactions]`
- `5-Star Ratings = CALCULATE(COUNTROWS(Customer), Customer[Rating] = 5)`
- Dynamic measures used for time-based trends (Monthly, Daily) and filtering

---

## 📌 Insights Derived

- **Saturdays** have the highest average sales, while mid-week days show slight decline.
- **UPI** and **Credit Card** are the most used payment methods.
- Top cities with high sales include **Mumbai**, **Delhi**, **Bangalore**, and **Chennai**.
- Positive skew in customer satisfaction with majority giving 4-5 stars.

---

## 📂 File Structure

- `Screenshot.png` – Dashboard snapshot
- `README.md` – Project overview and documentation
- `.pbix` file (not uploaded) – Power BI Dashboard file (Add your `.pbix` if possible)


---

## 📬 Contact

For any queries or suggestions, feel free to reach out:

**Shivansh Jain**  
📧 Email: [Jainjitendra312@gmail.com]  
🔗 [LinkedIn](www.linkedin.com/in/shivansh-jain-7b4b06338)

---

⭐ Don’t forget to star this repo if you found it helpful!
```
