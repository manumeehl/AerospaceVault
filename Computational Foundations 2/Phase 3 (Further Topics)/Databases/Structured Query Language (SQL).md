>SQL (Structured Query Language) is used for managing and manipulating relational databases.

### What do we need SQL for?
• Data Retrieval: Efficiently query large datasets.
• Data Manipulation: Insert, update, and delete records.
• Data Definition: Create and modify database structures.
• Data Control: Manage access to data through permissions.
• Integration: Supported by various DBMS like MySQL, PostgreSQL, etc.

### Important SQL Commands
Implementing the data model
• CREATE TABLE Creates tables and possibly constraints
• ALTER TABLE Modifies table definitions
• DROP TABLE Deletes a table and its data

Creating and updating Tuples
• INSERT INTO … VALUES …
• UPDATE … SET …
• DELETE FROM … WHERE

Querying
• SELECT ... FROM ... WHERE
• →In SQL, whenever you can put a table, you can put a SELECT as well
→ Nested expressions are possible
• GROUP BY
• And Aggregation Functions, e.g. AVG

Combining Tables
• UNION
• CROSS
• Joins:
• LEFT JOIN Take all left and fill data from right
• RIGHT JOIN Take all right and fill data from left
• INNER JOIN Take only intersection

Creating Views
• VIEW