# SQL Query Optimizer

## Explanation
Analyzes slow database queries and provides optimized equivalents.

## Detailed Prompt
Copy and paste the prompt below:

```text
I have an SQL query running on a [MySQL/PostgreSQL/SQL Server] database that is executing too slowly. The tables involved have the following schemas and indexes: [Paste Schemas]. Here is the query: [Paste Query]. Please rewrite this query for maximum performance, explain the N+1 or Cartesian product issues if any, and suggest new indexes that could speed it up.
```
