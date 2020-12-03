# Alter vs. Update


### Part 1

* Explain the difference between `alter` and `update` in SQL statements.
ALTER : Alter is used to change the structure of an existing table.
UDATE : allows you to modify data in a table.
### Part 2

* You are given the following table:

  ![Images/alter_update01.png](Images/alter_update01.png)

* Change the name of the column from `department_id` to `dept_id`.

ALTER TABLE table_name 
RENAME COLUMN department_id TO dept_id;

* Add a column named `annual_salary` to the table.
ALTER TABLE table_name
ADD COLUMN annual_salary INT