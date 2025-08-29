# Hotel Reservation API

## Description
This API allows users to search available rooms, book a reservation, view reservation details, and cancel reservations.

## Features
- Search available rooms by date, type, and guests
- Create a reservation
- View reservation details
- Cancel a reservation

## Technology
- Spring Boot (Java)
- Spring Data JPA
- MySQL Database

## Installation
1. Clone the repository
2. Import the project in your IDE
3. Run `mvn spring-boot:run`
4. API runs on `http://localhost:8080`

## Example Requests
### Get available rooms
`GET /rooms?date=2025-09-01&type=Deluxe`

Response:
```json
[
  { "id": 1, "type": "Deluxe", "price": 120, "available": true }
]
