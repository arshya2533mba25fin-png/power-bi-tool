# Loan Application Analysis Dashboard (Power BI)

An interactive Power BI dashboard designed to evaluate, track, and analyze loan applications. This tool provides comprehensive insights into applicant demographics, risk profiling, income metrics, and credit worthiness to streamline the financial decision-making process.

## 📊 Dashboard Preview

![Loan Application Dashboard Preview](./Screenshot%20(31).png)
*Note: If your image is in a folder named 'images', change the path to `./images/Screenshot%20(31).png`*

---

## 🚀 Key Features & Visualizations

* **Executive KPI Cards:** Quick glance at critical metrics including total applications (`22`), total sum of annual incomes (`1M`), average loan amount requested (`489K`), average credit score (`614.55`), and debt-to-income ratio (`0.45`).
* **System Action Breakdown (Donut Chart):** Visualizes automated vs. manual decisioning percentages (e.g., Auto Reject, Auto Approve, Manual Review).
* **Risk & Status Slicers:** Interactive filters to instantly isolate "Rejected" cases or "High Risk" candidates.
* **Applicant Income vs. Loan Amount (Scatter Chart):** Explores the correlation between how much an applicant earns versus the loan amount they requested.
* **Credit Score Analysis (Horizontal Bar Chart):** Tracks individual application IDs against their respective credit scores to flag outliers.
* **Trend Analysis (Dual-Axis Line Chart):** Displays the relationship between Annual Income, requested Loan Amount, and Credit Scores across the applicant pool.
* **Granular Data Table:** Detailed tabular view tracking individual applicant names alongside their exact annual income metrics.

---

## 🛠️ Data Model & Fields

The dashboard utilizes a structured dataset containing the following core attributes:
* `Application_ID` & `Applicant_Name`
* `Annual_Income_USD` & `Loan_Amount_Requested`
* `Credit_Score` & `Debt_To_Income_Ratio`
* `Risk_Level` (e.g., High Risk)
* `Status` (e.g., Rejected, Approved)
* `System_Initial_Action` (Auto/Manual workflows)
* `Remarks` (e.g., Low Credit Score, Low Income, Meets criteria)

---

## 💻 How to View the Project

1.  **Clone the Repository:**
    ```bash
    git clone [https://github.com/YOUR_USERNAME/YOUR_REPOSITORY_NAME.git](https://github.com/YOUR_USERNAME/YOUR_REPOSITORY_NAME.git)
    ```
2.  **Open in Power BI:**
    * Ensure you have [Power BI Desktop](https://powerbi.microsoft.com/desktop/) installed.
    * Open the `.pbix` file included in this repository.

---

## 📝 Remarks & Observations Criteria
The dashboard highlights applications based on specific flags:
* [ ] Additional verification required
* [ ] Low Credit Score
* [X] Low Income
* [ ] Meets all eligibility criteria
