# SQL Query Practice 

In this lab I practiced retrieving and organizing information from database tables using SQL queries in MariaDB.

## Queries Used

### Select specific columns from the machines table
```sql
SELECT device_id, operating_system, OS_patch_date
FROM machines;
```
<img width="700" height="132" alt="8uyte4f" src="https://github.com/user-attachments/assets/d95bb867-5c10-466d-86f3-d60b55252153" />

### Display all records from the login attempts table ordered by date and time
```sql
SELECT *
FROM log_in_attempts
ORDER BY login_date, login_time;
```
<img width="725" height="199" alt="7gdff8fj" src="https://github.com/user-attachments/assets/0e65ea6e-71e0-4219-a7b6-ed7db34be62d" />


### Select specific login information from the login attempts table
```sql
SELECT username, login_date, login_time
FROM log_in_attempts;
```
<img width="644" height="135" alt="56dfsq2c" src="https://github.com/user-attachments/assets/29b61f1e-af0d-4e0c-b210-a40cddb4ab8d" />

### Select device ID and email client information
```sql
SELECT device_id, email_client
FROM machines;
```
<img width="536" height="105" alt="4frg4wfd" src="https://github.com/user-attachments/assets/ec1ad09a-42b7-47e6-9db7-b9da9abfc1e0" />

## Skills Practiced

- SQL query writing
- Retrieving data from database tables
- Selecting specific columns
- Organizing query results
- Basic database analysis



