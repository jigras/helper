# MySQL

## Operations

### Find Duplicates
Find duplicates in SQL
```sql
SELECT name, COUNT(*) FROM table_name GROUP BY name HAVING COUNT(*) > 1
```

### Whitespace trim column
Trim first end line space from column string
- Trim whitespace left:
LTRIM()

- Trim whitespace right 
RTRIM()

Code:

```sql
UPDATE `table` SET `column_name`= RTRIM(LTRIM(`column_name`))
```


### Replace

```sql
UPDATE `table_name` SET `column_name` = REPLACE('column_name' , 'string_to_del', '') WHERE ~expression
```

## Date functions

### Current date
Current date SQL

```sql
SELECT CURRENT_DATE
```

### NOW
Function that return actual date and time
```sql
SELECT NOW()
```


### Extract
Extracting day from date
```sql
SELECT EXTRACT (DAY from date'2019-1-15')
```


Functions	
	
