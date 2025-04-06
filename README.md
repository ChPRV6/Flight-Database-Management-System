
# FlightConnect - A MERN Stack Project ✈️🌐

FlightConnect is a full-stack web application designed to manage flight bookings, passenger and crew data, ticketing, and airport operations. Built using the MERN stack (MongoDB, Express.js, React, Node.js), this system modernizes the traditional SQL-based version into a robust, interactive, and scalable solution.

---

## 🧩 Project Structure

```
flight-booking-mern/
├── client/                          # React Frontend
│   ├── src/                        
│   │   ├── components/              # Reusable Components
│   │   ├── pages/                   # Pages like Home, Login, Dashboard
│   │   ├── services/               <br> # API Calls (Axios)
│   │   └── App.js                  
│   └── package.json                
├── server/                          # Express Backend
│   ├── models/                      # Mongoose Schemas
│   ├── routes/                      # API Endpoints
│   ├── controllers/                 # Business Logic
│   ├── middleware/                  # Authentication Middleware
│   ├── server.js                    # Backend Entry Point
│   └── .env                         # Environment Variables
├── README.md                        # Project Documentation
└── package.json                     # Project Config
```

---

## 🚀 Getting Started

### 1. Clone the Repository
```bash
git clone https://github.com/yourusername/FlightConnect.git
cd FlightConnect
```

### 2. Backend Setup
```bash
cd server
npm install
```

Create `.env` file in `server/` folder:
```
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
```

Run the backend server:
```bash
npm run dev
```

### 3. Frontend Setup
```bash
cd client
npm install
npm start
```

---

## 🌐 Web Links & Service Endpoints

| Service        | URL                                  | Description                              |
|----------------|--------------------------------------|------------------------------------------|
| Backend API    | http://localhost:5000/api            | Base URL for all API requests            |
| Home Page      | http://localhost:3000/               | React Frontend Landing Page              |
| Login Page     | http://localhost:3000/login          | User Login                               |
| Register Page  | http://localhost:3000/register       | User Registration                        |
| Dashboard      | http://localhost:3000/dashboard      | User Dashboard                           |
| Admin Panel    | http://localhost:3000/admin          | Admin Dashboard for managing data        |
| Flights API    | http://localhost:5000/api/flights    | API to fetch flights data                |
| Passengers API | http://localhost:5000/api/passengers | API to fetch passenger data              |
| Tickets API    | http://localhost:5000/api/tickets    | API to handle ticket booking             |

---

## 🛠 Technologies Used

- **Frontend**: React.js, Axios, TailwindCSS (or Bootstrap)
- **Backend**: Node.js, Express.js
- **Database**: MongoDB with Mongoose ODM
- **Authentication**: JSON Web Tokens (JWT)
- **Tools**: Postman, Git, MongoDB Atlas, VSCode

---

## 🧠 Features

- Full flight, passenger, and ticket management
- Role-based access: Admin & User
- Booking, cancellation, and boarding pass generation
- RESTful API with secure routes
- Real-time data updates from MongoDB

---

## 📂 License

This project is licensed under the MIT License.
