# database

## T-SQL / Transact-SQL

Is Microsoft's proprietary extension to SQL (Structured Query Language).

T-SQL expands on the SQL standard to include local variables, various support functions for string processing, date processing, mathematics, etc. and changes to the DELETE and UPDATE statements.

## SSMS

SSMS / SQL Server Management Studio

## DDL

Data Definition Language. For creating a database e.g. CREATE, DROP, ALTER, RENAME, COMMENT

## DCL

Data Control Language. For administering a database e.g. GRANT, DENY, USE 

#### For example, assume you wish to grant the user the ability to retrieve information from the specific table in a database called dbo (default database name)
```sql
GRANT SELECT, INSERT, UPDATE, DELETE ON dbo.table_name TO [domain\user_name];
```

## DML

Data Manipulation Language. To access a database e.g. SELECT, INSERT, UPDATE, DELETE

## Index

An index is one way of providing quicker access to data. Without indexes we will have to read the entire table to find what we are loading for.

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

## 3NF

Third Normal Form (3NL)
A relation that is in 1NF and 2NF and in which no non-primary key attribute is transitively dependent on the primary key.
Based on concept of transitive dependency: A, B and C are attributes of a relation such that if A -> B and B -> C then C is transitively dependent on A through B (provided that A is not functionally dependent on B or C)


## Basics

To make execution time shorter (disable statistics which are printed on the console):
`SET NOCOUNT ON;`

@ID means it's a parameter that you will supply a value for later in your code.

`a != b`
is equivalent to
`a <> b`

`WHERE name IN ('x', 'y', 'z', etc.)`
