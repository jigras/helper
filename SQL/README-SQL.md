#MYSQL

##Operations
###Whitepsace trim
Trim first end line space from column string
- Trim whitespace left:
LTRIM()

- Trim whitespace right 
RTRIM()

Code:

```
UPDATE `table` SET `column_name`= RTRIM(LTRIM(`column_name`))
```
---