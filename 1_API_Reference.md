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
```
### Error Codes

- **401 Unauthorized** – Invalid API key  
- **500 Internal Server Error**

---

## POST /api/products

### Description  
Creates a new product in the inventory.

### Request Body
```json
{
  "name": "Widget B",
  "quantity": 100,
  "price": 14.50
}
```

---

### ✨ Final Look (Rendered Markdown Preview)

---

### Error Codes

- **401 Unauthorized** – Invalid API key  
- **500 Internal Server Error**

---

## POST /api/products

### Description  
Creates a new product in the inventory.

### Request Body
```json
{
  "name": "Widget B",
  "quantity": 100,
  "price": 14.50
}
```
**Response:**
### 201 Created – Returns the newly created product ID.
