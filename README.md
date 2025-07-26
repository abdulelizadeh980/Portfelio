# 🏦 Mega Bank ATM Transaction Data Analytics Project

This project delivers an advanced analytical solution using **Power BI** to analyze **Mega Bank's ATM transactions**. The dashboard offers a detailed overview of customer behaviors, ATM usage patterns, transaction types, and performance metrics—empowering strategic decision-making and operational optimization.

![Dashboard Preview](./Portfelio%20screenshot%20from%20Power%20BI.png)

---

## 🎯 Project Objective

The main goal of this project is to help **Mega Bank** gain deep insights into customer transaction patterns, ATM operations, and service efficiency—leading to data-driven improvements in banking services.

---

## 🗂️ Dataset Structure

The dataset includes the following tables:

- `Transactions` (Fact Table)
- `Customers` (Dimension)
- `Location` (Dimension)
- `Transaction Type` (Dimension)
- `Hour` (Dimension)
- `Holidays` (Dimension)
- **Calendar Table** (with merged Holidays and extended time intelligence columns)
- **Additional Columns Added:**
  - `Customer Age`, `Age Group`
  - `Transaction Duration`

---

## 📊 Key Features & Visuals

| Feature | Description |
|--------|-------------|
| **Power Query** | For data cleaning and transformation |
| **DAX Measures** | For all key KPIs and time intelligence |
| **Drillthrough** | Enables detailed transaction-level analysis |
| **Tooltips** | Provides contextual data on hover |
| **Bookmarks** | Used for switching between customized views |
| **Page Navigation Buttons** | Enables user-friendly multi-page navigation |
| **Time Intelligence** | Year-Month-Week-Day based trend analysis |
| **Box & Whisker Charts** | For identifying transaction outliers and anomalies |
| **Decomposition Tree** | For exploring transaction distribution by multiple categories |
| **Scatter Chart** | Shows correlation between transaction amount & duration |
| **Stacked Column Charts** | For comparing transaction amounts by Age, Gender, and Occupation |

---

## 📈 Business Goals

- Understand customer demographics and behavior patterns
- Analyze the most used ATM services and transaction types
- Optimize ATM performance and maintenance
- Identify areas for service improvement and expansion
- Detect anomalies and outliers in transaction data

---

## 📌 Business Requirements Addressed

- Transaction analysis by **time of day**, **day of week**, and **month**
- Average transaction amount by **customer** and **ATM location**
- Transaction distribution by **age group**, **gender**, and **occupation**
- Transaction type breakdown by **customer type** (Mega vs non-Mega)
- Impact analysis of **holidays and weekends**
- Frequency and amounts of **account and interbank transfers**
- **ATM performance evaluation** (uptime, usage rate, issues)
- Detection of **outliers** and abnormal transaction patterns
- Utilization analysis of ATM locations
- Average **transaction time** by location, transaction type, and time of day

---

## 📊 DAX Measures Used

- `Transaction Count`
- `Transaction Count %`
- `Transaction Frequency per Customer`
- `Transaction Amount`
- `Average Transaction Amount`
- `Customer Count`
- `Average Duration`
- `Total Duration`
- `Total Availability`
- `Utilization Rate` = `Total Duration / Total Availability`

---

## 📅 Last Refresh Date

**June 15, 2025 – 09:39:32 AM**

---

## 🧠 Stakeholders

- **Mega Bank Executives** – Strategic decision-making
- **ATM Operations Manager** – Optimization & efficiency
- **Branch Managers** – Customer experience & branch-level insights
- **IT Department** – Data access and security

---

## ✅ Outcomes

- 📌 A well-designed **interactive dashboard** showcasing critical transaction KPIs
- 🧩 Detailed visuals and breakdowns by time, customer type, location, and more
- 📈 Actionable insights to improve ATM usage, availability, and customer satisfaction
- 📄 A structured report to support strategic planning and service optimization

---

## 📎 Notes

- Calendar and Holidays tables were joined to support time intelligence.
- Custom age groups were added: `0–18`, `18–25`, `25–40`, `40–65`, `65+`.
- Duration (in minutes) was calculated for each transaction.
- The solution includes rich user experience with **tooltips**, **drillthrough**, **bookmarks**, and **navigation controls**.

---

🎉 **This project meets all listed business and technical requirements.**
Feel free to fork, use, or adapt it for similar banking or financial data scenarios.

---

## 📬 Contact

- **LinkedIn**: [https://www.linkedin.com/in/abdulsalamalizada](https://www.linkedin.com/in/abdulsalamalizada)
- **Email**: Abdulelizadeh@gmail.com
