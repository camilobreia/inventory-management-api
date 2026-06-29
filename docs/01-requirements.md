# 01 - Requirements

## Project Overview

The Inventory Management API is a RESTful API designed to help companies manage products, suppliers, categories and inventory movements. The system provides secure authentication, role-based authorization, stock control, inventory history, dashboards and reporting features.

---

# Functional Requirements

## Authentication

- Users must be able to sign in.
- Users must receive an Access Token and a Refresh Token.
- Users must be able to refresh expired access tokens.

## User Management

- Administrators can create users.
- Administrators can update users.
- Administrators can deactivate users.
- Administrators can list users.

## Role Management

- The system must support at least two roles:
  - Admin
  - Employee

## Product Management

- Create products.
- Update products.
- Delete (soft delete) products.
- List products.
- Search products.
- Filter products.
- Upload product images.

## Category Management

- Create categories.
- Update categories.
- Delete categories.
- List categories.

## Supplier Management

- Create suppliers.
- Update suppliers.
- Delete suppliers.
- List suppliers.

## Inventory

- Register stock entries.
- Register stock withdrawals.
- Keep inventory movement history.
- Display current stock.

## Dashboard

- Display total products.
- Display low stock products.
- Display recent inventory movements.

## Logs

- Record important system actions.

---

# Non-Functional Requirements

- REST API architecture.
- TypeScript.
- Express.
- PostgreSQL.
- Prisma ORM.
- Redis for caching.
- JWT Authentication.
- Refresh Token support.
- Docker support.
- Swagger documentation.
- Unit and integration tests.
- Input validation.
- Pagination.
- Filtering.
- Environment variables.
- Clean architecture principles.
