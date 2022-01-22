# SQL-Assignment-5
Q-1. Write an SQL query to print details of workers excluding first names, “Vipul” and
“Satish” from Worker table.

Ans   Select * from worker
      Where first_name not in  (’vipul’ or ‘satish’)

Q-2. Write an SQL query to print details of the Workers whose FIRST_NAME ends with
‘h’ and contains six alphabets.

Ans Select* from workers 
    Where FIRST_NAME like ‘______h’

Q-3. Write a query to validate Email of Employee.
Ans   Select * from worker
      Where email_ employee like %@gmail.com%
