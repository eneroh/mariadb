# mariadb

## Notes
- You must end commands in ;
- 

## Commands

```sql
mariadb -u <username> -p
```
Login to mariadb instance

```sql
CREATE DATABASE <database_name>;
```
Use _ instead of spaces
<br>
Creates a database

```sql
SHOW DATABASES;
```
Displays available databases

```sql
SHOW TABLES;
```
Displays tables associated to database

```sql
USE <database/table>
```
Use the specific database or table

```sql
INSERT INTO <table> VALUES('','','');
```
Place values into database

```sql
UPDATE <table> SET content = '' WHERE id='5';
```
Update item in table

