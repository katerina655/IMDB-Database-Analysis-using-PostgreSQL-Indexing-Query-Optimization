# IMDB-Database-Analysis-using-PostgreSQL-Indexing-Query-Optimization
A PostgreSQL project analyzing the IMDB dataset through a series of SQL queries, executed both with and without database indexes. The goal is to compare performance, measure execution times, and understand how indexing affects query optimization.

# PostgreSQL IMDB Database Assignments

This repository contains two university assignments for the "Database Management Systems" course.  
Both assignments work on the IMDB dataset (PostgreSQL) and explore indexing, query optimization,  
parallel execution, memory tuning, and table partitioning.

---

## 📁 Assignment 1 – Indexing & Query Optimization

**Goal:**  
Study the performance impact of different types of indexes on typical IMDB queries.

**Topics covered:**
- Creating tables and loading data
- Writing SQL queries for common user scenarios
- Measuring execution times before/after indexing
- Using GIN, hash, and B-tree indexes
- Understanding which queries actually benefit from indexes

All SQL scripts are inside the folder:  
`/Assignment1`

---

## 📁 Assignment 2 – Memory, Parallelism & Partitioning

**Goal:**  
Evaluate how PostgreSQL performance changes when modifying system parameters and applying range partitioning.

Topics covered:
- Increasing shared_buffers
- Adjusting parallel workers and costs
- Measuring performance differences
- Applying range partitioning on `title_basics`
- Using partition pruning to improve filtered queries

All SQL scripts are inside the folder:  
`/Assignment2`

---

##  Requirements

- PostgreSQL 14+  
- pgAdmin or psql  
- IMDB dataset in CSV format  
- Enough RAM for testing buffer/parallel settings

---

##  Notes

These assignments were completed as part of the 2024–2025 university course.  
All examples, measurements, and explanations are based on the environment in which  
the work was carried out.
