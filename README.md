# 📊 Data Analytics Project: [Customer Behavior Analyze]

## Overview
This project is a comprehensive data analysis workflow designed to extract actionable insights from a raw dataset. The process encompasses data loading, exploratory data analysis (EDA), data cleaning, SQL querying, dashboard creation, and reporting. The goal is to demonstrate a complete, end-to-end analytical skillset relevant to a data analyst role.

## Dataset
*   **Source:** [Customer_Shopping_Behvaior.csv]
*   **Description:** The dataset contains [3900] records of [Customer Shopping Behvaior].
*   **Key Attributes:**
    *   `orderID`: Unique identifier for each order.
    *   `product`: Name of the product purchased.
    *   `Subscription_status`: Number of units sold.
    *   `price`: Unit price of the product.
    *   `orderDate`: Date of the transaction.
    *   `customerID`: Unique identifier for the customer.
    

## Tools & Technologies
| **Data Analysis & Cleaning**: Python (Pandas)
| **Database Management**: MySQL
| **Data Visualization**: Power BI 
| **Reporting & Presentation**: Microsoft PowerPoint, Gamma App |

## Project Steps
The analysis was conducted in a structured, multi-stage process:

1.  **Data Loading & Initial Inspection:**
    *   The dataset was loaded into a Python Jupyter Notebook using the Pandas library.
    *   Initial checks were performed to understand the data structure, data types, and identify immediate issues like missing values or duplicates.

2.  **Exploratory Data Analysis (EDA):**
    *   Performed univariate and bivariate analysis to understand distributions and relationships between variables.

3.  **Data Cleaning & Preprocessing:**
    *   Handled missing values through imputation or removal.
    *   Corrected inconsistent data formats (e.g., dates, categories).
    *   Removed duplicate entries and irrelevant data points to ensure data quality for analysis.

4.  **SQL Analysis (MySQL):**
    *   The cleaned dataset was exported and imported into a MySQL database.
    *   Wrote and executed complex SQL queries to answer key business questions, such as:
        *   "What are the top 10 best-selling products?"
        *   "What is the monthly sales trend?"

5.  **Dashboard & Visualization (Power BI):**
    *   Connected Power BI directly to the MySQL database for a dynamic data connection.
    *   Built an interactive dashboard with key metrics (KPIs), charts, and filters to allow for drill-down analysis.
    *   The dashboard provides an at-a-glance view of business performance.

6.  **Reporting & Presentation:**
    *   A summary report was created, detailing the methodology, key findings, and recommendations.
    *   A concise and visually appealing presentation was built using **Gamma** to effectively communicate the insights to a non-technical audience.

## Power BI Dashboard
The interactive dashboard provides a high-level overview of the key metrics.

**Key Features:**
*   **Total Sales, Quantity, and Unique Customers** as KPIs.
*   **Sales Trend** over time (Monthly/Quarterly).
*   **Top Products** by sales volume.
*   **Sales by Country** on a map or bar chart.
*   Interactive filters for Date Range, Country, and Product.

![Screenshot of Power BI Dashboard](<img width="895" height="487" alt="CusotmerBehvaiorDashboard" src="https://github.com/user-attachments/assets/69e7dca6-f9c8-40dc-a949-a28b3b9fa235" />
)

## How to Run This Project
Follow these steps to set up and run the project on your local machine.

### Prerequisites
*   Python 3.x installed (with Jupyter Notebook)
*   MySQL Server and MySQL Workbench installed
*   Power BI Desktop (optional, to view the .pbix file)

### Installation & Setup
1.  **Clone the repository:**
    ```bash
    git clone https://github.com/your-username/your-repo-name.git
    cd your-repo-name
    ```

2.  **Set up a Python Virtual Environment (Recommended):**
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    pip install -r requirements.txt
    ```

3.  **Database Setup:**
    *   Open MySQL Workbench and create a new connection/schema.
    *   Run the `sql/schema_creation.sql` file to create the necessary table.
    *   Use the provided `load_data_to_mysql.py` script or MySQL's import wizard to load the `cleaned_data.csv` file into your database.

4.  **Run the Analysis:**
    *   Open the Jupyter Notebook: `notebooks/data_analysis.ipynb` and run the cells sequentially.
    *   The SQL queries used for analysis are located in the `sql/` folder.

5.  **View the Outputs:**
    *   **Dashboard:** Open the `dashboard/sales_dashboard.pbix` file in Power BI Desktop. Refresh the data connection to point to your local MySQL instance.
    *   **Report:** View the `docs/Final_Report.pdf`.
    *   **Presentation:** View the `docs/Project_Presentation.pdf` or the public link to your Gamma presentation.

---
**Contact**
[Your Name]
[Your LinkedIn Profile URL]
[Your Email Address]
