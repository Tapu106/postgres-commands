
![Postgresql Icon](https://sourcegraphstatic.com/blog/postgres-version-update/postgres-version-update.jpg)
***
# Postgresql
 - PostgreSQL is a powerful, open source object-relational database system that uses and extends the SQL language combined with many features that safely store and scale the most complicated data workloads. The origins of PostgreSQL date back to 1986 as part of the POSTGRES project at the University of California at Berkeley and has more than 30 years of active development on the core platform.

 - PostgreSQL has earned a strong reputation for its proven architecture, reliability, data integrity, robust feature set, extensibility, and the dedication of the open source community behind the software to consistently deliver performant and innovative solutions. PostgreSQL runs on all major operating systems, has been ACID-compliant since 2001, and has powerful add-ons such as the popular PostGIS geospatial database extender. It is no surprise that PostgreSQL has become the open source relational database of choice for many people and organisations.
***
## Installation [Windows]
 - follow this link
 ```https://www.postgresql.org/download/windows/ ```
***
After installing postgresql
- a default user 'postgress' and database 'postgres' is created.
- you can access database using GUI Client(pgAdmin) or Command-Prompt(psql) both are installed with the postgresql. 

## From Author
You can find diffrent and better sources for documentation on postgres commands.However, in this repo I have only added those commands which I used.If you have had help from this repo, don't forget to give a star :wink:
***
## Useful Commands
 - ```\l```  - for the list of postgresql databases created in your local machine.
 - ```\du``` -  for the list of users and their roles who have access to the databases.
***
## Creating Databse
```bash CREATE DATABASE db_name; ```
