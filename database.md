# database

## T-SQL / Transact-SQL

Is Microsoft's proprietary extension to SQL (Structured Query Language).

T-SQL expands on the SQL standard to include local variables, various support functions for string processing, date processing, mathematics, etc. and changes to the DELETE and UPDATE statements.

## SSMS

SSMS / SQL Server Management Studio

## PODS

Pipeline Open Data Structure - a relational data model devised for implementing on RDBMS (Relational Database Management System) platform like Microsoft SQL Server. 

[What is the PODS Pipeline Data Model?](http://www.pods.org/pods-model/what-is-the-pods-pipeline-data-model/)

```sql
/**** EXAMPLE ****/
/*
+------------+--------------+----------------+------------------+------------------+--------------+----------+-----------+-------------+---------------+------------+--------------------+
| CONTROL_ID | TABLE_NAME   | ATTRIBUTE_NAME | USER_NAME        | DESCRIPTION      | ELEMENT_TYPE | CONSTANT | DATA_TYPE | DATA_FORMAT | DATA_GROUP_ID | RELATED_ID | EXTERNAL_REFERENCE |
+------------+--------------+----------------+------------------+------------------+--------------+----------+-----------+-------------+---------------+------------+--------------------+
| CLIENT     | table_name_1 | column_1       | hoursPerWeek     | Hours Per Week   | NULL         | NULL     | D         | DATE        | NULL          | param1     | NULL               |
+------------+--------------+----------------+------------------+------------------+--------------+----------+-----------+-------------+---------------+------------+--------------------+
| CLIENT     | table_name_2 | column_2       | daysPerWeek      | Days Per Week    | NULL         | NULL     | N         | NUMBER      | NULL          | param2     | NULL               |
+------------+--------------+----------------+------------------+------------------+--------------+----------+-----------+-------------+---------------+------------+--------------------+
| CLIENT     | table_name_3 | column_3       | relationshipType | relatioship type | NULL         | NULL     | S         | STRING      | NULL          | param3     | NULL               |
+------------+--------------+----------------+------------------+------------------+--------------+----------+-----------+-------------+---------------+------------+--------------------+
*/
```

NOTE:
CONTROL_ID: All ASP.NET server controls include an ID property that uniquely identifies the control and is the means by which the control is programmatically accessed in the code-behind class.


## Basics

To make execution time shorter (disable statistics which are printed on the console):
`SET NOCOUNT ON;`

@ID means it's a parameter that you will supply a value for later in your code.

`a != b`
is equivalent to
`a <> b`

`WHERE name IN ('x', 'y', 'z', etc.)`
