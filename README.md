# Flator.ir API Documentation

## Base URL
`https://apiurl.com/api/v1`

### General Info
- **Method**: `POST`
- **Response format**: `JSON`

---

## Endpoints

### 1. **New Order**
Create a new order.
- **Parameters**:
  - `key`: Your API key
  - `action`: `add`
  - `service`: Service ID
  - `link`: URL
  - `quantity`: Number of items
  - Optional: `runs`, `interval`

- **Sample Response**:
  ```json
  {
    "status": "success",
    "order": 32
  }
- **Order Status:
  ```json
  {
  "order": "32",
  "status": "pending",
  "charge": "0.0360"
  }

- **Order Status:
  ```json
  [
  {
    "service": "5",
    "name": "Instagram Followers [15K]",
    "rate": "1.02",
    "min": "500",
    "max": "10000"
  }
  ]

- **Check Balance:
  ```json
  {
  "status": "success",
  "balance": "0.03",
  "currency": "USD"
  }

This structure outlines the API documentation and includes essential information for each endpoint.

