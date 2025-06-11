# Celestial Bodies Database

This repository contains my solution for the **Celestial Bodies Database** project from the [FreeCodeCamp Relational Database Certification](https://www.freecodecamp.org/learn/relational-databases/).

## Project Overview

The project involves creating a PostgreSQL database named `universe` to model celestial bodies. The database includes the following tables:
- `galaxy`: Stores information about galaxies.
- `star`: Stores information about stars, linked to galaxies.
- `planet`: Stores information about planets, linked to stars.
- `moon`: Stores information about moons, linked to planets.
- `constellation`: Stores information about constellations.

The `universe.sql` file contains the SQL commands to create the database schema and populate it with sample data, meeting all the project requirements.

## Files
- `universe.sql`: The SQL dump file with `CREATE TABLE` and `INSERT` commands for the database.

## How to Use
1. Install PostgreSQL.
2. Run the commands in `universe.sql` to create and populate the `universe` database:
   ```bash
   psql -U postgres < universe.sql
