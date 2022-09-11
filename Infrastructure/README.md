# Persistence Layer

This layer contains classes for accessing external resources such as `file systems`, `web services`, `SMTP`, and so on.
These classes should be based on interfaces defined within the application layer.

## Overview

* 📌 API Clients
* 📌 File System
* 📌 Email and/or SMS
* 📌 System Clock
* 📌 Anything external

## Key Points

* ✅ Contains classes for accessing external resources;
* ✅ Such as `file systems`, `web services`, `SMTP`, and so on;
* ✅ Implements abstractions/interfaces defined within the Application Layer;
* ✅ No layers depends on infrastructure layer.
