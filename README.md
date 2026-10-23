# Customer Shopping Behavior Analysis

An end-to-end data analytics project that transforms retail customer shopping data into meaningful business insights using Python, SQL, and Power BI.

## 📌 Overview

This project analyzes customer shopping behavior to understand purchasing patterns, customer preferences, spending trends, and factors that influence purchase decisions.

The project follows a complete data analytics workflow, starting with raw dataset loading and exploratory data analysis, followed by data cleaning, SQL-based analysis, interactive dashboard development, and business reporting.

**Project objectives:**
- Explore and understand customer shopping data.
- Clean and prepare data for reliable analysis.
- Perform exploratory data analysis (EDA) using Python.
- Answer business questions using SQL.
- Build an interactive Power BI dashboard.
- Summarize findings and recommendations in a report and presentation.

## 📊 Dataset

**Dataset:** Customer Shopping Behavior

The dataset contains customer-level shopping information, including:

- Customer demographics, such as age and gender
- Products purchased and product categories
- Purchase amounts and customer locations
- Product size, color, and season
- Review ratings and shopping preferences
- Other purchasing and customer behavior attributes

The dataset contains **3,900 records and 18 columns**.

**Dataset file:** `customer_shopping_behavior.csv`

## 🛠️ Tools & Technologies

| Tool | Purpose |
|---|---|
| Python | Data analysis and preparation |
| Pandas | Data loading, cleaning, and manipulation |
| Jupyter Notebook | Interactive analysis and documentation |
| PostgreSQL / MySQL / SQL Server | Database storage and SQL analysis |
| SQL | Business queries and data aggregation |
| Power BI | Interactive dashboard and visualization |
| Gamma AI | Presentation creation |
| Git & GitHub | Version control and project hosting |

## 🔄 Project Workflow

### 1. Data Loading and Exploration — Python

- Load the CSV dataset using Pandas.
- Inspect the dataset structure, dimensions, and data types.
- Examine column names and summary statistics.
- Identify missing values, duplicates, and potential data quality issues.

### 2. Data Cleaning and Preparation — Python

- Handle missing or inconsistent values where necessary.
- Check and remove duplicate records where appropriate.
- Validate data types and prepare columns for analysis.
- Create or transform features when required.
- Prepare the cleaned dataset for database loading.

### 3. Database Integration — SQL

Load the prepared dataset into a database using Python and SQLAlchemy.

Supported database options:
- PostgreSQL
- MySQL
- Microsoft SQL Server

The SQL scripts address business questions related to customer spending, purchasing behavior, product ratings, discounts, and shipping preferences.

### 4. SQL Business Analysis

Use SQL queries to extract actionable insights from the customer shopping dataset.

Example business questions include:

- What is the total purchase revenue by gender?
- Which customers used discounts but still spent more than the average purchase amount?
- Which products have the highest average review ratings?
- How do average purchase amounts compare across shipping types?
- What patterns can be identified across customer segments and product categories?

### 5. Power BI Dashboard

Build an interactive dashboard to explore customer shopping trends and communicate analytical findings.

The dashboard can be used to examine:
- Customer demographics
- Purchase amount and revenue patterns
- Product categories and purchasing preferences
- Customer review ratings
- Seasonal and shopping behavior trends

Dashboard file: `customer_behavior_dashboard.pbix`

### 6. Reporting and Presentation

- Prepare a project report summarizing the methodology, analysis, findings, and business recommendations.
- Create a presentation using Gamma AI to communicate the project's key insights in a clear and visual format.

## 📈 Dashboard

The Power BI dashboard provides a visual overview of customer shopping behavior and supports exploration of purchasing patterns and customer preferences.

**Dashboard file:** `customer_behavior_dashboard.pbix`

To view the dashboard, download the file and open it using Microsoft Power BI Desktop.

## 💡 Results and Business Value

This project demonstrates how raw retail data can be converted into structured analysis and business intelligence.

The workflow supports:
- Understanding customer purchasing patterns.
- Comparing spending behavior across customer segments.
- Identifying product and category-level trends.
- Evaluating review ratings and shopping preferences.
- Communicating findings through SQL queries, visualizations, and reports.

The specific findings and recommendations should be drawn from the completed SQL analysis and Power BI dashboard.

## 📁 Project Structure

```text
customer_behaviour_analysis/
│
├── customer_shopping_behavior.csv
├── Customer_Shopping_Behavior_Analysis.ipynb
├── customer_behavior_sql_queries.sql
├── customer_behavior_dashboard.pbix
├── Customer-Shopping-Behavior-Analysis.pptx
├── README.md
└── LICENSE
```

## 🚀 How to Run the Project

### Prerequisites

Install or set up the following tools:

- Python 3
- Jupyter Notebook
- PostgreSQL, MySQL, or Microsoft SQL Server
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

For PostgreSQL, install the appropriate database driver:

```bash
python -m pip install "psycopg[binary]"
```

For MySQL, install a compatible driver such as:

```bash
python -m pip install pymysql
```

For SQL Server, configure a compatible SQL Server driver and connection string.

### Step 3: Launch Jupyter Notebook

```bash
python -m notebook
```

Open `Customer_Shopping_Behavior_Analysis.ipynb` and execute the notebook cells in order.

### Step 4: Set Up the SQL Database

1. Start your chosen database server.
2. Create a database for the project.
3. Configure the database connection in the notebook.
4. Load the prepared dataset into the database.
5. Open `customer_behavior_sql_queries.sql`.
6. Execute the queries using your database's SQL client.

**Note:** SQL syntax and connection settings may need minor adjustments depending on the database engine you choose.

### Step 5: Open the Power BI Dashboard

Open `customer_behavior_dashboard.pbix` in Power BI Desktop.

If prompted, configure the data source and credentials to match your database setup.

### Step 6: Review the Report and Presentation

Use the project report to review the methodology and findings. Open `Customer-Shopping-Behavior-Analysis.pptx` to review the presentation included in the repository.

Gamma AI can also be used to create or refine the presentation.

## 📌 Key Skills Demonstrated

- Data loading and manipulation with Python
- Exploratory data analysis (EDA)
- Data cleaning and validation
- SQL querying and business analysis
- Relational database integration
- Data visualization and dashboard development
- Business reporting and presentation
- Analytical problem-solving

## 🔮 Future Improvements

- Automate the data ingestion and cleaning workflow.
- Add more business-focused KPIs and dashboard filters.
- Expand customer segmentation and purchasing trend analysis.
- Document reproducible database setup and query execution.
- Add screenshots of the dashboard and examples of key findings.

## 👩‍💻 Author

**Kaviyavarshini C K**

GitHub: [@kaviyack](https://github.com/kaviyack)

## 📄 License

This project is licensed under the MIT License. See the `LICENSE` file for details.

