# 📦 WarehouseManagementWeb

**WarehouseManagementWeb** - веб-приложение для управления складом.

**Демо:** [https://devproduct.ru](https://devproduct.ru)

## Стек
- **Backend:** ASP.NET Core 9.0
- **Frontend:** Angular

## 🏗️ Архитектура
```mermaid
flowchart LR
    A[Angular Frontend] -->|HTTP| B[ASP.NET Core Backend]
    B -->|Dapper| C[(PostgreSQL Database)]
```
