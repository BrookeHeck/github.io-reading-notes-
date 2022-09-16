# SQL Pre Work Notes
[SQL Bolt Tutorial](https://sqlbolt.com/lesson/introduction)

[Completed Tutorial Screenshots](#CompleteTutorialScreenShots)
## Select Queries
- a statement which declares what dta we are looking for, where to find it, and possibly how to transform
- EXAMPLE:
``` 
SELECT column, another_column
FROM mytable;
```
- You can get all the data from a table with this command
```
SELECT *
FROM mytable;
```

## Queries with Constraints
- The WHERE clause in a query is used to filter out data by checking specific column values to determine whether it should be included in the results
- EXAMPLE:
```
SELECT column, another_column
FROM mytable
WHERE condition
  AND/OR another_condition
```
<img src="./../img/sqlConditions.png" width="500px" height="auto" />
<img src="./../img/sqlConditions2.png" width="500px" height="auto" />

## Filtering and Sorting Query Results
- Use the DISTINCT keyword to get rid of any rows that have a duplicate column value

```
SELECT DISTINCT colomn, another_column
FROM mytable
WHERE conditions(s)
```

- Use ORDER BY to sort your results by a given column in ascending or descending order
```
SELECT column, another_column, …
FROM mytable
WHERE condition(s)
ORDER BY column ASC/DESC
LIMIT num_limit OFFSET num_offset;
```
- LIMIT and OFFSET are used with ORDER BY to reduce the number or rows returned and where to begin counting the number of rows

## Multi-table Queries with JOINS
- the JOIN clause combines row data across two separate tables using a unique key
  - The INNER JOIN matches rows from a first and second table with the same key
  ```
  SELECT column, another_table_column, …
  FROM mytable
  INNER JOIN another_table 
    ON mytable.id = another_table.id
  WHERE condition(s)
  ORDER BY column, … ASC/DESC
  LIMIT num_limit OFFSET num_offset
  ```
  - LEFT, RIGHT, or FULL JOIN allow you to keep data in the results even if there is no match between the keys
  ```
    SELECT column, another_column, …
    FROM mytable
    INNER/LEFT/RIGHT/FULL JOIN another_table 
        ON mytable.id = another_table.matching_id
    WHERE condition(s)
    ORDER BY column, … ASC/DESC
    LIMIT num_limit OFFSET num_offset;
  ``` 

## NULLS in SQL
- Avoid getting null data by using defaults, such as 0
- When it's not possible to do this because default values will skew analysis of data, you can use IS/IS NOT NULL to filter null values

```
SELECT column, another_column, …
FROM mytable
WHERE column IS/IS NOT NULL
AND/OR another_condition
AND/OR …;
```

## Queries with Expressions
- expressions can use mathematical and string functions with basic arithmetic to transform values
- each database has its own set of mathematical, string, and date functions
```
SELECT particle_speed / 2.0 AS half_particle_speed
FROM physics_data
WHERE ABS(particle_position) * 10.0 > 500;
```
  ### Aggregate Functions
  - used to summarize information about a group of rows or data
  ```
  SELECT AGG_FUNC(column_or_expression) AS aggregate_description
  FROM mytable
  WHERE constraint_expression;
  ```
  - We can use the HAVING clause with the GROUP BY clause to filter grouped rows from the result set
  ```
  SELECT group_by_column, AGG_FUNC(column_expression) AS aggregate_result_alias
  FROM mytable
  WHERE condition
  GROUP BY column
  HAVING group_condition;
  ```

## Query Order of Execution
  1. FROM and JOINS - determine the total working data set
  2. WHERE - only include data that satisfy constraint
  3. GROUP BY - group based on common values
  4. HAVING - only include data that satisfy constraint within the groups
  5. SELECT - expressions within select are computed
  6. DISTINCT - duplicate values are discarded
  7. ORDER BY - data is sorted
  8. LIMIT / OFFSET - discard data outside of the range

## Inserting New Data




### Complete Tutorial Screen Shots
<img src="./../img/sqlTutorials/tutorial1.png" width="200px" height="auto" />
<img src="./../img/sqlTutorials/tutorial2.png" width="200px" height="auto" />
<img src="./../img/sqlTutorials/tutorial3.png" width="200px" height="auto" />
<img src="./../img/sqlTutorials/tutorial4.png" width="200px" height="auto" />
<img src="./../img/sqlTutorials/tutorial5.png" width="200px" height="auto" />
<img src="./../img/sqlTutorials/tutorial6.png" width="200px" height="auto" />
<img src="./../img/sqlTutorials/tutorial7.png" width="200px" height="auto" />
<img src="./../img/sqlTutorials/tutorial8.png" width="200px" height="auto" />
<img src="./../img/sqlTutorials/tutorial9.png" width="200px" height="auto" />
<img src="./../img/sqlTutorials/tutorial10.png" width="200px" height="auto" />
<img src="./../img/sqlTutorials/tutorial11.png" width="200px" height="auto" />
<img src="./../img/sqlTutorials/tutorial13.png" width="200px" height="auto" />
<img src="./../img/sqlTutorials/tutorial14.png" width="200px" height="auto" />
<img src="./../img/sqlTutorials/tutorial15.png" width="200px" height="auto" />
<img src="./../img/sqlTutorials/tutorial16.png" width="200px" height="auto" />
<img src="./../img/sqlTutorials/tutorial17.png" width="200px" height="auto" />
<img src="./../img/sqlTutorials/tutorial18.png" width="200px" height="auto" />


