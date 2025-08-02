# Drizzle ORM Usage Guide

This document provides instructions on how to use Drizzle ORM with this project.

## Generating Migrations

To generate a new migration based on your schema changes, run the following command:

```bash
npx drizzle-kit generate
```

This will create a new SQL migration file in the `drizzle` directory.

## Applying Migrations

To apply the generated migrations to your database, run the following command:

```bash
npx drizzle-kit migrate
```

This will execute the pending migration files and update your database schema.

## Neon Database

This project is connected to a Neon database. The database connection string is stored in a `.env` file and should be kept secret.
