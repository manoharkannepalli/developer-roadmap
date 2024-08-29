#UPDATE

The UPDATE statement in SQL is used to modify existing records in a table. You can specify which columns to update and the new values to assign. It’s also common to use a WHERE clause to update only specific records. Here’s the basic syntax of an UPDATE statement:

SQL CODE EXAMPLE

UPDATE employees 
SET first_name = 'Jane', last_name = 'Smith' 
WHERE employee_id = 101;

In this example, the first_name and last_name of the record with employee_id 101 are updated to 'Jane' and 'Smith', respectively.
