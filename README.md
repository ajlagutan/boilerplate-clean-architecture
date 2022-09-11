# Clean Architecture Boilerplate

A simple boilerplate for creating projects with clean architecture.

The project structure was taken from Jason Taylor's [NorthwindTraders](https://github.com/jasontaylordev/NorthwindTraders) repository. [PDF Link](https://github.com/jasontaylordev/NorthwindTraders/blob/master/Docs/Slides.pdf)

> **NOTE:** Presentation layer is not included on this boilerplate.

## Architecture & Design

### Overview
* 📌 Independent of frameworks;
* 📌 Independent of UI;
* 📌 Independent of database;
* 📌 Independent of anything external;
* 📌 Testable.

### Key Points
* ✅ **[Domain](Domain)** contains enterprise-wide logic and types;
* ✅ **[Application](Application)** contains business-logic and types;
* ✅ **[Infrastructure](Infrastructure)** (including **[Persistence](Persistence)**) contains all external concerns;
* ✅ **Presentation** and **Infrastructure** depend only on **Application**;
* ✅ **Presentation** and **Infrastructure** components can be replaced with minimal effort.
