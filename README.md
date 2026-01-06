# Database Implementation Projects
This repository contains two distinct database projects, each focusing on a different architecture and methodology.

---

## Project 1: Railway Management System (SQL)
A relational database project developed and managed using **Microsoft SQL Server Management Studio (SSMS)**. This project focuses on the logistics and scheduling of a railway network.

### Key Features
* **Schema Design:** Implementation of a relational model to manage trains, stations, routes, and schedules.
* **T-SQL Implementation:** Comprehensive DDL scripts for table structures and DML for populating railway data.
* **Complex Querying:** Execution of advanced queries involving multi-table Joins (e.g., matching trains to specific routes and stations) and Aggregations.
* **Data Integrity:** Strict enforcement of Referential Integrity and constraints to ensure scheduling consistency.

### Tech Stack
* **RDBMS:** Microsoft SQL Server (SSMS)
* **Language:** T-SQL

---

## Project 2: Store Inventory & Sales (NoSQL)
A flexible data-modeling project implemented using **MongoDB**, focusing on a retail/store environment.

### Key Features
* **Non-Relational Modeling:** Designing collections for products, orders, and customers using a document-oriented approach.
* **CRUD Operations:** Practical implementation of Create, Read, Update, and Delete actions for store inventory.
* **Aggregation Framework:** Data processing and filtering using MongoDB's aggregation pipelines for sales analysis.
* **JSON/BSON Structure:** Leveraging dynamic schemas to handle varying product attributes and categories.

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
