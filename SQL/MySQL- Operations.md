# MySQL

## Operations
### Whitepsace trim column
Trim first end line space from string column 
- Trim whitespace left:
LTRIM()

- Trim whitespace right 
RTRIM()

Code:

```
UPDATE `table` SET `column_name`= RTRIM(LTRIM(`column_name`))
```
---
