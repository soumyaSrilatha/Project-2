# API Endpoints - Budget Tracker

## POST /api/login
Authenticate user

Request:
```json
{
  "username": "user1",
  "password": "pass123"
}
```

Response:
```json
{
  "token": "jwt-token"
}
```

---

## GET /api/expenses
List all expenses for the user

Response:
```json
[
  {
    "date": "2025-05-01",
    "category": "Food",
    "amount": 15.5,
    "description": "Lunch"
  }
]
```
