# 01. Introduction

> **Source:** [Codédex](https://www.codedex.io/) | SQL Chapter

## 🎯 Core Concept
SQL (Structured Query Language) is a programming language designed to manage and retrieve data stored in databases. It's essential for both Data Science and Web Development.

## 📝 Key Syntax
```sql
-- Basic query to retrieve all data from a table
SELECT * FROM table_name;
# 02. SELECT

> **Source:** [Codédex](https://www.codedex.io/) | SQL Chapter

## 🎯 Core Concept
The `SELECT` statement is the foundation of SQL queries. It retrieves data from a database table - either all columns or specific ones you choose.

## 📝 Key Syntax

### Select All Columns
```sql
-- Using asterisk to get everything
SELECT * FROM shows;

-- Can be split across lines (semicolon ends the statement)
SELECT *
FROM shows;