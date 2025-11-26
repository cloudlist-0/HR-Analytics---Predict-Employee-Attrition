# HR Analytics: Employee Attrition Prediction

## 📌 Project Overview
High employee attrition (turnover) is a costly problem for companies. This project analyzes a dataset of employee records to understand *why* people leave and uses Machine Learning to *predict* which employees are at risk of resigning in the future.

The goal is to provide the HR department with actionable insights and a predictive tool to improve retention strategies.

## 🛠️ Tools & Technologies Used
* **Python:** Data cleaning, analysis, and modeling.
* **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-Learn.
* **Machine Learning:** Logistic Regression (Binary Classification).
* **Power BI:** Interactive dashboard for visualizing attrition KPIs.

## 📂 Files in this Repository
* **` HR_Analysis.ipynb`**: The main Jupyter Notebook containing all Python code (EDA, Preprocessing, Model Building).
* **`hr_data.csv`**: The original raw dataset (Source: IBM HR Analytics).
* **`hr_data_processed.csv`**: The cleaned dataset used for the Power BI dashboard.
* **`HR_Analysis_dashboard.pdf`**: A static PDF export of the interactive Power BI dashboard.
* **`HR Analytics report.pdf`**: A detailed 2-page report including the abstract, steps, and strategic recommendations.

## 📊 Key Insights
* **Income Matters:** Employees with lower monthly incomes are significantly more likely to leave.
* **Age Factor:** Attrition is highest among younger employees (18-25 years old).
* **Overtime:** Frequent overtime is a strong predictor of resignation.
* **Stagnation:** Employees who have not been promoted in 3+ years are at high risk.

## 🚀 How to Run
1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/YourUsername/HR-Analytics-Project.git](https://github.com/YourUsername/HR-Analytics-Project.git)
    ```
2.  **Install dependencies:**
    ```bash
    pip install pandas numpy seaborn matplotlib scikit-learn
    ```
3.  **Run the Notebook:**
    Open `HR_Analysis.ipynb` in Jupyter Notebook or VS Code and run all cells.

## 📈 Model Performance
* **Algorithm:** Logistic Regression
* **Accuracy:** ~87% (See notebook for exact metrics)
* **Metric:** Optimized for Recall to ensure we catch as many "at-risk" employees as possible.

## 👤 Author
**Shawn Thomas**
* Data Analyst Intern
  
