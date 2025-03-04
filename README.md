# Event Booking System (Golang)

This is a practice project built with **Golang** to create an **Event Booking System** with user authorization.

## Features
- User Registration & Login (JWT Authorization)
- Event Creation
- List Events
- Event Booking

## Tech Stack
- Golang
- Gin (Web Framework)
- GORM (ORM)
- SQLite (Database)
- JWT Authentication

## Installation

### Prerequisites
- Go 1.21+

### Clone the Repository
```bash
git clone https://github.com/nuttnonn/event-booking-golang.git
cd event-booking-golang
```

### Install Dependencies
```bash
go mod tidy
```

### Environment Variables
Create a `.env` file in the root folder and set the following environment variables:
```env
JWT_SECRET=your_secret_key
DATABASE_URL=event.db
```

### Run the Server
```bash
go run main.go
```
The server will run at `http://localhost:8080`

## API Endpoints
| Method | Endpoint    | Description     |
|--------|------------|----------------|
| POST   | /register  | Register User   |
| POST   | /login     | User Login      |
| GET    | /events    | List Events     |
| POST   | /events    | Create Event    |

## Folder Structure
```
├── models         # Database Models
├── routes         # API Routes
└── main.go        # Entry Point
```

## License
This project is for learning purposes only.

