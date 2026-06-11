# Relational storage vs non-relational storage

A relational database stores data in tables that are reletated to one another. A relational database is organised into tables (like excel sheets), and those are made up of ROWS (Individual records) & colums (specific attributes).

# Common relational database
*MySQL*
*SQLite*
*PostgreSQL*
*Microsoft_SQL_Server*

# Relational Storage (SQL)
-The structure: Data is stored in fixed tables with rows and colums.

-The "Rule": You must define a schema (a blueprint) before you add data. Every row in table must have the same colums.

-The strenght: it is excellent for Relationships. You can "join" a suppliers table to a materials table using common D.


# Non-Relational Database/Storage (NoSQL)

*A non relationsal database doesn't require data to be stored in tables with relationship. Instead data may be stored as: Documents, key-value pairs, Graphs, Wide columns.

# Common Non-Relational Databases:
*MongoDB*
*Apache Cassandra*
*Redis*

# Non-Relational Storage (NoSQL)

-The Structure: Data is stored in Documents (like jason files), key value pairs, or Graphs. 

-The "Rule": It is schema-less. One record can have 5 pieces of information, and the next record can have 20. it is flexible.

-The Strenght: it is built for speed & Unstructured data. it handles massive amounts of data that doesn't fit neatly into a grid.
