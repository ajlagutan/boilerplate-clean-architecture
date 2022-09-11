# Application Layer

This layer contains all application logic. It is dependent on the domain layer, but has no dependencies on any other layer or project.

This layer defines interfaces that are implemented by outside layers.

## Overview

* 📌 Interfaces
* 📌 Models
* 📌 Logic
* 📌 Commands/Queries (CQRS)
* 📌 Validators
* 📌 Exceptions

### Why CQRS?

* ❣ Command Query Responsibility Segregation;
* ❣ Separates reads (queries) from writes (commands);
* ❣ Can maximise performance, scalability, and simplicity;
* ❣ Easy to add new features, just add a new query or command;
* ❣ Easy to maintain, changes only affect one command or query.

#### MediatR + CQRS = ❤

* ❣ Define commands and queries as requests;
* ❣ Application layer is just a series of request/response objects;
* ❣ Ability to attach additional behaviour before and/or after each request, e.g. logging, validation, caching, authorisation, and so on.

## Key Points

* ✅ Using CQRS + MediatR simplifies your overall design;
* ✅ Fluent Validation is useful for all validation scenarios;
* ✅ MediatR simplifies cross cutting concerns;
* ✅ Independent of infrastructure and data access concerns.
