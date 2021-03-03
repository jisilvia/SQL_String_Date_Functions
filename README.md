# SQL String and Date Functions

In SQL, dates are complicated for newbies, since while working with database, the format of the date in table must be matched with the input date in order to insert.

A string function is a function that takes a string value as an input regardless of the data type of the returned value.

## Project Description

This project demonstrates an understanding of Date and String functions by fulfilling various data requests. It also demonstrates knowledge of writing and executing SQL within Jupyter notebook, which is traditionally used for Python code.

## Requirements

**SQL.** Structured Query Language (SQL) is a programming language that is typically used in relational database or data stream management systems.

**SQL Client Software.** A software package designed to define, manipulate, retrieve and manage data in a database, such as:
- [DBeaver](https://dbeaver.io/)
- [MySQL Worbench](https://www.mysql.com/products/workbench/).

**Web Host Service.** A web hosting service is a type of Internet hosting service that allows individuals and organizations to make their website accessible via the World Wide Web.
- [Amazon Web Services (AWS)](https://aws.amazon.com/)

**Python.** Python is an interpreted, high-level and general-purpose programming language. 

**[Jupyter Notebook](https://jupyter.org/)**. Jupyter notebook can be used to view, edit, and run Python code.

### Packages 
```python
!pip install PyMySQL,
import pymysql,
pymysql.install_as_MySQLdb(),
import sqlalchemy
```

## Launch
Install the packages above.
Download the sakila database *sakila_data.sql* and schema *sakila_schema.sql*. Using your web host, create a new database for the downloaded files. Open the sakila schema file in your SQL client software and execute the code. Lastly, open the sakila data file in your SQL client software and execute the code to create the database.

Your SQL code is now ready to run.

## Authors

[Silvia Ji](https://www.linkedin.com/in/silviaji/) - [GitHub](github.com/jisilvia)

## License
This project is licensed under the [MIT](https://choosealicense.com/licenses/mit/) License.

## Acknowledgements

The project template was provided by Gregory Lontok at Loyola Marymount University.

The Dataset used was provided by [MySQL](https://dev.mysql.com/doc/sakila/en/sakila-installation.html).
