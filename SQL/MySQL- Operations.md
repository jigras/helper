# MySQL

## Operations

### Find Duplicates
Find duplicates in SQL
```sql
SELECT
    name, COUNT(*)
FROM
    table_name
GROUP BY
    name
HAVING 
    COUNT(*) > 1
```

### Whitepsace trim
Trim first end line space from column string
- Trim whitespace left:
LTRIM()

- Trim whitespace right 
RTRIM()

Code:

```sql
UPDATE `table` SET `column_name`= RTRIM(LTRIM(`column_name`))
```
---