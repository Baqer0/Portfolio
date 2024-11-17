# Business Intelligence Data Warehouse Project

**Project Overview:**
This project involves the development of a data warehouse to derive business intelligence from data for an e-commerce company, employing a dimensional model to ensure effective data organization. The proof of concept demonstrates data extraction, transformation, and loading (ETL) from chosen data sources, as well as the creation of reports and visualizations that highlight insights beneficial to stakeholders.


**Key Sections**
1. Subject Area Selection and Business Vision
- Rationale for Subject Area: Explanation of why specific subject areas were selected based on business needs and data availability.
- Stakeholder Identification: Key stakeholders and their roles in the data warehouse development.
- Business Vision: The strategic objectives for developing the data warehouse and expected business benefits.
  
**2. Schema Design**
- Dimensional Model: Presentation of the proposed schema, including star and/or snowflake schema diagrams.
- Design Justification: Discussion on the rationale for the schema layout and how it aligns with business needs.

**3. Data Implementation**
- **ETL Process:** Detailed overview of how data was extracted from the operational source(s), transformed, and loaded into the data warehouse using Microsoft SQL Server.
- **Tools Used:** Mention of SQL Server Integration Services (SSIS) or SQL scripts.

**4. Reporting and Visualization**
- SSRS Reports: Four comprehensive reports generated to support the business requirements.
- Tableau Visuals: Four visualizations created using Tableau to showcase key trends and insights.
- Dashboard Development: A Tableau dashboard integrating the visualizations for easy stakeholder access.

**Technologies Used**
- Microsoft SQL Server: For database creation and management.
- SSIS: For the ETL process.
- SSRS: For creating detailed reports.
- Tableau: For interactive visualizations and dashboard creation.

**Insights and Expected Outcomes:**
Discussion on the potential insights the company could gain, such as performance metrics, trend analysis, and predictive insights from the developed data warehouse.

**Conclusion**
This project highlights the end-to-end development of a data warehouse, from schema design and data integration to reporting and visualization, to enable data-driven decision-making.

**Explore the Project Outcome & the Business Intelligence Insights**

<html>
<head>
  <style>
    .icon-container {
      display: flex;
      justify-content: space-between;
      align-items: center;
      width: 100%;
    }
    .icon-item {
      text-align: center;
      flex: 1;
      margin: 0 10px; /* Adjust margin for spacing between items */
    }
  </style>
</head>
<body>

  <div class="icon-container">
    <div class="icon-item">
      <a href="./DatabaseSchema/index.html">
        <img src="../asset/DataBase_Schema.png" width="100" height="100" alt="Star Schema"/><br/>
        <b>Database Schema</b>
      </a>
    </div>
    <div class="icon-item">
      <a href="./BusinessReports/index.html">
        <img src="../asset/Business_Reports.png" width="100" height="100" alt="SSRS Report"/><br/>
        <b>Business Analytics Reports (SSRS)</b>
      </a>
    </div>
    <div class="icon-item">
      <a href="./BusinessDashboard/index.html">
        <img src="../asset/dashboard.png" width="100" height="100" alt="Dashboard"/><br/>
        <b>Business Analytics Visuals and Dashboard</b>
      </a>
    </div>
  </div>

</body>
</html>

