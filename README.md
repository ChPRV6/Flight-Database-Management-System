
# FlightConnect — A MERN Stack Project

A Full-Stack Flight Booking Web Application built using the MERN Stack (MongoDB, Express.js, React.js, Node.js).  
This project replicates a flight booking system with features like passenger management, flight scheduling, ticket booking, fare calculation, and crew details.

## Tech Stack

| Layer        | Technology                      |
|-------------|----------------------------------|
| Frontend     | React.js, Axios, Tailwind CSS (Optional) |
| Backend      | Node.js, Express.js             |
| Database     | MongoDB, Mongoose ORM           |
| Authentication | JWT (JSON Web Token) for secure login  |

## Features

- User Registration & Login (JWT Authentication)
- Admin & User Roles
- CRUD Operations for:
  - Passengers
  - Airports
  - Airplanes & Models
  - Flights
  - Tickets & Boarding Pass
- Search Flights & Book Tickets
- View Booking History
- Fare Calculation based on Airports

## Project Structure

flight-booking-mern/
│
├── client/                  # React Frontend
│   ├── src/
│   │   ├── components/      # Reusable Components
│   │   ├── pages/           # Pages like Home, Login, Dashboard
│   │   ├── services/        # API Calls (Axios)
│   │   └── App.js
│
├── server/                  # Express Backend
│   ├── models/              # Mongoose Schemas
│   ├── routes/              # API Endpoints
│   ├── controllers/         # Business Logic
│   ├── middleware/          # Authentication Middleware
│   ├── server.js            # Backend Entry Point
│
└── .env                     # Environment Variables
└── package.json             # Project Config
└── README.md                # Project Documentation

## How To Run This Project

### Prerequisites

- Node.js installed (v18+)
- MongoDB installed locally or use MongoDB Atlas
- npm or yarn installed

### 1. Clone the Repository

git clone https://github.com/yourusername/FlightConnect.git
cd FlightConnect

### 2. Backend Setup

cd server
npm install

Create `.env` file in `server/` folder:

PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key

Run the server:

npm run dev

### 3. Frontend Setup

cd client
npm install
npm start

