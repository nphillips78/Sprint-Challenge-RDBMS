1. Explain the difference between RDBMS and SQL.
   An RDBMS is a system, the database software itself. It handles everything to do with the database - storage, querying, updating, etc using relational data. SQL is the Structured Query Language that we use to talk to the database.
2. Why do tables need a primary key?
   Primary keys ensure that data in a specific column are unique and allow you to access and modify rows without altering any other rows in the same table.
3. What is the name given to a table column that references the primary key on another table?
   ..Foreign key
4. What do we need to have a many to many relationship between two tables?
   Junction table
5. What SQL statement is used to retrieve data from a table?
   SELECT
6. What SQL clause is used to filter the results of a query?
   WHERE
7. What are views? Provide one example use case for them.
   Views are essentially saved searches. If you'll need to access certain data with the same filters frequently, you can save the view and run it whenever you need. A good reason to use a view would be in customer management systems - for example, a view of leads that need follow ups.
