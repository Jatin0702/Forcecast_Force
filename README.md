# CRM Sales Data Management Project

## Overview
The CRM Sales Data Management Project focuses on cleaning, analyzing, and visualizing customer relationship management (CRM) data. This project integrates Python scripts and a Power BI template to provide an end-to-end solution for data preparation, database management, and insightful reporting.

## Key Components
### 1. Data Cleaning (`crm_data_cleaning.ipynb`)
- **Purpose**: Cleans raw CRM data to ensure quality and consistency.
- **Steps**:
  - Imported raw data files such as `accounts.csv` and `sales_pipeline.csv`.
  - Performed data inspection and transformations to handle missing values, normalize data, and remove duplicates.
  - Prepared cleaned datasets suitable for database integration and analysis.

### 2. Database Integration (`sql_connecting_file.ipynb`)
- **Purpose**: Uploads cleaned datasets into a MySQL database for structured storage.
- **Steps**:
  - Established a connection to the MySQL database using SQLAlchemy.
  - Uploaded cleaned datasets (`Accounts_Cleaned_Data.csv`, `products.csv`, `sales_pipeline_cleaned.csv`, etc.) to corresponding database tables.
  - Ensured successful data migration and verified database integrity.

### 3. Data Visualization (`crm_sales_project.pbit`)
- **Purpose**: Visualizes CRM data to derive insights and track performance metrics.
- **Details**:
  - Includes interactive dashboards for key performance indicators (KPIs) such as sales performance, pipeline analysis, and account management.
  - Provides actionable insights for decision-making and strategic planning.

## Features
- **Comprehensive Data Pipeline**: Covers data cleaning, integration, and visualization.
- **Interactive Dashboards**: Power BI template offers rich visualizations and dynamic insights.
- **Scalable Database Storage**: MySQL database ensures organized and efficient data storage.

## Prerequisites
- **Python Libraries**: `pandas`, `sqlalchemy`, `pymysql`
- **Software**: Power BI Desktop, MySQL Server
- **Datasets**: `accounts.csv`, `products.csv`, `sales_pipeline.csv`, `sales_teams.csv`, `data_dictionary.csv`

## How to Run
### Step 1: Data Cleaning
1. Open the `crm_data_cleaning.ipynb` file.
2. Execute the cells to clean the raw datasets.
3. Save the cleaned datasets.

### Step 2: Database Integration
1. Open the `sql_connecting_file.ipynb` file.
2. Update the database credentials in the script.
3. Execute the cells to upload cleaned data to the MySQL database.

### Step 3: Data Visualization
1. Open the `crm_sales_project.pbit` file in Power BI Desktop.
2. Connect the template to your database.
3. Refresh the data to view updated dashboards.

## Project Team
This project was developed by a collaborative team, with responsibilities divided as follows:
- **Database Integration and Deployment**: Ensured smooth data migration to MySQL.
- **Data Cleaning**: Focused on preparing high-quality datasets.
- **Dashboard Design**: Designed and implemented Power BI visuals.

## Future Enhancements
- Automating the data pipeline for real-time updates.
- Adding advanced analytics, such as predictive modeling, to the dashboards.
- Expanding the database to include additional CRM data sources.

## Conclusion
This project demonstrates a robust approach to managing CRM data by combining Python scripting, database management, and interactive visualizations. It enables organizations to leverage their CRM data for informed decision-making and strategic growth.

