# SQL Filtering and Data Retrieval Practice

In this lab I practiced retrieving and filtering information from database tables using SQL.

## Queries Used

### Select device IDs and operating systems
```sql
SELECT device_id, operating_system
FROM machines;
```
<img width="672" height="115" alt="43t43ttw" src="https://github.com/user-attachments/assets/f7295b35-5ac2-418f-b27e-5db8ab7cfb04" />

### Filter machines by operating system
```sql
SELECT device_id, operating_system
FROM machines
WHERE operating_system = 'OS 2';
```
<img width="682" height="139" alt="y453ff2y5" src="https://github.com/user-attachments/assets/1dea43a8-a34c-48be-ac4f-11f4791b0d05" />

### Display employees from the Finance department
```sql
SELECT *
FROM employees
WHERE department = 'Finance';
```
<img width="725" height="175" alt="32th23f4" src="https://github.com/user-attachments/assets/f22e20ee-425d-448f-bdaa-bda9b82b08df" />

### Display employees from the Sales department
```sql
SELECT *
FROM employees
WHERE department = 'Sales';
```
<img width="720" height="169" alt="43t34g3g5" src="https://github.com/user-attachments/assets/dd954131-7199-4a99-85f0-cdb8810726c9" />

### Display employees from a specific office
```sql
SELECT *
FROM employees
WHERE office = 'South-109';
```
<img width="722" height="169" alt="43t23r2" src="https://github.com/user-attachments/assets/7189fa50-9b9d-45e3-a81e-4aa4281efbad" />

### Display employees from offices starting with "South"
```sql
SELECT *
FROM employees
WHERE office LIKE 'South%';
```
<img width="714" height="139" alt="8y2tg2f2" src="https://github.com/user-attachments/assets/856659f8-7b67-4b1d-acf7-ef177c9e5650" />

## Skills Practiced

- SQL query writing
- Data filtering with WHERE
- Retrieving specific database records

- Basic database analysis
