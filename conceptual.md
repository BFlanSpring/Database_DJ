### Conceptual Exercise

Answer the following questions below:

#### _**What is PostgreSQL?**_
PostgreSQL is an open source database management system, this system is open source meaning it can be freely used, modified, and distributed by anyone who would like ot use it. It is alos important to note that PostgreSQL is a relational database, storing and managing data in structured and organized tables. PostgreSQL supports structured query language for querying, defining and manipulating data. 

#### _**What is the difference between SQL and PostgreSQL?**_
SQL stands for structured query language that is used to interact with relational databases providing a common syntax for defining, querying and manipulating data in any relational DB system. SQL isnt a database system, its a language standard, whereas PostgreSQL is the database managemnt system itself.

#### _**In `psql`, how do you connect to a database?**_
To connect to a database using PSQL, you have to first install PSQL and run the command sudo service postgresql start, once it loads up, run the command psql. Once your into psql, run \l to view all available databases and then \c database_name to connect to your desired database.

#### _**What is the difference between `HAVING` and `WHERE`?**_
WHERE is used to filter rows **BEFORE** they are grouped, whereas HAVING  is used to gilter groups of rows **AFTER** they are grouped. WHERE is used to specify conditions that rows must meet to be included in the result, Having is used to specify conditions that the aggregated groups of rows must meet ot be included in the set.

#### _**What is the difference between an `INNER` and `OUTER` join**_
Both INNER and OUTER JOIN are very important and useful when merging certain aspects of different tables. JOIN and INNER JOIN are the same, they join only the rows that match the condition of both tables, whereas OUTER JOIN has methoids that can join LEFT, RIGHT and FULL. Merge all rows from left table combined with mathcing rowns from other table, RIGHT is the sam just flipped and full merges all rows from both tables.

#### _**What is the difference between a `LEFT OUTER` and `RIGHT OUTER` join?**_
As discussed above, LEFT OUTER JOIN, all rows from the tbale on the left side (left table) are included in the result set, disregrading wether there are matching rows in the table on the rigth side. Rows from the right table are included only if they have matching values in the join condition with the left table. RIGHT OUTER JOIN is the same idea just flipped.

#### _**What is an ORM? What do they do?**_
ORM stands for Object Relational Mapping which is a programming technique and framework that allows developers to work with relation DBs using OOP languages. ORM acts as a bridge between the relational databse and the app's code, allowing the user to interact with the database using high-level, object-oriented constructs instead of writing raw SQL Querys.

#### _**What are some differences between making HTTP requests using AJAX**_
AJAX is a combination of JS and the XMLHttpRequest object and XML, whereas Fetch API is more modern, native JS API introduxed in ES6 for making HTTP requests. AJAX  tends to have a more verbose and complex sytanx comparewd to that of Fetch API, where it uses a cleaner and more intuitive syntax. It is also important to note that making cross-origin request via AJAX is much more difficult that fetch api becuase of it same-origin policy restrcitions. 

#### _**What is CSRF? What is the purpose of the CSRF token?**_
CSRF stands for Cross-Site Request Forgery, it is >"a security vulnerability that occurs when an atatcker tricks a users broser into making an unwanted and potentially malicious request to a different website on which the user is authenicated"
The token acts as a security key that authenticates the user and their requests.

#### _**What is the purpose of `form.hidden_tag()`?**_
The form hidden tag is a function that is typically used to generate an HTML hidden input field containing a CSRF token. Its primary purpose is to include the CSRF toeken in a form of a hiden fiels, which allows the form submission to be protected against CSRF attacks.
