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


**SQL Data Types:**

1. **Character Data Type**:
SQL supports two character data types for storing printable and displayable characters. They are used for storing information like name, city, description etc.

![image](https://lex.infosysapps.com/content-store/Infosys/Infosys_Ltd/Public/lex_auth_012702851034046464731/web-hosted/assets/sqlchrctrdt.JPG)

2. **Integral Data Type**:
SQL supports SMALLINT, INTEGER and INT data types that are used for storing whole numbers. Unlike other databases, Oracle does not define different size limits for them. They are all treated internally to have 38 digits of precision. Some real-life examples of values are provided below:

![image](https://lex.infosysapps.com/content-store/Infosys/Infosys_Ltd/Public/lex_auth_012702851034046464731/web-hosted/assets/sqlintrgldt.JPG)

3. **NonIntegral Data Type**:
Nonintegral data types have an integer part and a fractional part. Either NUMERIC, DECIMAL or NUMBER data types can be used to store nonintegral numbers.

![image](https://lex.infosysapps.com/content-store/Infosys/Infosys_Ltd/Public/lex_auth_012702851034046464731/web-hosted/assets/precision-scale.png)

Scale is the number of digits allowed after the decimal point. Precision is the total number of significant digits i.e. digits both before and after the decimal point. If Scale is not provided then NUMBER datatype can be used to store integral values.

Precision and Scale of non-integral data type determines the maximum value that can be stored. It also determines, how input data will be modified before storing the value. We can use the following logic to determine the value that will be stored:

![image](https://lex.infosysapps.com/content-store/Infosys/Infosys_Ltd/Public/lex_auth_012702851034046464731/web-hosted/assets/sqlintgrldt.JPG)

![image](https://lex.infosysapps.com/content-store/Infosys/Infosys_Ltd/Public/lex_auth_012702851034046464731/web-hosted/assets/sqlnonintegral.JPG)

4. **Miscellaneous Data Type**:
For storing date and large objects, SQL supports the following data types:

![image](https://lex.infosysapps.com/content-store/Infosys/Infosys_Ltd/Public/lex_auth_012702851034046464731/web-hosted/assets/75a.PNG)

Here are some key events and their dates from history:

![image](https://lex.infosysapps.com/content-store/Infosys/Infosys_Ltd/Public/lex_auth_012702851034046464731/web-hosted/assets/75b.PNG)


