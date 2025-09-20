# Database Management Systems (DBMS) & SQL Roadmap (PostgreSQL Focus)

A structured roadmap to revise **DBMS fundamentals** while practicing SQL in **PostgreSQL** for placement preparation.

---

## 1. Fundamentals of DBMS
- **What is DBMS?**
- **Types of DBMS**
  - Hierarchical
  - Network
  - Relational (RDBMS)
  - NoSQL
- **DBMS vs RDBMS**
- **Schemas & Instances**
- **Keys in DBMS**
  - Primary Key
  - Candidate Key
  - Alternate Key
  - Foreign Key
  - Composite Key
  - Super Key
- **Constraints**
  - NOT NULL
  - UNIQUE
  - DEFAULT
  - CHECK
  - PRIMARY KEY, FOREIGN KEY

---

## 2. ER Model (Entity-Relationship Model)
- **Entities, Attributes, Relationships**
- **Types of Attributes**
  - Simple, Composite, Derived, Multivalued
- **Types of Relationships**
  - One-to-One
  - One-to-Many
  - Many-to-Many
- **Mapping ER to Relational Model**

---

## 3. Relational Model
- **Relation Schema & Relation Instance**
- **Degree & Cardinality**
- **Tuples vs Attributes**
- **Relational Algebra**
  - Selection (σ)
  - Projection (π)
  - Union, Set Difference, Intersection
  - Cartesian Product
  - Join Operations (Theta Join, Natural Join, Outer Join)

---

## 4. Normalization
- **Functional Dependencies (FDs)**
- **Closure of Attributes**
- **Types of Normal Forms**
  - 1NF
  - 2NF
  - 3NF
  - BCNF
  - 4NF, 5NF
- **Denormalization (When & Why?)**

---

## 5. Transaction Management
- **ACID Properties**
- **States of a Transaction**
- **Concurrency Control**
  - Locking (Shared, Exclusive)
  - Two-Phase Locking (2PL)
  - Deadlocks (Prevention, Detection, Recovery)
- **Isolation Levels**
  - Read Uncommitted
  - Read Committed
  - Repeatable Read
  - Serializable
- **Write-Ahead Logging (WAL) in PostgreSQL**

---

## 6. Indexing & Query Optimization
- **What is Indexing?**
- **Types of Indexes**
  - Primary, Secondary
  - Clustered, Non-clustered
  - B-Tree Index (PostgreSQL Default)
  - Hash Index
  - GIN/ GiST Index (Full-text search in PostgreSQL)
- **Cost-based Query Optimization**
- **EXPLAIN & EXPLAIN ANALYZE in PostgreSQL**

---

## 7. SQL (with PostgreSQL Focus)

### **Basics**
- CREATE, DROP, ALTER
- INSERT, UPDATE, DELETE
- SELECT with WHERE, ORDER BY, LIMIT, OFFSET

### **Joins**
- INNER JOIN
- LEFT JOIN
- RIGHT JOIN
- FULL OUTER JOIN
- SELF JOIN
- CROSS JOIN

### **Aggregation & Grouping**
- GROUP BY, HAVING
- Aggregate functions: COUNT, SUM, AVG, MIN, MAX
- Window functions: ROW_NUMBER(), RANK(), DENSE_RANK(), PARTITION BY

### **Advanced SQL in PostgreSQL**
- Subqueries (Scalar, Correlated, EXISTS/NOT EXISTS)
- Common Table Expressions (CTEs) with `WITH`
- Recursive CTEs
- JSON & JSONB operations
- Array data types
- UPSERT with `ON CONFLICT`
- PostgreSQL-specific operators (`->`, `->>`, `#>>`, `@>`, `<@`)

---

## 8. Views & Stored Procedures
- **Views**
  - CREATE VIEW
  - Materialized Views (PostgreSQL Feature)
- **Functions**
  - User-defined functions
  - PL/pgSQL basics
- **Stored Procedures vs Functions**
- **Triggers**
  - BEFORE, AFTER, INSTEAD OF
  - Row-level vs Statement-level

---

## 9. Security in PostgreSQL
- **Users & Roles**
- **GRANT & REVOKE**
- **Row-Level Security (RLS)**
- **Authentication methods**

---

## 10. Distributed Databases & Scaling
- **Sharding**
- **Replication**
  - Master-Slave Replication
  - Streaming Replication in PostgreSQL
- **Partitioning**
  - Range Partitioning
  - List Partitioning
  - Hash Partitioning
- **CAP Theorem in Databases**
- **Consistency Models**

---

## 11. Real-World PostgreSQL Features
- **Full-Text Search**
- **Extensions in PostgreSQL**
  - `pg_trgm` (fuzzy search)
  - `PostGIS` (geospatial data)
- **Parallel Queries**
- **Foreign Data Wrappers (FDW)**

---

## 12. Practice Section
- **LeetCode Database Questions**
- **HackerRank SQL Challenges**
- **PostgreSQL Hands-on**
  - Build a sample DB (e.g., Employee Management / E-commerce)
  - Write complex queries
  - Optimize with indexes
  - Try recursive queries & JSON operations
