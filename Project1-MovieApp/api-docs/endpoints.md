# API Endpoints - Movie Review App

## POST /api/login
Authenticate user

Request:
```json
{
  "email": "user@example.com",
  "password": "password123"
}
```

Response:
```json
{
  "token": "jwt-token"
}
```

---

## GET /api/movies
Get all movies with reviews

Response:
```json
[
  {
    "title": "Inception",
    "reviews": [
      {
        "user": "Alice",
        "rating": 5,
        "comment": "Great movie!"
      }
    ]
  }
]
```
