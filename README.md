# SQL-Challenge
This is the 7th homework from the coding bootcamp course.
This is about the use of a SQL to explore data, it invovles data modeling, data engineering and data analysis which is are parts of a everyday task as a data analyist.

## Key Reflects

### New Findings
The PostgreSQL is used in this homework, it is a free-open resource to store and explore a database. ERD, which aka 'Entity Relationship Diagram' is used to understand the parts(tables) within a database. It is very handy to understand what are the contents(columns) and relationships between different columns over different tables. 

The data engineering part is to build the table schema of the model(database), and then import contents(values) to the corresponding tables. Some of the key notes:
  1. A foreign key can only reference to a unique column in another table, or, to the primary key in another table;
  2. When having foreign keys, the tables should be created in order and start with the one has no FK to any other table so that the FK will work;
  3. Sometimes for a table, a single column cannot be used as the primary key as it cannot reference to a unique row of data, then multiple column should be set as primary keys, aka 'composite key' so that it can work together to point out an unique row;
  4. When importing CSV files to fill the values in tables, should note that the table columns should be the same as the csv headers and set the correct delimiters

The data analysis part is more about selecting required values from columns, applying joins, unions, conditions etc. It is good to create a view after a desired table is shown for further development.

There is also a simply application about the sqlalchemy when use python to editing a databse.

### Uncertainties
1. When set up the value type in a table column, I used 'DATE' but it cannot read a date format as MM/DD/YYYY so I changed to VARCHAR. Wonder if there is specific type in SQL to read different date format.



