# SQL Logical Operators and Filtering Practice

In this lab I practiced filtering database records using SQL logical operators such as AND, OR, NOT, and LIKE.

## Queries Used

### Display failed login attempts after 6 PM
```sql
SELECT *
FROM log_in_attempts
WHERE login_time > '18:00' AND success = FALSE;
```
<img width="735" height="175" alt="54gh45ge" src="https://github.com/user-attachments/assets/2ece8b68-b762-4667-b7d3-79646b00561a" />


### Display login attempts from specific dates
```sql
SELECT *
FROM log_in_attempts
WHERE login_date = '2022-05-09' OR login_date = '2022-05-08';
```
<img width="733" height="228" alt="g5egrfeb" src="https://github.com/user-attachments/assets/5a1a1efa-e605-4470-8ebf-941e8c29cf78" />


### Display records excluding countries starting with "MEX"
```sql
SELECT *
FROM log_in_attempts
WHERE NOT country LIKE 'MEX%';
```
<img width="739" height="214" alt="8kjhg43" src="https://github.com/user-attachments/assets/61607189-9934-4bbd-b870-c38874eee83d" />

### Display Marketing employees from East offices
```sql
SELECT *
FROM employees
WHERE department = 'Marketing' AND office LIKE 'East%';
```
<img width="689" height="173" alt="8j7h56g43" src="https://github.com/user-attachments/assets/9558cdce-c1ce-45d6-9ff6-d6b97cfd373e" />

### Display employees excluding Information Technology
```sql
SELECT *
FROM employees
WHERE NOT department = 'Information Technology';
```
<img width="729" height="164" alt="jvv34b45" src="https://github.com/user-attachments/assets/52a1347d-4d61-4a65-8a2c-bbf69f4f6fa3" />


### Display employees from Finance or Sales departments
```sql
SELECT *
FROM employees
WHERE department = 'Finance' OR department = 'Sales';
```
<img width="712" height="144" alt="5y6g5g4" src="https://github.com/user-attachments/assets/21226664-67e0-4332-a264-f3319edb5b99" />

## Skills Practiced

- SQL query writing
- Data filtering with WHERE
- Using AND, OR, and NOT operators
- Using wildcard searches with LIKE
- Retrieving specific database records
- Basic database analysis


