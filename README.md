# Inventory and Sales Management System - Business Intelligence Solution

## Welcome to our Inventory and Sales Management System Business Intelligence (BI) solution!

This project utilizes the power of **Microsoft SQL Server Management Studio (SSMS)**, **SQL Server Integration Services (SSIS)**, **SQL Server Analysis Services (SSAS)**, and **Power BI** to provide insightful analytics and reporting capabilities for your inventory and sales data.

### Features

- **Data Management with SQL Server Management Studio (SSMS):** Efficiently manage data using SSMS, ensuring data quality and integrity.
- **Data Integration with SQL Server Integration Services (SSIS):** Seamlessly integrate data from various sources into a centralized data warehouse for streamlined analysis.
- **Advanced Analytics with SQL Server Analysis Services (SSAS):** Utilize SSAS to create multidimensional models, including dimensions, for in-depth analysis.
- **Interactive Reporting with Power BI:** Empower decision-makers with interactive dashboards and reports generated using Power BI.

### How to Use

#### Download and Install Software:

1. **Download and install SQL Server Management Studio (SSMS).**
2. **Download and install SQL Server Integration Services (SSIS).**
3. **Download and install SQL Server Analysis Services (SSAS).**
4. **Download and install Power BI Desktop.**
5. Additionally, ensure you have **Visual Studio** installed for SSIS package development.

#### SQL Server Management Studio (SSMS):

1. Download the databases **avishaydb** and **avishaydbDWH**.
2. Restore the downloaded databases in your SQL Server instance.

#### SQL Server Integration Services (SSIS):

1. Add the provided **.dtsx** files to your SSIS project.
2. Configure the packages as needed to extract, transform, and load data from your source systems into the data warehouse (**avishaydbDWH**).

#### SQL Server Analysis Services (SSAS):

1. Utilize SSAS to create multidimensional models, including dimensions, based on the data stored in the data warehouse (**avishaydbDWH**).
2. Configure parameters and hierarchies to facilitate deeper analysis of inventory and sales metrics.

#### Power BI:

1. Connect Power BI to the SQL Server databases (**avishaydb** and **avishaydbDWH**) to access the data.
2. Import the necessary tables or views from the data warehouse (**avishaydbDWH**) into Power BI.
3. Create interactive dashboards and reports to analyze inventory and sales data effectively, utilizing SSAS cubes for deeper insights.

### Getting Started

To get started with the project:

1. Clone or download the repository.
2. Follow the instructions above to set up and configure the project components.
3. Explore the data and customize the BI solution according to your business needs.
