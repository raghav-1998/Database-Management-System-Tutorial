A **Database** is a shared collection of logically related data and description of these data, designed to meet the information needs of an organization.

A **Database Management System (DBMS)** is a software system that enables users to define, create, maintain, and control access to the database. Database Systems typically have high costs and require high-end hardware configurations

An **Application Program** communicates with a database by issuing an appropriate request (typically a SQL statement)


**Function of DBMS:**

1.	**Data management**: Store, retrieve & modify data.
2.	**Transaction support**: Ensure modification to database must either successful or not done at all.
3.	**Concurrency Control**: Simultaneous data access to provider
4.	**Recovery**: Recovery mechanism of data so nothing is lost
5.	**Security**: Access to authorized user.
6.	**Integrity**: Maintain accuracy of data.
7.	**Utilities**: Data import/export, user management, backup , performance analysis & 	    logging




**Types of Database System**
1. **Hierarchical (Tree Structure)**: 
Hierarchical Databases organize data into a tree-like structure. Data is stored as records which are connected to one another through parent child relationships. Some examples of Hierarchical Databases are Information Management System (IMS), Raima Database Manager (RDM) Mobile etc.

2. **Network (Graph structure)**:
Network Databases organize data into a graph structure in which object types are nodes and relationship types are arcs. Each record can have multiple parent and child records. Some examples of Network Databases are Integrated Database Management System (IDMS), Integrated Data Store (IDS) etc.

3. **Relational Database (Tabular)**:
Relational Databases organizes data into one or more tables. A table consists of attributes (columns), tuples (rows) and provides a way to uniquely identify each tuple. Tables are related to each other through parent child relationships. Some examples of Relational Databases are DB2, Oracle, SQL Server etc.

4. **NoSql (Key-Value Pair)**:
NoSQL (Not only SQL) database uses key-value, graph or document data structures to store data. These databases aim for simplicity of design, horizontal scaling and finer control over availability. Some examples on No Sql databases are Cassandra, MongoDB, CouchDB, OrientDB, HBASE etc.


**Relational Model**


|Id|Ename|Salary|Bonus|Dept|
|--+-----+------+-----+----|
|1 |James|75000  |1000 |ICP|
|2 |Ethan|90000  |2000 |ETA|
|3 |Emily|25000  |     |ETA|
|4 |Jack |30000  |1000 |ETA|

Employee(Id,Ename,Salary,Bonus,Dept)

1. Relational Databases store data in relations i.e. tables. Each relation must have a name.
2. An attribute is a named column of a relation. It stores a specific information about an object e.g. salary.
3. A tuple is a row in a relation. It represents relationship between attributes that can contain single value.
4. Cardinality of relation is the number of rows it contains. e.g. Cardinality of relation above is 4.
5. Degree of relation is the number of attributes it contains. e.g. Degree of relation above is 5.
6. NULL represents the value of an attribute that is currently unknown or not applicable. e.g. Bonus in 3rd row.
7. A domain is the set of allowable values for one or more attributes. e.g. Domain of Dept is {ICP,ETA}
8. A collection of relations with distinct relation names is called as Relational Model.











