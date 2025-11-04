# 📦 WarehouseManagementWeb

**WarehouseManagementWeb** - веб-приложение для управления складом.

**Демо:** [https://devproduct.ru](https://devproduct.ru)

## Стек
- **Backend:** ASP.NET Core 9.0
- **Frontend:** Angular

## Архитектура
```mermaid
flowchart LR
    A[Angular] -->|HTTP| B[ASP.NET Core]
    B -->|Dapper| C[(Database)]
```
