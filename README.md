# 💸 Smart Expense Tracker Application

### Python-Based Expense Management and Data Analysis

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python&logoColor=white)
![Jupyter Notebook](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?logo=pandas)
![NumPy](https://img.shields.io/badge/NumPy-Calculations-013243?logo=numpy)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-blue)
![Status](https://img.shields.io/badge/Project-Completed-success)

## 📌 Project Overview

The **Smart Expense Tracker Application** is a Python-based project developed using Jupyter Notebook. It helps users manage daily expenses, maintain expense records, calculate spending summaries, and understand their spending habits through data analysis and visualization.

The application stores expense information in a CSV file and uses Python libraries to process the data, generate reports, and display charts. Users can also enter new expenses, filter existing records, and analyze monthly and category-wise spending.

## 🎯 Objectives

- To maintain daily expense records in a structured format.
- To calculate total and average expenses.
- To categorize expenses for better understanding.
- To filter expenses by category, date, and amount.
- To analyze monthly spending patterns.
- To represent expense data using charts and graphs.
- To practice Python programming, object-oriented programming, and data analysis.

## ✨ Key Features

- ➕ **Add New Expenses:** Enter the date, amount, category, and description of an expense.
- ✅ **Input Validation:** Check expense amounts and dates before adding records.
- 📊 **Expense Summary:** Calculate total and average spending.
- 🔍 **Expense Filtering:** Find records using category, date range, or amount range.
- 📅 **Monthly Analysis:** Calculate monthly total and average spending.
- 🧮 **Numerical Calculations:** Find the highest and lowest expenses and category-wise spending percentages.
- 📈 **Data Visualization:** Display bar charts, line graphs, pie charts, and histograms.
- 💾 **CSV File Management:** Save, load, and display expense records.

## 🧰 Technologies and Libraries Used

| Technology | Purpose |
|---|---|
| Python | Main programming language used to develop the application |
| Jupyter Notebook | Provides an interactive environment to write and execute Python code |
| Pandas | Loads, cleans, filters, groups, and summarizes expense data |
| NumPy | Performs numerical calculations on expense amounts |
| Matplotlib | Creates charts and graphs for visual analysis |
| Seaborn | Creates a histogram to analyze the distribution of expense amounts |
| CSV | Stores expense records in a structured file format |

## 📚 Topics Covered and Explanation

### 1. Python Basics

The project uses variables, data types, functions, input statements, and print statements to collect and process expense information. These concepts form the foundation of the application.

### 2. Control Structures and Input Validation

Conditional statements are used to check whether expense details are valid. Exception handling helps manage invalid dates or amounts, while validation prevents zero or negative expenses from being added.

### 3. Object-Oriented Programming (OOP)

The project uses a class named `ExpenseTracker` to organize related operations into reusable methods. This makes the program easier to understand and maintain.

The class contains four main methods:

- **`add_expense()`** — validates and adds a new expense.
- **`get_summary()`** — calculates and displays total and average spending.
- **`filter_expenses()`** — filters expense records based on selected conditions.
- **`generate_report()`** — generates a summary of expense records and category-wise spending.

### 4. Pandas Data Handling

Pandas is used to load the CSV file into a DataFrame. It helps clean missing or invalid values, organize records, filter expenses, and group data by category or month.

It also helps calculate monthly totals, monthly averages, and category-wise expense summaries.

### 5. NumPy Numerical Analysis

NumPy is used to perform calculations on expense amounts. The project calculates:

- Total expenses
- Average expense amount
- Highest expense
- Lowest expense
- Category-wise spending percentages

These calculations help summarize the dataset efficiently.

### 6. Data Visualization

The project uses Matplotlib and Seaborn to present expense information visually.

| Visualization | Explanation |
|---|---|
| **Bar Chart** | Compares total spending across different expense categories |
| **Line Graph** | Shows how spending changes over time |
| **Pie Chart** | Displays the percentage contribution of each category to total spending |
| **Histogram** | Shows the frequency and distribution of expense amounts |

These visualizations make it easier to identify spending patterns and understand the expense data.

### 7. CSV File Handling

The application uses `expenses.csv` to store expense records. Pandas reads the file when the application starts and saves updated records after new expenses are added.

The CSV file makes the data easy to view, reuse, and analyze without requiring a database.

### 8. Monthly and Category-Wise Analysis

The application groups expenses by month and category to identify where money is being spent. It also helps identify the categories and months with the highest spending.

## 📁 Project Structure

```text
Smart-Expense-Tracker/
│
├── Smart_Expense_Tracker_App.ipynb
├── expenses.csv
└── README.md
```

- **Smart_Expense_Tracker_App.ipynb:** Contains the complete project implementation, calculations, analysis, and visualizations.
- **expenses.csv:** Contains the sample expense dataset with 110 initial records.
- **README.md:** Provides the project overview, features, and documentation.

## 📊 Dataset Information

The project uses a CSV dataset containing **110 sample expense records**.

| Column | Description |
|---|---|
| Date | Date on which the expense occurred |
| Amount | Expense amount in rupees |
| Category | Type of expense |
| Description | Short explanation of the expense |

The dataset includes categories such as Food, Transport, Utilities, Entertainment, Shopping, Health, Education, and Other.

## 🚀 How to Run the Project

1. Download or clone the repository from GitHub.
2. Install Python and Jupyter Notebook.
3. Install the required libraries: Pandas, NumPy, Matplotlib, and Seaborn.
4. Keep `Smart_Expense_Tracker_App.ipynb` and `expenses.csv` in the same folder.
5. Open the notebook in Jupyter Notebook.
6. Run the cells in order from top to bottom.
7. Enter expense details when prompted and view the generated summaries and charts.

## 🎓 Learning Outcomes

This project provides practical experience in:

- Writing Python programs using functions and classes.
- Applying conditions and input validation.
- Reading and writing CSV files.
- Cleaning and analyzing data with Pandas.
- Performing numerical calculations with NumPy.
- Creating charts using Matplotlib and Seaborn.
- Filtering, grouping, and summarizing datasets.
- Presenting information through reports and visualizations.

## 🔮 Future Enhancements

Possible improvements include:

- Setting monthly budgets and displaying budget alerts.
- Adding options to edit or delete expenses.
- Developing an interactive expense dashboard.
- Exporting reports to Excel or PDF.
- Adding expense search and date-wise summaries.
## Expense Records in csv File

<img width="329" height="326" alt="expense_csv" src="https://github.com/user-attachments/assets/a47a7f08-9b64-4c85-9d02-18a1806f6098" />

## Other Outputs of Records

<img width="562" height="386" alt="Output" src="https://github.com/user-attachments/assets/e015d3ec-238f-49f2-b1a0-262edfda8bb9" />

## Tracker Summary and Report

<img width="475" height="316" alt="Summary   Report" src="https://github.com/user-attachments/assets/e97b74cc-9ce7-4557-a9d2-13b4ea477d51" />

## Add Expense as per user input

<img width="834" height="355" alt="add_expense" src="https://github.com/user-attachments/assets/71db5606-9390-4f03-bf55-a606ec2f8031" />

## Show Food Expense only

<img width="346" height="566" alt="Food Expense" src="https://github.com/user-attachments/assets/743f2ab1-da79-4347-8b2c-2f5027b83c3e" />

## Group by Category and Amount

<img width="334" height="221" alt="Group by" src="https://github.com/user-attachments/assets/6d0d14cc-480d-420f-a528-557dbd43467d" />

## Bar Chart

<img width="790" height="382" alt="Bar Chart" src="https://github.com/user-attachments/assets/282ac824-76ac-4af1-9a42-64ff4107cc9f" />

## Line Graph

<img width="791" height="379" alt="Line Graph" src="https://github.com/user-attachments/assets/83633420-e0cb-4f3c-b5c7-c3be6efc3ccc" />

## Pie Chart

<img width="674" height="505" alt="Pie Chart" src="https://github.com/user-attachments/assets/c2e276cd-1771-4ec1-add9-db34d6d28e65" />

## Histogram

<img width="650" height="374" alt="Histogram" src="https://github.com/user-attachments/assets/8909b3d8-2fc7-47b7-be7f-f06cf741e23c" />

## 🏁 Conclusion


The Smart Expense Tracker Application demonstrates how Python and its data analysis libraries can be used to manage and analyze expense records. By combining object-oriented programming, CSV file handling, numerical calculations, and data visualization, the project provides a simple way to understand spending patterns and practice important programming concepts.

---

**Project Type:** Python Data Analysis  
**Development Environment:** Jupyter Notebook  
**Purpose:** Educational project for learning Python programming and data analysis.
