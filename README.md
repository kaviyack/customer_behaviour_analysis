# Customer Shopping Behavior Analysis

An end-to-end data analytics project that transforms retail customer shopping data into meaningful business insights using Python, SQL, and Power BI.

## 📌 Overview

This project analyzes customer shopping behavior to understand purchasing patterns, customer preferences, spending trends, and factors that influence purchase decisions.

The project follows a complete data analytics workflow, from loading and exploring raw data to cleaning, SQL-based analysis, interactive dashboard development, and business reporting.

**Project Objectives**
- Explore and understand customer shopping data.
- Clean and prepare data for reliable analysis.
- Perform exploratory data analysis (EDA) using Python.
- Answer business questions using SQL.
- Build an interactive Power BI dashboard.
- Communicate findings through a report and presentation.

## 📊 Dataset

**Dataset:** Customer Shopping Behavior

The dataset contains customer-level shopping information, including:

- Customer demographics, such as age and gender
- Products purchased and product categories
- Purchase amounts and customer locations
- Product size, color, and season
- Review ratings and shopping preferences
- Other purchasing and customer behavior attributes

**Dataset size:** 3,900 records and 18 columns.

**Dataset file:** `customer_shopping_behavior.csv`

## 🛠️ Tools & Technologies

| Tool | Purpose |
|---|---|
| Python | Data analysis and preparation |
| Pandas | Data manipulation and cleaning |
| Jupyter Notebook | Interactive analysis |
| PostgreSQL | Database storage and SQL analysis |
| SQL | Business queries and aggregations |
| SQLAlchemy | Python-to-database connectivity |
| Power BI | Interactive dashboards and visualization |
| Gamma AI | Presentation creation |
| Git & GitHub | Version control and project hosting |

## 🔄 Project Workflow

### 1. Data Loading and Exploration — Python

- Load the CSV dataset using Pandas.
- Inspect dataset dimensions, columns, and data types.
- Generate summary statistics.
- Examine missing values, duplicates, and potential data quality issues.

### 2. Data Cleaning and Preparation — Python

- Handle missing or inconsistent values where necessary.
- Check for duplicate records.
- Validate data types and column values.
- Transform features where required.
- Prepare the dataset for further analysis.

### 3. Database Integration — PostgreSQL

Load the prepared dataset into PostgreSQL using Python and SQLAlchemy.

The database provides a structured environment for querying customer transactions and analyzing purchasing behavior.

### 4. SQL Business Analysis

Use SQL queries to investigate business questions, including:

- What is the total purchase revenue by gender?
- Which customers used discounts but still spent more than the average purchase amount?
- Which products have the highest average review ratings?
- How do average purchase amounts compare across shipping types?
- What patterns can be identified across customer segments and product categories?

The SQL analysis uses aggregation, filtering, grouping, and other querying techniques to extract useful business insights.

### 5. Power BI Dashboard

Develop an interactive dashboard to explore customer shopping trends and communicate analytical findings.

The dashboard supports analysis of:

- Customer demographics
- Purchase amounts and spending patterns
- Product categories and preferences
- Customer review ratings
- Seasonal shopping behavior

### 6. Reporting and Presentation

- Prepare a report documenting the methodology, analysis, key findings, and business recommendations.
- Use Gamma AI to create a presentation that communicates the project's objectives, analytical process, and insights.

## 📈 Dashboard

The Power BI dashboard provides a visual overview of customer shopping behavior, helping explore purchasing patterns, customer preferences, and spending trends.

### Dashboard Preview

![Customer Shopping Behavior Dashboard](<customer analysis dashboard.png>)

**Power BI file:** `customer_behavior_dashboard.pbix`

To explore the interactive dashboard, download the Power BI file from this repository and open it using Microsoft Power BI Desktop.

## 💡 Results and Business Value

This project demonstrates how raw retail data can be transformed into structured analysis and business intelligence.

The analysis supports:

- Understanding customer purchasing patterns.
- Comparing spending behavior across customer segments.
- Identifying product and category-level trends.
- Evaluating customer ratings and shopping preferences.
- Presenting findings through SQL queries, visualizations, and reports.

The final business findings and recommendations are based on the results obtained from the SQL analysis and Power BI dashboard.

## 📁 Project Structure

```text
customer_behaviour_analysis/
│
├── customer_shopping_behavior.csv
├── Customer_Shopping_Behavior_Analysis.ipynb
├── customer_behavior_sql_queries.sql
├── customer_behavior_dashboard.pbix
├── Customer-Shopping-Behavior-Analysis.pptx
├── dashboard - customer analysis.png
├── README.md
└── LICENSE
```

## 🚀 How to Run the Project

### Prerequisites

Install or configure the following tools:

- Python 3
- Jupyter Notebook
- PostgreSQL
- Power BI Desktop
- Git

### Step 1: Clone the Repository

```bash
git clone https://github.com/kaviyack/customer_behaviour_analysis.git
cd customer_behaviour_analysis
```

### Step 2: Install Python Dependencies

```bash
python -m pip install pandas sqlalchemy jupyter
```

Install the PostgreSQL driver:

```bash
python -m pip install "psycopg[binary]"
```

### Step 3: Launch Jupyter Notebook

```bash
python -m notebook
```

Open `Customer_Shopping_Behavior_Analysis.ipynb` and execute the notebook cells in order.

### Step 4: Set Up PostgreSQL

1. Start your PostgreSQL server.
2. Create a database for the project.
3. Configure the database connection in the notebook.
4. Load the prepared dataset into PostgreSQL.
5. Open `customer_behavior_sql_queries.sql`.
6. Execute the queries using pgAdmin or another PostgreSQL client.

**Note:** Update the database connection settings to match your local PostgreSQL installation. Never commit database passwords or other credentials to GitHub.

### Step 5: Open the Power BI Dashboard

1. Download `customer_behavior_dashboard.pbix` from the repository.
2. Open it in Power BI Desktop.
3. Configure the data source and credentials if prompted.
4. Explore the available dashboard visualizations.

### Step 6: Review the Presentation

Open `Customer-Shopping-Behavior-Analysis.pptx` to review the project presentation.

Gamma AI can also be used to create or refine the presentation and communicate the key findings.

## 📌 Key Skills Demonstrated

- Python programming and Pandas
- Exploratory data analysis (EDA)
- Data cleaning and preparation
- SQL querying and business analysis
- PostgreSQL database integration
- Data visualization using Power BI
- Business reporting and presentation
- Analytical thinking and problem-solving

## 🔮 Future Improvements

- Automate the data ingestion and cleaning workflow.
- Add more business-focused KPIs and dashboard filters.
- Expand customer segmentation and purchasing trend analysis.
- Document database setup and query execution in greater detail.
- Add quantified findings and actionable recommendations.
- Include additional dashboard views for deeper analysis.

## 👩‍💻 Author

**Kaviyavarshini C K**

GitHub: [@kaviyack](https://github.com/kaviyack)

## 📄 License

This project is licensed under the MIT License. See the `LICENSE` file for details.
