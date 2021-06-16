#### 1. What is SQL?
SQL stands for Structured Query Language. It is the standard language for relational database management systems

#### 2. What are Constraints in SQL?
Constraints are used to specify the rules concerning data in the table. It can be applied for single or multiple fields in an SQL table during creation of table or after creationg using the ALTER TABLE command. The constraints are:

* **NOT NULL** - Restricts NULL value from being inserted into a column.
* **CHECK** - Verifies that all values in a field satisfy a condition.
* **DEFAULT** - Automatically assigns a default value if no value has been specified for the field.
* **UNIQUE** - Ensures unique values to be inserted into the field.
A UNIQUE constraint ensures that all values in a column are different. This provides uniqueness for the column(s) and helps identify each row uniquely. Unlike primary key, there can be **multiple unique constraints** defined per table. The code syntax for UNIQUE is quite similar to that of PRIMARY KEY and can be used interchangeably.

* **INDEX** - Indexes a field providing faster retrieval of records.
* **PRIMARY KEY**  - Uniquely identifies each record in a table.
The PRIMARY KEY constraint uniquely identifies each row in a table. It must contain UNIQUE values and has an implicit NOT NULL constraint

* **FOREIGN KEY**  - Ensures referential integrity for a record in another table.

#### 3. What is a Join? List its different types.
* **(INNER) JOIN**: Retrieves records that have matching values in **both tables involved in the join**. This is the widely used join for queries.
* **LEFT (OUTER) JOIN** Retrieves all the records/rows from the **left and the matched records/rows from the right table**.
* **RIGHT (OUTER) JOIN**: Retrieves all the records/rows from the **right and the matched records/rows from the left table**.









