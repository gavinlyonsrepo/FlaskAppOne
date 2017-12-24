# **NOTE: WORK IN PROGRESS** 

Overview
--------------------------------------------
* Name: FlaskAppOne
* Title : Flask Application one
* Description: Simple application with authentication and CRUD functionality using the Python Flask micro-framework
* Author Gavin Lyons

Table of contents
---------------------------

  * [Overview](#overview)
  * [Table of contents](#table-of-contents)
  * [Installation](#installation)
  * [Usage](#usage)
  * [Files](#files)
  * [Dependencies](#dependencies)
  * [Communication](#communication)
  * [History](#history)
  * [Copyright](#copyright)

Installation
-----------------------------------------------
TODO

Usage
-------------------------------------------

```sh
python app.py
```

Files
-----------------------------------------

| File | Description |
| ------ | ------ |
| app.py | Python script |
| templates | *.html templates |
| templates/include | _*.html include files |

MYSQL database required, name : myflaskapp , password: yourpassword : 

Two tables:

Table one - users

| Field         | Type         | Null | Key | Default           | Extra          |
|---------------|--------------|------|-----|-------------------|----------------|
| id            | int(11)      | NO   | PRI | NULL              | auto_increment |
| name          | varchar(100) | YES  |     | NULL              |                |
| email         | varchar(100) | YES  |     | NULL              |                |
| username      | varchar(30)  | YES  |     | NULL              |                |
| password      | varchar(100) | YES  |     | NULL              |                |
| register_date | timestamp    | NO   |     | CURRENT_TIMESTAMP |                |



Table Two - articles

| Field       | Type         | Null | Key | Default           | Extra          |
|-------------|--------------|------|-----|-------------------|----------------|
| id          | int(11)      | NO   | PRI | NULL              | auto_increment |
| title       | varchar(255) | YES  |     | NULL              |                |
| author      | varchar(100) | YES  |     | NULL              |                |
| body        | text         | YES  |     | NULL              |                |
| create_date | timestamp    | NO   |     | CURRENT_TIMESTAMP |                |



Dependencies
-------------------------------------

Python | python modules

* python 
* flask 
* flask_mysqldb
* wtforms 
* passlib.hash 
* functools 



Communication
-----------
If you should find a bug or you have any other query, 
please send a report.
Pull requests, suggestions for improvements
and new features welcome.
* Contact: Upstream repo at github site below or glyons66@hotmail.com
* Upstream repository: https://github.com/gavinlyonsrepo/FlaskAppOne

History
------------------

TODO

 
Copyright
---------
TODO
