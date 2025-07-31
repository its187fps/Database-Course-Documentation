# Database-Course-Documentation
 Documentation and reports for the Database Course tasks.
 

| Feature          | Flat File System                                     | Relational Database                                      |
|------------------|------------------------------------------------------|----------------------------------------------------------|
| Structure        | Stores data in plain text files (e.g., CSV, Excel)  | Stores data in structured tables with defined schemas    |
| Data Redundancy  | High — data is often repeated                        | Low — uses relationships to avoid data duplication       |
| Relationships    | No relationships between data records                | Supports relationships (e.g., one-to-many, many-to-many) |
| Example Usage    | Employee list in a spreadsheet                       | Company HR system with multiple connected tables         |
| Drawbacks        | Difficult to update, search, and maintain            | Requires setup, design, and knowledge of SQL             |


<img width="788" height="360" alt="image" src="https://github.com/user-attachments/assets/684a3f44-f115-433c-9b3e-ff7e1bc3f3e0" />


## 3. Roles in a Database System

In a typical database project, several roles work together to design, build, and manage the system. Below are the key roles and their responsibilities:

- 🔹 System Analyst  
  Gathers requirements from stakeholders, analyzes business processes, and defines what the database system should accomplish.

- 🔹 Database Designer  
  Designs the structure of the database including tables, relationships, keys, and constraints to meet the system requirements.

- 🔹 Database Developer  
  Writes the SQL code to create tables, views, stored procedures, triggers, and other database components.

- 🔹 Database Administrator (DBA)  
  Manages and maintains the database environment. This includes tasks like backup and recovery, user access control, performance tuning, and security.

- 🔹 Application Developer  
  Develops the front-end or back-end application that interacts with the database. They ensure the app sends and retrieves data correctly.

- 🔹 Business Intelligence (BI) Developer  
  Creates dashboards, reports, and data visualizations. They transform raw data into meaningful insights for decision-making.

  ## 4. Types of Databases

There are several types of databases, each designed for specific needs and use cases. Below is a summary of the most common types:

### 🔹 Relational vs. Non-Relational Databases

- 🗂️ Relational Databases (RDBMS):  
  - Store data in structured tables with rows and columns.  
  - Use SQL (Structured Query Language) for querying.  
  - Support relationships between tables (e.g., foreign keys).  
  - Examples: MySQL, PostgreSQL, Oracle.

- 📦 Non-Relational Databases (NoSQL):  
  - Store data in flexible formats (documents, key-value pairs, graphs, etc.).  
  - Do not require a fixed schema.  
  - Often used for big data, real-time applications, or unstructured data.  
  - Examples: MongoDB (document), Cassandra (wide-column), Redis (key-value), Neo4j (graph).

---

### 🔹 Centralized vs. Distributed vs. Cloud Databases

- 🖥️ Centralized Database:  
  - All data is stored and accessed from a single central location/server.  
  - Easy to manage but limited scalability.  
  - Example Use Case: Small office systems.

- 🌐 Distributed Database:  
  - Data is spread across multiple locations/servers, often geographically distributed.  
  - Offers higher availability and performance.  
  - Example Use Case: Global e-commerce platforms.

- ☁️ Cloud Database:  
  - Hosted and managed in the cloud by providers like AWS, Azure, or Google Cloud.  
  - Scalable, accessible from anywhere, and managed as a service.  
  - Examples: Amazon RDS, Azure SQL Database, Google Cloud Spanner.  
  - Use Case: Web and mobile apps with variable traffic.

---

### 🔹 Use Case Examples

| Database Type             | Example Systems or Applications                 |
|---------------------------|--------------------------------------------------|
| Relational (e.g., MySQL)  | Banking systems, school management, ERP systems |
| Non-Relational (e.g., MongoDB) | Social media platforms, product catalogs        |
| Distributed               | Online shopping platforms like Amazon           |
| Cloud                     | SaaS apps, mobile backends, analytics systems   |


