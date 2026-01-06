# Database Implementation Projects
This repository contains two distinct database projects, each focusing on a different architecture and methodology.

---

## Project 1: Railway Management System (SQL)
A relational database project developed and managed using **Microsoft SQL Server Management Studio (SSMS)**. The project manages the logistics and scheduling of a railway network.

### Key Features
* **Schema Design:** Relational model implementation for trains, stations, and routes.
* **T-SQL Implementation:** DDL scripts for table structures and DML for data population.
* **Querying:** Utilizing Multi-table Joins and Aggregations to retrieve schedule and route information.
* **Data Integrity:** Enforcement of Referential Integrity through Primary and Foreign Keys.

### Tech Stack
* **RDBMS:** Microsoft SQL Server (SSMS)
* **Language:** T-SQL

---

## Project 2: Store Management (NoSQL)
A data-modeling project implemented using **MongoDB**, focused on managing a store's inventory and customer orders.

### Key Features
* **Document Modeling:** Designing collections for products and customers using a NoSQL approach.
* **Data Operations:** Implementation of data insertion and advanced search/filtering queries.
* **JSON/BSON Structure:** Managing semi-structured data with flexible schemas.
* **Aggregation:** Basic usage of MongoDB's filtering and grouping capabilities.

### Tech Stack
* **Database:** MongoDB
* **Tools:** MongoDB Compass / Shell

---

## Directory Structure
* `/SQL-SSMS`: SQL scripts, schema definitions, and railway-related query files.
* `/NoSQL-MongoDB`: Collection exports, JSON data, and query scripts for the Store system.
## How to Run
1. **SQL:** Execute the `.sql` scripts within **SQL Server Management Studio**.
2. **NoSQL:** Import the JSON/BSON files into a **MongoDB** instance or run the scripts via the MongoDB shell.
