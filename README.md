# Intro to SQL Joins

## Objectives

* Explain the order & structure of join statements
* Write basic SQL joins: `one-to-many`
  - INNER join
  - LEFT join
  - FULL OUTER join
* Write basic SQL joins that only select certain fields
  - INNER join
  - LEFT join

## Instructions

1. Create a database called joins
2. Connect to joins database using psql
3. Run joins.sql file while connected to db:
  - `\i joins.sql`

INNER JOIN going from 'owner' to 'pet'

  Select * FROM owner INNER JOIN pet ON pet.owner_id = owner.id

  

## Resources

* [Learn - Joins Syntax](https://github.com/gSchool/sql-curriculum/blob/master/Joins.md#joins---syntax)
* [Visual Representation of SQL Joins](https://www.codeproject.com/Articles/33052/Visual-Representation-of-SQL-Joins)
