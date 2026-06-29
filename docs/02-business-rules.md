# 02 - Business Rules

## User Rules

- Only administrators can create new users.
- Only administrators can update user roles.
- Deactivated users cannot sign in.
- Each user must have exactly one role.

## Product Rules

- Every product must belong to one category.
- Every product must have one supplier.
- Products cannot have negative stock.
- Initial stock must be zero.
- Minimum stock must be greater than or equal to zero.
- Product names must be unique.

## Category Rules

- A category cannot be deleted if it has associated products.
- Category names must be unique.

## Supplier Rules

- A supplier cannot be deleted if it has associated products.
- Supplier names must be unique.

## Inventory Rules

- Stock withdrawals cannot exceed the available quantity.
- Every inventory movement must be recorded.
- Every inventory movement must be associated with the user who performed it.
- Inventory movements cannot be edited or deleted.

## Log Rules

- User sign-in events must be logged.
- Product creation must be logged.
- Product updates must be logged.
- Product deletion must be logged.
- Inventory entries must be logged.
- Inventory withdrawals must be logged.
