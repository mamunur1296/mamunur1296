# Md. Mamunur Rushid

**Software Engineer | .NET & Backend Architecture Specialist**  
📍 Dhaka, Bangladesh &nbsp;|&nbsp; 📧 [mamunurrushid60@gmail.com](mailto:mamunurrushid60@gmail.com) &nbsp;|&nbsp; 📱 +8801767988385

<p>
  <a href="https://www.linkedin.com/in/mamunur-rushid-2910821b6" target="_blank"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="https://github.com/mamunur1296" target="_blank"><img src="https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white" alt="GitHub" /></a>
  <a href="https://leetcode.com/mamunurrushid60/" target="_blank"><img src="https://img.shields.io/badge/LeetCode-FFA116?style=flat&logo=leetcode&logoColor=white" alt="LeetCode" /></a>
  <a href="https://codeforces.com/profile/Mamunur-Rushid" target="_blank"><img src="https://img.shields.io/badge/Codeforces-1F8ACB?style=flat&logo=codeforces&logoColor=white" alt="Codeforces" /></a>
</p>

---

### 👨‍💻 Executive Summary

Dedicated **Software Engineer with 2.7+ years of hands-on experience** architecting high-throughput, maintainable RESTful APIs and distributed backend systems using **C# and .NET (9 / 10)**.

- 🏛️ **Architectural Focus:** Deep practitioner of **Clean / Onion Architecture**, **Domain-Driven Design (DDD)**, **CQRS (MediatR)**, and **Event-Driven Systems**.
- ⚡ **High-Performance Data Access:** Specialized in blending **Dapper (Micro-ORM)** for latency-critical database queries with **Entity Framework Core** for complex domain mapping and migrations.
- 🔄 **Reliability & Consistency:** Experienced in designing **Transactional Outbox Patterns**, automated background job processors (**Hangfire**), and distributed caching (**Redis**).
- 🎓 **Education:** Pursuing **Master's in Information Technology (M.Sc. IT)** at *Jahangirnagar University*.

---

### 🛠️ Technical Arsenal

| Category | Technologies & Tools |
| :--- | :--- |
| **Languages & Core** | `C#`, `.NET 10 / 9 / 8 / 6`, `TypeScript`, `JavaScript`, `SQL` |
| **Backend Frameworks** | `ASP.NET Core Web API`, `ASP.NET Core MVC`, `ASP.NET Core Identity` |
| **Data Access & ORM** | `Dapper (Micro-ORM)`, `Entity Framework Core`, `ADO.NET` |
| **Architecture & Patterns** | `Clean / Onion Architecture`, `Domain-Driven Design (DDD)`, `CQRS (MediatR)`, `Transactional Outbox`, `Repository & Unit of Work`, `SOLID Principles` |
| **Databases & Caching** | `PostgreSQL`, `Microsoft SQL Server`, `Redis (Distributed Caching)`, `MySQL` |
| **Background Jobs & Real-Time**| `Hangfire`, `Background Worker Services`, `SignalR` |
| **DevOps & Cloud** | `Docker`, `Docker Compose`, `GitHub Actions (CI/CD)`, `Git`, `Azure DevOps` |
| **Testing & Quality** | `NUnit`, `Moq`, `FluentValidation`, `Automapper`, `Swagger / OpenAPI` |

---

### 🏛️ Flagship Engineering Projects

#### 1. [Enterprise Library Management System (LibraryMS)](https://github.com/mamunur1296/LibraryMS)
> **Enterprise-grade, distributed RESTful backend built on .NET 10 and Clean Architecture.**

