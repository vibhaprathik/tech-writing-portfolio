# API Reference: Inventory Management System

## GET /api/products

**Description:**  
Returns a list of all products in the inventory.

**Parameters:**  
None

**Response:**
```json
[
  {
    "id": 101,
    "name": "Widget A",
    "quantity": 42,
    "price": 9.99
  },
  ...
]
