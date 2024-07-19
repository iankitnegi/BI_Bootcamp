# Welcome to Power BI Bootcamp

### Getting Started
1. **Tool Introduction:**
   - Power Bi has option to work in multiple layouts.
   - It provides an option to connect with multiple data sources.
   - Report View is the area to create visuals.
   - Table View helps one to check and modify the tables.
   - Model view helps one to create the data model.
2. **Column Transformation:**
   - Filtering, sorting, replacing values & changing data types are the most commonly used operations.
   - You can add a new column to a table based on existing col(s)
3. **Table Transformation:**
   - Merging & appending allows you to combine two or more tables.
   - Merging combines tables vertically based on one or more common columns.
   - Appending combines tables horizontally based on the column name and type.
4. **Power Query Hack:**
   - Name the query steps appropriately to make it more readable & collaborative.
   - Disable load for the supporting tables which are not used in the report.
5. **DAX:**
   - DAX is the language that you need to talk to Power BI to create formulas or language to create formulas in PowerBI/Excel
   - You can get about 80% use cases done with 20% DAX measures.
   - DAX is utilized in both Power BI & Excel
   - DAX is capable of creating both Measures & Calculated Columns.
6. **Data Modelling:**
   - Inshort, Connecting Table
   - Data Modelling is all about creating connections between tables.
   - Primary(Dimemsion) tables and Fact tables are two kinds of tables.
7. **Creating Visuals:**
   - KPI card, Bar/Pie Charts, Tables/Matrix and Slicers are commonly used visuals.
   - One neew to click the visuals to activate the visual settings.
   - Use horizontal bar chart to represnt more than 3 categories.
8. **Summary/CRUX:**
   - "Power BI is an end-to-end enterprise business intelligence tool. It supports various layouts and connects with many data sources, offering flexibility in data presentation and analysis."
   - "Power Query functions as an ETL (Extract, Transform, Load) engine, enabling filtering, sorting, and the addition of new columns, which are essential for data manipulation."
   - Data Modeling in Power BI focuses on creating connections between tables, primarily involving two kinds of tables: Dimension (Primary) tables and Fact tables
   - "DAX (Data Analysis Expressions) is the language used to create formulas in Power BI, while M-language is used for scripting in Power Query."
   - "Effective visuals, such as KPI cards and bar charts, combined with robust data modeling, are central to Power BI’s capabilities in data analysis and reporting.
________________________________

### Project Plannning & Scoping
1. **Problem Statement:**   
This is a project-based learning course. We will use an imaginary company called AtliQ Hardware and discuss its business model. It is a consumer goods electronics company having operations in various countries. Their business is growing rapidly and they still rely on excel files for data analytics. Excel files are hard to consume and not effective in generating insights. Also due to the lack of effective analytics the company faced a major loss in Latin America.      
_Senior executives of this company have decided to invest in a data analytics project and have assigned a team for this work._
3. **The Email that Started this Project:**   
The data analytics project starts with an email from a product owner roughly outlining the requirements of 5 different dashboards in Power BI.
4. **Project Kick-off Meeting:**   
A project kick-off meeting is held between the product owner, senior data analyst, and a junior data analyst to discuss the project. The senior data analyst Tony Sharma asks some important questions during the meeting.
5. **Learn how a ‘Project Charter’ is Used in Companies:**   
A project charter is a short document describing the entire project. We will use a tool called Mural for this and cover few important dimensions of the project such as,   
   - Project goals
   - Key stakeholders
   - Hopes and fears
   - Risks
   - Timeline
6. **Project Kick-off: Session Debrief:**      
In this session debrief we will talk about 3 skills that we need to learn out of the project kick-off meeting,
   - Being proactive
   - Expectation management
   - Project management skills
7. **Senior Data Analyst Sets Up the Next Steps with Junior Data Analyst:**   
Senior data analyst, Tony Sharma, will now set up the next steps with Junior data analyst, Peter Pandey. In this video, they will cover the following topics,
   - Create a Microsoft teams channel
   - Why Microsoft teams for project communication?
   - Sent action points in the teams channel
   - What is Fiscal Year (a.k.a FY)?
   - Why Power BI?
8. **Simplified: Profit and Loss Statement**   
   - Revenue
   - Net invoice sales
   - Pre-invoice deductions
   - Post invoice discounts
   - Net sales
   - COGS: Cost of goods sold
   - Gross margin
9. **Summary/CRUX:**   
   - Spending time to understand the problem, the end goal, and the bigger picture of the project is the very important first step of any project.
   - It is critical to constantly align your understanding of project scope, requirements, and timelines with the product owner / key stakeholder throughout the project.
   - The profit and loss statement is the most important piece of analysis any company will need.
________________________________

### Data Collection, Exploration & Validation
1. **Simplified: Data Warehouse, OLTP vs OLAP, Data Catalog:**   
   - What is a data warehouse
   - OLTP (Online Transaction Processing) vs OLAP (Online Analytical Processing): The primary purpose of online analytical processing (OLAP) is to analyze aggregated data, while the primary purpose of online transaction processing (OLTP) is to process database transactions. You use OLAP systems to generate reports, perform complex data analysis, and identify trends. In contrast, you use OLTP systems to process orders, update inventory, and manage customer accounts.   
   - What is data catalog
2. **[Creating a Date Table](https://community.fabric.microsoft.com/t5/Desktop/Creating-Date-Tables/m-p/553980)**
3. **Validate Data against Benchmark Numbers:**
   - Show how data analytics team is using Microsoft teams task planner for task assignment
   - Data validation in Power BI against the benchmark numbers provided by the product owner
   - Address gaps found during data validation: In the video, for Total forecast Qty you will see a gap of 376 K which I ask a data engineer to fix it and eventually it matches the correct number which is 86.82436M for the year 2022. When you practice this, you will not see any gap because the dataset that is provided to you has this issue fixed already. So do not worry if your numbers are matching without any gap. The idea here is to show data quality issues that come up in organizations and how they take care of fixing them.   
4. **Summary/CRUX:**
   - Day-to-day software that organizations use for their business processes is called OLTP (Online Transaction Processing) systems.
   - For data analytics needs, we need sort of like a copy of OLTP databases. Some transformations are performed on OLTP databases such that a new set of data can be generated that is well suitable for analytical needs. This new data is stored in a different database also known as Data Warehouse. The new system that contains the data warehouses is also known as OLAP (Online Analytical Processing) systems.
   - Data catalog will enable a data analyst to browse through the list of databases available in the company.
   - Start schema contains fact and dimension tables. Facts are transaction tables whereas dimensions are entity tables. When we connect them to build a data model, it creates something called a STAR schema.
   - For quick data exploration, basic SQL queries are very useful.
________________________________

### Data Transformation in Power Query   
1. 






















