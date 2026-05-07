# Customer_behavior_analysis
Customer Behavior Analysis project
# Customer Behaviour Analysis

## Project Overview

This project focuses on analyzing customer shopping behaviour using **Python, PostgreSQL, SQL, and Power BI**. The goal is to clean, transform, and analyze customer purchase data to discover meaningful insights about customer preferences, purchasing patterns, and business performance.

The project combines:

* **Data Cleaning & Transformation** using Python (Pandas)
* **Database Management & SQL Analysis** using PostgreSQL
* **Interactive Dashboard Creation** using Power BI

---

## Objectives

* Understand customer purchasing behaviour
* Clean and preprocess raw customer shopping data
* Store transformed data in PostgreSQL
* Solve business-related problems using SQL queries
* Build an interactive dashboard for visualization and insights

---

## Technologies Used

* **Python**
* **Pandas**
* **PostgreSQL**
* **SQLAlchemy**
* **Power BI**
* **Jupyter Notebook**

---

## Project Workflow

### 1. Data Cleaning & Preprocessing

The dataset was cleaned and transformed using Python.

Key preprocessing steps:

* Checked dataset structure and statistics
* Handled missing values using median values
* Standardized column names
* Created new columns such as:

  * `age_group`
  * `purchase_frequency_days`
* Removed duplicate or unnecessary columns

### 2. PostgreSQL Integration

After preprocessing, the cleaned dataset was loaded into PostgreSQL using SQLAlchemy.

Tasks performed:

* Created PostgreSQL database connection
* Imported cleaned data into PostgreSQL table
* Executed SQL queries for business problem solving

### 3. SQL Business Analysis

Several SQL queries were written to answer business-related questions such as:

* Customer purchasing trends
* Sales performance analysis
* Frequency of purchases
* Category-wise customer behaviour
* Revenue insights

### 4. Power BI Dashboard

An interactive Power BI dashboard was created to visualize:

* Customer demographics
* Purchase trends
* Category performance
* Revenue distribution
* Customer behaviour patterns

---

## Files Included

| File Name                                    | Description                                         |
| -------------------------------------------- | --------------------------------------------------- |
| `Customer_behaviour-2.ipynb`                 | Python notebook for data cleaning and preprocessing |
| `Business problem solve by postgresql.sql`   | SQL queries for business analysis                   |
| `customer_behaviour_analysis dashboard.pbix` | Power BI dashboard file                             |

---

## Key Insights

* Customer purchasing frequency varies across different age groups.
* Certain product categories generate higher revenue.
* Purchase behaviour patterns help identify customer preferences.
* Data visualization makes business insights easier to understand.

---

## Future Improvements

* Add predictive analytics using Machine Learning
* Create customer segmentation models
* Deploy dashboard online
* Automate ETL pipeline

---

## How to Run the Project

### Step 1: Clone the Repository

```bash
git clone <repository-link>
```

### Step 2: Install Required Libraries

```bash
pip install pandas sqlalchemy psycopg2-binary
```

### Step 3: Run Jupyter Notebook

Open and run:

```bash
Customer_behaviour-2.ipynb
```

### Step 4: Import SQL File

Run the SQL queries in PostgreSQL.

### Step 5: Open Power BI Dashboard

Open the `.pbix` file in Power BI Desktop.

---

## Conclusion

This project demonstrates how data analysis tools like Python, PostgreSQL, and Power BI can be combined to transform raw customer data into meaningful business insights. It highlights the complete workflow from data preprocessing to database analysis and dashboard visualization.

---

## Author

**Sameer**

