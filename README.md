# test-sqLite

## subjects learned:
* project contain many databases
* database contain many tables
* table contain many rows
* constrains on tables:
  * NN= not null
  * PK= primary key
  * AI= attached running Index
  * U= Unique
  * check= added constrains to check
  * these and more will be elaborate later...
* not case sensitive
* to write comment: --<hjdlkds>--, ctrl+/
* types:
  * Real=float
  * text= not limited string
  * char= string can be limited length =char(50)
* to create new table (page 28):
  ```
  CREATE TABLE company(
ID INT PRIMARY KEY NOT NULL,
NAME TEXT  not NULL,
age int NOT NULL,
address char(50),
salary REAL DEFAULT 0
)
```
* to delete table:
```
DROP TABLE company
```
* to insert new row to company table(page 39):

```
insert into company
(col1,col2,... colN) -- optionaly
values(val1,val2,... valueN)
```
  **NOT Good Practice: if without specify the column names, need to send all values with the exact order.
  ** better to specify the columns name
*pragna table_info('company')- will return the table structure
## extra subjects:
