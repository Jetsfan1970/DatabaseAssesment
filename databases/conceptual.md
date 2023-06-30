### Conceptual Exercise

Answer the following questions below:

- What is PostgreSQL?

It is a relational database management system.

- What is the difference between SQL and PostgreSQL?

SQL is a language used to communicate with relational databases, while PostgreSQL is a RDBMS. It is a specific implementation that supports SQL.

- In `psql`, how do you connect to a database?

psql nameofdb

- What is the difference between `HAVING` and `WHERE`?

The WHERE clause is used to filter rows before grouping and aggregating, while HAVING is used to filter the result set after grouping. HAVING is used with the GROUP BY clause.

- What is the difference between an `INNER` and `OUTER` join?

An inner join returns only matched rows between the joined tables. It selects rows where the join condition is satisfied in both tables.

An outer join returns both matched and unmatched rows between the joined tbales. It includes all rows from one table and the matching rows from the others.

- What is the difference between a `LEFT OUTER` and `RIGHT OUTER` join?

The difference is in the treatment of unmatched rows and the selection of left and right tables. A left join returns all the left table and the matching right. If there is no match, null values are used in the columns of the right tanle. The right join is the reverse.

- What is an ORM? What do they do?

An ORM is an object-relational mapping program. They map an objected oriented programming language and a relational databse. It allows developers to work with databases as objects in the code.

- What are some differences between making HTTP requests using AJAX
  and from the server side using a library like `requests`?

  AJAX sends HTTP requests directly to the server and client side code is repsonsible for handling the response. it is commonly used to fetch data, submit forms, etc without interupting the user experince. Requsts is used on the server side to send http to an external API or web source.

- What is CSRF? What is the purpose of the CSRF token?

CSRF stands for Cross-Site Request Forgery, and is when an attacker tricks a user into performing unintended actions on a web app where the user is not authenticated. The purpose of the CSRF token is to stop attacks. It is a unqiue value associated with the user's session or form.

- What is the purpose of `form.hidden_tag()`?

It is used to hide html fields in a form. It contains the CSRF token.
