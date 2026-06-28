# 05. LIKE

> **Source:** [Codédex](https://www.codedex.io/) | SQL Chapter

## 🎯 Core Concept
The `LIKE` operator is used in the `WHERE` clause to search for a **pattern** in a column. 

## 📝 Key Syntax
sql
SELECT * 
FROM shows 
WHERE name LIKE 'T%';  -- Shows that start with 'T'

## Detailed Explanation


**The % Wildcard**
% matches any number of characters (zero or more)

'A%' - starts with 'A'

'%z' - ends with 'z'

'%the%' - contains "the" anywhere
