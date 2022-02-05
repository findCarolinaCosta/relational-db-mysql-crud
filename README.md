# Project relational-db-mysql-crud
## _All for one_

[![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://github.com/findCarolinaCosta/relational-db-mysql-crud) No deploy since I only did the tests

In this project I put into practice the manipulation in relational database, using MySQL.

- ✨Good ✨
## Tech Infos

In relational db mysql crud the following technologies are used:

- [SQL](https://en.wikipedia.org/wiki/SQL) - Language for management and use of relational databases. 
- [MYSQL](https://www.mysql.com/) - SQL database engine software.
- [WORKBENCH](https://www.mysql.com/products/workbench/) - Database design graphical tool.
- [Jest](https://jestjs.io/es-ES/docs/testing-frameworks) - Testing Web Frameworks.
- [ESLINT](https://github.com/betrybe/eslint-config-trybe) - JavaScript code analysis software.
- [Northwind](https://github.com/Microsoft/sql-server-samples/tree/master/samples/databases/northwind-pubs) - Database

## Installation and tests

Project relational-db-mysql-crud:
- requires [NPM](https://www.npmjs.com/) v6 to run.
- requires [MYSQL](https://dev.mysql.com/doc/mysql-getting-started/en/)
- [WORKBENCH](https://dev.mysql.com/downloads/installer/) - optional

Make a git clone of the repository.
```
git clone https://github.com/findCarolinaCosta/relational-db-mysql-crud.git
```

Install the dependencies and devDependencies and start the server.

```
cd relational-db-mysql-crud
npm install
```

Instructions for testing your queries:
To run the tests locally, you need to write the following in your terminal:
```sh
MYSQL_USER=<SEU_NOME_DE_PESSOA_USUARIA> MYSQL_PASSWORD=<SUA SENHA> HOSTNAME=<NOME_DO_HOST> PORT=<PORTA> npm test
```

That is, suppose that in order to access the database made in this project you have `root` as your username, `password` as password, `localhost` as host and `1337` as port. Then you would run:
```sh
MYSQL_USER=root MYSQL_PASSWORD=password HOSTNAME=localhost PORT=1337 npm test
```

Using the previous base example, suppose you have not set a password for `root` and are using the default port (3306). In this case, you would run:
```sh
MYSQL_USER=root MYSQL_PASSWORD= HOSTNAME=localhost PORT= npm test
  ```

Tip: environment variables set on the same command line are valid for that command only. If you prefer, you can export the environment variables for the entire _session_ (all commands until you close that terminal). For example:

```sh
export MYSQL_USER=root MYSQL_PASSWORD=password HOSTNAME=localhost PORT=1337
```

And after that you just need to run `npm test` when testing this project.

---

⚠️ **No need to place** `USE northwind` or `SET SQL_SAFE_UPDATES = 0;` at the beginning of your files ⚠️

⚠️ After running the local tests, the `northwind` database is deleted ⚠️

---

- Delete the .git folder to start with a new history.

## Project report
In this project, I developed and practiced the following skills:

- I understood what are databases;
- I understood how Structured Query Language (SQL) is used;
- I understood how tables fit into the database concept;
- I set up a local development environment to practice SQL;
- I understood how to use MySQL Workbench;
- I understood what a SQL query is and what are its command types;
- I generated values with SELECT;
- I selected columns individually with SELECT;
- Renamed and generate columns in a query with AS (Alias);
- Concatenate columns and values with CONCAT;
- Remove duplicate data in a query with DISTINCT;
- I counted the amount of results in a query with COUNT;
- I limited the amount of results in a query with LIMIT;
- I skipped results in a query with OFFSET;
- I ordered the results of a query with ORDER BY;
- Filtered query results with WHERE;
- I used boolean and relational operators in queries;
- I created more dynamic and malleable queries with LIKE;
- I made queries that encompass a range of results with IN and BETWEEN;
- I found and sorted results that include dates;
- I inserted data into tables with INSERT;
- Updated data in tables with UPDATE;
- Deleted data in tables with DELETE;

_Sorry in advance for any grammatical errors_ 😄