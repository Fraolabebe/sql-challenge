# SQL Joins

## Part 1

* Describe the different types of join clauses supported in SQL.
INNER : Allows us to combine multiple table using rows that have matching values in two or more tables.

LEFT : The LEFT JOIN combine tables and returns all rows from the left table, and the matching rows from the right table. if there is no match with the right table the result is NULL.

RIGHT: The RIGHT JOIN combine tables and returns all rows from the right table, and the matching rows from the left table. if there is no match with the left table the result is NULL.

FULL (OUTER) JOIN: Returns all records when there is a match in either left or right table. It results with values that are unique to both tables 



## Part 2

* Consider the following tables:

  * vendor_table
  ![vendor_table.png](Images/vendor_table.png)

  * yarn_table
  ![yarn_table.png](Images/yarn_table.png)

* Which join was used to create the final view below?

  ![table_join.png](Images/table_join.png)

Left join was used to create the table