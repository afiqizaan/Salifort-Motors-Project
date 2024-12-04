# Salifort Motors: Employee Retention Analysis
This project involves analyzing employee data to uncover trends and building predictive models to identify employees at risk of leaving. Insights gained will help the HR department take targeted actions to improve retention and employee satisfaction.

## Business Scenario and Problem
The HR department at Salifort Motors aims to improve employee satisfaction and retention levels. Employee turnover has significant cost implications, including time-consuming recruitment and training processes. By leveraging data analytics, the HR department seeks to answer a critical question:  
**What factors are likely to make employees leave the company?**

This project involves analyzing employee data to uncover trends and building predictive models to identify employees at risk of leaving. Insights gained will help the HR department take targeted actions to improve retention and employee satisfaction.

---

## Goals
1. Analyze the dataset collected by the HR department to identify trends and insights.
2. Build predictive models to determine whether an employee is likely to leave the company.
3. Provide actionable recommendations to improve employee retention.

---

## Dataset
The dataset includes 14,999 rows and 10 variables, describing employee satisfaction, performance, tenure, and other work-related factors.  

| **Variable**                | **Description**                                                             |
|-----------------------------|-----------------------------------------------------------------------------|
| satisfaction_level          | Employee-reported job satisfaction level [0–1]                             |
| last_evaluation             | Score of employee's last performance review [0–1]                          |
| number_project              | Number of projects employee contributes to                                  |
| average_monthly_hours       | Average number of hours employee worked per month                          |
| time_spend_company          | How long the employee has been with the company (years)                    |
| Work_accident               | Whether or not the employee experienced an accident while at work           |
| left                        | Whether or not the employee left the company                               |
| promotion_last_5years       | Whether or not the employee was promoted in the last 5 years               |
| Department                  | The employee's department                                                  |
| salary                      | The employee's salary level (low, medium, high)                            |

---

## Key Steps
### **1. Data Exploration and Preprocessing**
   - Performed exploratory data analysis (EDA) to understand the dataset and identify trends.
   - Cleaned and prepared data for modeling by handling missing values, encoding categorical variables, and normalizing features.

### **2. Building Predictive Models**
   - Implemented multiple machine learning algorithms:
     - Logistic Regression
     - Decision Tree
     - Random Forest
     - XGBoost
   - Evaluated model performance using metrics such as:
     - Accuracy
     - Precision
     - Recall
     - F1-score
     - AUC-ROC Curve
   - Selected the best-performing model for making predictions.

### **3. Insights and Recommendations**
   - Analyzed feature importance to determine key drivers of employee churn.
   - Proposed actionable HR strategies to address factors contributing to employee dissatisfaction and turnover.

---

## Tools and Libraries
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn, XGBoost

---

## Deliverables
1. **Predictive Models**: Multiple machine learning models built and evaluated for predicting employee churn.
2. **Data Visualizations**: Graphs and charts to highlight trends and relationships in the dataset.
3. **Business Recommendations**: Insights and strategies to improve employee retention.

---

## How to Use
1. Clone the repository:
   ```bash
   git clone https://github.com/afiqizaan/Salifort-Motors-Project.git
2. Navigate to the project directory and open the Jupyter Notebook:
   ```bash
   cd Salifort_Motors_Employee_Retention
   jupyter notebook Salifort_Motors_Employee_Retention_Analysis.ipynb

3. Follow the steps in the notebook to explore the dataset, build models, and review results.

