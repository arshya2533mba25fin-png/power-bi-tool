# 📊 Loan Application & Credit Risk Analysis Dashboard

An interactive Power BI dashboard designed to evaluate loan applications, assess applicant financial profiles, track decision-making metrics, and analyze credit risk distribution. 

---

## 🖥️ Dashboard Overview

![Dashboard Screenshot](./path/to/your/image/Screenshot_(31).png)

> **💡 Note for Users:** Replace `./path/to/your/image/Screenshot_(31).png` with the actual relative path where you save this screenshot inside your GitHub repository (e.g., `assets/dashboard_screenshot.png`).

---

## 📈 Key Metrics & KPIs

The dashboard tracks **22 total applications** and provides high-level insights across five critical financial metrics:
* **Total Volume:** 1 Million (`Sum of Annual_Income_USD`)
* **Total Funding Requested:** 489K (`Sum of Loan_Amount_Requested`)
* **Average Credit Score:** 614.55
* **Average Debt-to-Income (DTI) Ratio:** 0.45

---

## 🧩 Visualizations & Insights

The report breaks down the application lifecycle and risk assessment through the following components:

### 1. Application Breakdown (`System_Initial_Action`)
* **Donut Chart:** Displays the distribution of initial system behaviors.
    * *Auto_Reject:* 40.91% (9 Applications)
    * *Manual_Review...:* 27.27% (6 Applications)
    * *Auto_Approve:* 27.27% (6 Applications)
    * *Manual_Review:* 4.55% (1 Application)

### 2. Scatter Plot (`Loan Amount Requested` vs `Annual Income`)
* Maps individual applicants to identify trends, outliers, and density gaps between how much an applicant earns versus what they are requesting.

### 3. Credit Score by Application ID
* **Horizontal Bar Chart:** Ranks applicants by their credit scores (ranging down from the 500+ mark) to quickly pinpoint the most creditworthy profiles.

### 4. Applicant Financial Summary Table
* A granular list view containing individual records (e.g., Arthur Curry, Arthur Dent, Barry Allen) tracking their specific `Annual_Income_USD` culminating in a grand total of **1,141,000 USD**.

### 5. Line Chart (`Loan Amount Requested` & `Credit Score` vs `Annual Income`)
* A dual-axis trend analysis evaluating how credit scores and requested amounts fluctuate across varying income brackets.

### 6. Interactive Slicers & Filters
* **Status Filter:** Filter data seamlessly by application status (e.g., *Rejected*).
* **Risk Level Filter:** Filter metrics based on applicant risk profile (e.g., *High Risk*).
* **Remarks Checkboxes:** Drill down into specific underwriter or system flags like *Low Credit Score*, *Low Income*, *Additional verification required*, or *Meets all eligibility criteria*.

---

## 🛠️ Tech Stack & Tools Used

* **BI Tool:** Power BI Desktop
* **Data Modeling:** DAX (Data Analysis Expressions) for calculated measures (e.g., `total applications`)
* **Data Source:** Structured tabular dataset containing applicant demographics, income, credit details, and automated decision tracking.

---

## 🚀 How to View the Interactive File

1. Clone this repository to your local machine:
   ```bash
   git clone [https://github.com/YOUR_USERNAME/YOUR_REPOSITORY_NAME.git](https://github.com/YOUR_USERNAME/YOUR_REPOSITORY_NAME.git)
