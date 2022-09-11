# Persistence Layer

This will contain all data access configurations, abstractions, and contexts.

## Overview

* 📌 DbContexts
* 📌 Migrations
* 📌 Configurations
* 📌 Seeding
* 📌 Abstractions

### Unit of Work & Repository Patterns

Should we implement these patterns?

When using EF 6 or EF Core, then it isn't always the best choice, because:

* ❣ EF Core insulates your code from database changes;
* ❣ DbContext acts as a unit of work;
* ❣ DbSet acts as a repository;
* ❣ EF Core has features for unit testing without repositories.

## Key Points

* ✅ Independent of the database;
* ✅ Use Fluent API Configuration over Data Annotations;
* ✅ Prefer conventions over configuration;
* ✅ Automatically apply all entity type configurations.
