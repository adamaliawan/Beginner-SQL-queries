# SQL Basics: Sakila Database Query Exercises

This project involves solving basic SQL queries using the Sakila database, a popular sample database for learning SQL. The queries focus on retrieving and manipulating data from the Sakila database, which stores information about a fictional DVD rental store.

## Project Overview

The main objectives of this project are:
- To demonstrate proficiency in writing SQL queries.
- To answer common business-related questions using data from the Sakila database.
- To explore basic SQL concepts such as data retrieval, filtering, aggregation, and joining tables.

## Dataset

The Sakila database contains several tables that represent a typical business scenario for a DVD rental store, including information about:
- **Films**: Details about the movies available for rent.
- **Actors**: Information on actors appearing in films.
- **Customers**: Details about the customers renting the movies.
- **Rentals**: Information on rental transactions.
- **Payments**: Data about payments made by customers.
- **Stores**: Information on physical stores where rentals are made.

## Key SQL Concepts Covered
- **SELECT**: Retrieve data from one or more tables.
- **WHERE**: Filter data based on specific conditions.
- **JOIN**: Combine rows from two or more tables based on related columns.
- **GROUP BY**: Group data to perform aggregate calculations (e.g., count, sum).
- **ORDER BY**: Sort query results based on one or more columns.
- **LIMIT**: Restrict the number of rows returned by a query.

## Example Queries

1. **Retrieve a list of all films with their rental prices and length**:
   ```sql
   SELECT title, rental_rate, length 
   FROM film;