* **Clean Architecture & DDD:** Strict physical separation across `Domain`, `Application`, `Infrastructure`, and `HttpApi` layers, enforcing rich domain models (`Book`, `Member`, `Borrow`, `Reservation`).
* **CQRS with MediatR Behaviors:** Complete command/query separation with cross-cutting pipeline behaviors for automated request logging, validation (`FluentValidation`), and resilient retry policies with exponential backoff.
* **Transactional Outbox Pattern:** Utilized custom EF Core Interceptors (`AuditableEntityInterceptor`, `DomainEventToOutboxInterceptor`) ensuring database consistency and guaranteed asynchronous event delivery.
* **Automated Background Engine:** Handled outbox message processing and recurring daily late-fine accumulation ($2.00/day) via **Hangfire**, paired with **MailKit** for transactional email alerts.
* **Performance & Reporting:** Integrated **Redis Distributed Caching** for instant catalog reads and applied the **Strategy Pattern** for export pipelines (Excel & PDF).
* **Tech Stack:** `.NET 10`, `ASP.NET Core Web API`, `EF Core`, `PostgreSQL`, `Redis`, `Hangfire`, `MediatR`, `Docker`, `GitHub Actions`, `NUnit`
* 🔗 **[Explore Repository & Documentation →](https://github.com/mamunur1296/LibraryMS)**

---

#### 2. [Dynamic Role-Based Access Control & Dapper Engine (App.Api)](https://github.com/mamunur1296/Dapper_Tamplate_Role/tree/master/App.Api)
> **High-performance API framework featuring reflection-based action discovery and dynamic RBAC.**

* **Automated Action Discovery:** Built an assembly-scanning `ActionDiscoveryService` using .NET Reflection to automatically discover controllers, actions, and auto-seed granular permissions into SQL Server at startup.
* **3-Tier Dynamic RBAC:** Granular authorization engine governing `Menu` → `SubMenu` → `Controller Action`, secured with custom action filters (`MyAuthGuardAttribute`).
* **Hybrid ORM Architecture:** Combined EF Core for identity management with **Dapper (Micro-ORM)** for ultra-fast, low-latency querying and bulk transaction processing.
* **Repository & Unit of Work:** Decoupled data access logic with transaction management over raw Dapper connections.
* **Enterprise Middlewares:** Configured custom Global Exception Handling for standard RFC-7807 responses and User Context middleware for claim injection.
* **Tech Stack:** `ASP.NET Core Web API`, `Dapper`, `Entity Framework Core`, `SQL Server`, `Identity Core`, `JWT Bearer`, `AutoMapper`
* 🔗 **[Explore Repository & Documentation →](https://github.com/mamunur1296/Dapper_Tamplate_Role/tree/master/App.Api)**

---

#### 3. [English Learning Platform API](https://github.com/mamunur1296/English_Larnign_Api)
> **Educational platform backend designed with Clean Architecture and modular user management.**

* Applied Clean Architecture principles isolating business use cases with MediatR and AutoMapper.
* Implemented token-based session management, refresh token rotation, and role authorization via ASP.NET Identity.
* Designed responsive administrative views and client interactions using MVC, jQuery, and AJAX.
* **Tech Stack:** `.NET Core 6 / 8`, `ASP.NET Core Web API & MVC`, `SQL Server`, `EF Core`, `JWT`, `Bootstrap`
* 🔗 **[Explore Repository →](https://github.com/mamunur1296/English_Larnign_Api)**

---

### 📈 Contribution Activity

<div align="center">
  <a href="https://github.com/mamunur1296">
    <img src="https://streak-stats.demolab.com?user=mamunur1296&theme=tokyonight&hide_border=true&date_format=M%20j%5C%2C%20Y" alt="GitHub Streak Stats" width="60%" />
  </a>
</div>

---

<div align="center">
  <p><i>Looking for collaboration on distributed systems or open-source .NET initiatives? Let's connect!</i></p>
  <a href="https://www.linkedin.com/in/mamunur-rushid-2910821b6" target="_blank"><img src="https://img.shields.io/badge/Connect_on_LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="Connect on LinkedIn" /></a>
  <a href="mailto:mamunurrushid60@gmail.com"><img src="https://img.shields.io/badge/Send_an_Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Send Email" /></a>
</div>
