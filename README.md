# Expenses Tracker Website

## About the project

This is a full-stack expenses tracker application that lets users add, view, and manage daily expenses. The backend uses Node.js, Express and MongoDB. The frontend is built with React.

---

## Prerequisites

- Node.js (>= 14)
- npm
- MongoDB (Atlas or local)

---

## Clone the repository

```bash
git clone https://github.com/shishirshebbar/Expenses-Tracker-Website.git
cd expenses-tracker
```

---

## Backend setup

1. Change to the backend directory and install dependencies:

```bash
cd backend
npm install
```

2. Create a `.env` file in the backend root with at least:

```
PORT=5000
NODE_ENV=development
MONGO_URL=your_mongodb_connection_uri
```

3. Start the backend server:

```bash
npm start
```

The backend will run on http://localhost:5000 (if PORT=5000).

---

## Frontend setup

1. Change to the frontend directory and install dependencies:

```bash
cd frontend
npm install
```

2. Start the frontend app:

```bash
npm start
```

The frontend will open at http://localhost:3000 and expects the backend at http://localhost:5000.

---

## Run both (development)

From the project root you can run both frontend and backend concurrently if a script is provided (e.g., using concurrently):

```bash
npm run dev
```

---

## Notes

- Replace `your_mongodb_connection_uri` with your actual MongoDB connection string.
- Adjust ports in `.env` or frontend config if needed.
