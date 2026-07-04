# Guider — .NET Microservices Backend (2023)

> ⚠️ This is an **archived project** — a prototype backend built in early 2023. It is NOT the current Guider LMS.

## What This Is

An early attempt at a Guider application using a .NET microservices architecture. Not in active use.

## Tech Stack

| Layer | Tech |
|---|---|
| Language | C# (.NET) |
| Architecture | Microservices |
| API Gateway | ASP.NET Web API (`GuiderGateway.WebApi`) |
| Services | `Class.Microservice`, `User.Microservice` |
| Data | `GuidersData` (data layer) |
| Solution file | `Guider.sln` |

## Structure

```
Guider.sln
├── GuiderGateway.WebApi/     — API Gateway entry point
├── Class.Microservice/       — Handles class-related logic
├── User.Microservice/        — Handles user-related logic
└── GuidersData/              — Shared data/models layer
```

## Status

**Archived.** The active Guider LMS is a separate project using PHP + Vue.js + MySQL, running on XAMPP.
