

|Functions|Description|
|---|---|
|ADDDATE()|MySQL ADDDATE() adds a time value with a date.|
|ADDTIME()|In MySQL the ADDTIME() returns a time or datetime after adding a time value with a time or datetime.|
|CONVERT_TZ()|In MySQL the CONVERT_TZ() returns a resulting value after converting a datetime value from a time zone specified as the second argument to the time zone specified as the third argument.|
|CURDATE()|In MySQL the CURDATE() returns the current date in 'YYYY-MM-DD' format or 'YYYYMMDD' format depending on whether numeric or string is used in the function.|
|CURRENT_DATE()|In MySQL the CURRENT_DATE returns the current date in ‘YYYY-MM-DD’ format or YYYYMMDD format depending on whether numeric or string is used in the function.|
|CURRENT_TIME()|In MySQL the CURRENT_TIME() returns the current time in ‘HH:MM:SS’ format or HHMMSS.uuuuuu format depending on whether numeric or string is used in the function.|
|CURRENT_TIMESTAMP()|In MySQL the CURRENT_TIEMSTAMP returns the current date and time in ‘YYYY-MM-DD HH:MM:SS’ format or YYYYMMDDHHMMSS.uuuuuu format depending on whether numeric or string is used in the function.|
|CURTIME()|In MySQL the CURTIME() returns the value of current time in ‘HH:MM:SS’ format or HHMMSS.uuuuuu format depending on whether numeric or string is used in the function.|
|DATE_ADD()|MySQL DATE_ADD() adds time values (as intervals) to a date value. The ADDDATE() is the synonym of DATE_ADD().|
|DATE_FORMAT()|MySQL DATE_FORMAT() formats a date as specified in the argument. A list of format specifiers given bellow may be used to format a date.|
|DATE_SUB()|MySql date_sub() function subtract a time value (as interval) from a date.|
|DATE()|MySQL DATE() takes the date part out from a datetime expression.|
|DATEDIFF()|MySQL DATEDIFF() returns the number of days between two dates or datetimes.|
|DAY()|MySQL DAY() returns the day of the month for a specified date.|
|DAYNAME()|MySQL DAYNAME() returns the name of the week day of a date specified in the argument.|
|DAY OF MONTH()|MySQL DAYOFMONTH() returns the day of the month for a given date.|
|DAY OF WEEK()|MySQL DAYOFWEEK() returns the week day number (1 for Sunday,2 for Monday …… 7 for Saturday ) for a date specified as an argument.|
|DAY OF YEAR()|MySQL DAYOFYEAR() returns day of the year for a date. The return value is within the range of 1 to 366.|
|EXTRACT()|MySQL EXTRACT() extracts a part of a given date.|
|FROM_DAYS()|MySQL FROM_DAYS() returns a date against a datevalue.|
|FROM_UNIXTIME()|MySQL FROM_UNIXTIME() returns a date /datetime from a version of unix_timestamp.|
|GET_FORMAT()|MySQL GET_FORMAT() converts a date or time or datetime in a formatted manner as specified in the argument.|
|HOUR()|MySQL HOUR() returns the hour of a time.|
|LAST_DAY()|MySQL LAST_DAY() returns the last day of the corresponding month for a date or datetime value.|
|LOCALTIME()|MySQL LOCALTIME returns the value of current date and time in ‘YYYY-MM-DD HH:MM:SS’ format or YYYYMMDDHHMMSS.uuuuuu format depending on the context (numeric or string) of the function.|
|LOCALTIMESTAMP()|MySQL LOCALTIMESTAMP returns the value of current date and time in ‘YYYY-MM-DD HH:MM:SS’ format or YYYMMDDHHMMSS.uuuuuu format depending on the context (numeric or string) of the function.|
|MAKEDATE()|MySQL MAKEDATE() returns a date by taking a value of a year and a number of days. The number of days must be greater than 0 otherwise a NULL will be returned.|
|MAKETIME()|MySQL MAKETIME() makes and returns a time value from a given hour, minute and seconds.|
|MICROSECOND()|MySQL MICROSECOND() returns microseconds from the time or datetime expression.|
|MINUTE()|MySQL MINUTE() returns a minute from a time or datetime value.|
|MONTH()|MySQL MONTH() returns the month for the date within a range of 1 to 12 ( January to December).|
|MONTHNAME()|MySQL MONTHNAME() returns the full name of the month for a given date.|
|NOW()|MySQL NOW() returns the value of current date and time in ‘YYYY-MM-DD HH:MM:SS’ format or YYYYMMDDHHMMSS.uuuuuu format depending on the context (numeric or string) of the function.|
|PERIOD_ADD()|MySQL PERIOD_ADD() adds a number of months with a period and returns the value in the format YYYYMM OR YYMM. Remember that the format YYYYMM and YYMM are not date values.|
|PERIOD_DIFF()|MySQL PERIOD_DIFF() returns the difference between two periods.|
|QUARTER()|MySQL QUARTER() returns the quarter of the year for a date.|
|SEC_TO_TIME()|MySQL SEC_TO_TIME() returns a time value by converting the seconds specified in the argument.|
|SECOND()|MySQL SECOND() returns the second for a time.|
|STR_TO_DATE()|MySQL STR_TO_DATE() returns a datetime value by taking a string and a specific format string as arguments.|
|SUBDATE()|MySQL SUBDATAE() subtracts a time value (as interval) from a given date.|
|SUBTIME()|MySQL SUBTIME() subtracts one datetime value from another.|
|SYSDATE()|MySQL SYSDATE() returns the current date and time in YYYY-MM-DD HH:MM:SS or YYYYMMDDHHMMSS.uuuuuu format depending on the context of the function.|
|TIME_FORMAT()|MySQL TIME_FORMAT() converts a time in a formatted string using the format specifiers.|
|TIME_TO_SEC()|MySQL TIME_TO_SEC() converts a time value in to seconds.|
|TIME()|MySQL TIME() extracts the time part of a time or datetime expression as string format.|
|TIMEDIFF()|MySQL TIMEDIFF() returns the differences between two time or datetime expressions.|
|TIMESTAMP()|MySQL TIMESTAMP() returns a datetime value against a date or datetime expression.|
|TIMESTAMPADD()|MySQL TIMESTAMPADD() adds time value with a date or datetime value.|
|TIMESTAMPDIFF()|MySQL the TIMESTAMPDIFF() returns a value after subtracting a datetime expression from another.|
|TO_DAYS()|MySQL TO_DAYS() returns number of days between a given date and year 0.|
|UNIX_TIMESTAMP()|MySQL UNIX_TIMESTAMP() returns a Unix timestamp in seconds since '1970-01-01 00:00:00' UTC as an unsigned integer if no arguments are passed with UNIT_TIMESTAMP().|
|UTC_DATE()|MySQL UTC_DATE returns the current UTC (Coordinated Universal Time) date as a value in 'YYYY-MM-DD' or YYYYMMDD format depending on the context of the function i.e. in a string or numeric context.|
|UTC_TIME()|MySQL UTC_TIME returns the current UTC time as a value in 'HH:MM:SS' or HHMMSS format depending on the context of the function i.e. in a string or numeric context.|
|UTC_TIMESTAMP()|In MySQL the UTC_TIMESTAMP returns the current UTC date and time as a value in 'YYYY-MM-DD HH:MM:SS' or YYYYMMDDHHMMSS.uuuuuu format depending on the usage of the function i.e. in a string or numeric context.|
|WEEK()|MySQL WEEK() returns the week number for a given date.|
|WEEKDAY()|MySQL WEEKDAY() returns the index of the day in a week for a given date (0 for Monday, 1 for Tuesday and ......6 for Sunday).|
|WEEK OF YEAR()|MySQL WEEKOFYEAR() returns the calender week (as a number) of a given date.|
|YEAR()|MySQL YEAR() returns the year for a given date.|
|YEARWEEK()|MySQL YEARWEEK() returns year and week number for a given date.|