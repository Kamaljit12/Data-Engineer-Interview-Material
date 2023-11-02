# Data Warehousing

# OLTP
OLTP, or Online Transaction Processing, is a class of software applications capable of supporting transaction-oriented programs. Here are  some key points about OLTP:
### Transactional Operations: 
- OLTP systems handle a large number of short, atomic transactions. These transactions are typically  CRUD operations - Create, Read, Update, Delete.
### Concurrency: 
- Due to the high number of transactions, OLTP systems use multi-concurrency control techniques to prevent conflicts  and ensure data consistency.
### Data Integrity: 
- The systems are designed to ensure absolute data integrity through ACID (Atomicity, Consistency, Isolation, Durability)  properties.
### Real-Time Processing: 
- OLTP applications are designed for real-time transactional processing and quick response times.
### High Availability: 
- Given the critical nature of many OLTP systems, they are designed for high availability and fault tolerance.
### Operational vs. Analytical: 
- OLTP systems are focused on operational data and current transactional activity, as opposed to OLAP
(Online Analytical Processing) systems, which are optimized for complex, analytical queries and historical and aggregated data 
reporting.
### Performance Metrics: 
- The performance of OLTP systems is usually measured in transactions per second (TPS).
### Database Design: 
- OLTP systems often use a relational database design with an extensive index to deliver rapid responses to SQL 
queries.
# OLTP Systems
### ERP Systems: 
- Many ERP (Enterprise Resource Planning) systems, such as SAP ERP, Oracle ERP, Microsoft Dynamics, etc., are 
considered OLTP systems.
### Banking Systems: 
- Online banking systems and ATM (Automated Teller Machines) software are examples of OLTP systems.
### Airline Reservation Systems: 
- Software for reserving and selling tickets for airlines.
## E-commerce Platforms: 
- Systems like Amazon and eBay, which handle numerous online transactions daily.
### Telecommunication Network Systems: 
- They handle real-time transactions like call data records.
### Retail POS Systems: 
- Point of Sale systems in retail stores.
### Customer Relationship Management Systems: 
- CRM systems like Salesforce and HubSpot, where real-time data updates are 
crucial.
### Online Service Applications: 
- Many apps, such as ride-sharing apps like Uber and Lyft, food delivery apps like DoorDash, and Airbnb, 
use OLTP systems for real-time transactions.
# Popular Databases for OLTP 
### Oracle Database: 
- A popular relational database management system from Oracle Corporation.
### MySQL: 
- An open-source relational database management system owned by Oracle Corporation.
### Microsoft SQL Server: 
- A relational database management system developed by Microsoft.
### PostgreSQL: 
- A powerful, open-source object-relational database system.
### IBM DB2: 
- A family of database server products developed by IBM.
### MariaDB: 
- An open-source relational database management system, forked from MySQL.
### SAP HANA: 
- An in-memory, column-oriented, relational database management system developed by SAP.
### Amazon Aurora: 
- A relational database service from Amazon Web Services (AWS), compatible with MySQL and PostgreSQL.
### Google Cloud Spanner: 
- A scalable, enterprise-grade, globally-distributed, and strongly consistent database service built for the cloud 
specifically to combine the benefits of relational database structure with non-relational horizontal scale.
### CockroachDB: 
- An open-source distributed SQL database designed for global online transaction processing (OLTP).
# OLAP 
### OLAP, or Online Analytical Processing, is a category of software tools that provide analysis of data for business decisions. It is characterized by relatively low volume of transactions but complex queries involving aggregations, which need to be executed relatively quickly.
## Here are the key characteristics of OLAP systems:
### Multi-Dimensional Analysis: 
- OLAP tools allow users to analyze data along multiple dimensions, which is generally more intuitive for 
users. For example, a business person might want to analyze sales by product, by region, and by time period.
### Speedy Query Performance: 
- Despite the size and complexity of the data sets, OLAP tools provide rapid results to queries due to their 
use of multidimensional data cubes and precalculation.
### Aggregation and Computation: 
- OLAP systems are optimized to perform complex calculations and data aggregations, like sums, 
averages, ratios, ranks, etc., on the fly.
### Support for Complex Queries: 
- OLAP tools support complex queries and enable users to perform 'what-if' type analysis.
### Data Discovery: 
- They support data discovery by providing flexible, ad-hoc querying and multi-dimensional analysis.
### Read-Optimized: 
- Unlike OLTP, which is write-optimized, OLAP is optimized for a high volume of read operations with fewer write 
operations.
# OLAP Systems
## There are several databases and systems that are designed to work as OLAP systems, providing multi-dimensional analysis of data. Here are  some of them:
### Microsoft Analysis Services: Also known as SSAS (SQL Server Analysis Services), it provides data mining and multi-dimensional  analysis.
### SAP BW (Business Warehouse): 
- SAP's data warehousing solution that includes OLAP capabilities.
### Amazon Redshift: 
- A fully managed, petabyte-scale data warehouse service in the cloud from Amazon Web Services.
### Google BigQuery: 
- A fully managed, serverless data warehouse that enables super-fast SQL queries and interactive analysis of 
massive datasets.
### Snowflake: 
- A cloud-based data warehousing platform that supports multi-dimensional analysis of large volumes of data.

![image](https://github.com/Kamaljit12/Data-Engineer-Interview-Material/assets/89628021/4d98e1ed-dc4b-4f5b-9a11-34fac14819f2)


