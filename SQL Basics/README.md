**Structured Query Language (SQL)** is used to manage data in all relational databases like DB2, Oracle, SQL Server etc.

**SQL Commands and Data Types**
1. **Data Definition Language(DDL):**
Data Definition Language is used to specify the structure i.e. schema of a relational database. DDL provides commands for creation, modification and deletion of various database objects like tables, views, stored procedures, indexes, constraints etc. The output of DDL is placed in data dictionary which contains metadata i.e. data about data.
    1. **CREATE**:Creating new database object.
    2. **ALTER**: Modify existing database object.
    3. **DROP**: Deleting existing database object.
    4. **TRUNCATE**: Remove all rows from table.

2. **Data Manipulation Language(DML):**
Data Manipulation Language enables users to access or manipulate data in a relational database. DML provides commands for retrieval, creation, deletion and modification of information in a database. DML requires a user to specify what data is needed without specifying how to get it. The database engine is left to figure out effective means of retrieving data.
    1. **INSERT**: Create new rows in table.
    2. **UPDATE**: Modify data in table.
    3. **DELETE**: Delete data from table.
    4. **SELECT**: Retrieve data from table.

3. **Data Control Language(DCL):**
Data Control Language enables users to provide access to various database objects like views, tables, stored procedures etc. in a relational database. Typically only DBAs have access to grant and revoke privileges. Whenever a user submits a query, the database checks against the granted privileges and rejects the query if it is not authorized.
    1. **GRANT**:Provide access right on database.
    2. **REVOKE**: Withdraw access right on database.

4. **Transaction Control Language(TCL):**
Transaction Control Language specifies commands for beginning and ending a transaction. A transaction consists of a sequence of SQL statements that are applied in an atomic (all or none) manner. A commit makes all the changes applied by the transaction permanent on the database while a rollback undoes all the changed applied by the transaction.
    1. **COMMIT**:Save database changes and end transaction.
    2. **ROLLBACK**: Undo changes that are not committed and end transaction.