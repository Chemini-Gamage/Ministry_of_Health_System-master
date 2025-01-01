# MERN Project- Ministry Of Health

This project is focused on 3 core actors as PHI, Midwife and the Doctor where 8 different functions would be focused and is built using the MERN stack: **MongoDB, Express.js, React.js, and Node.js**. Follow the steps below to set up and run the project locally.

---

## Prerequisites

Make sure you have the following installed on your system:

- [Node.js](https://nodejs.org/) (v14 or later)
- [MongoDB](https://www.mongodb.com/try/download/community) (or use MongoDB Atlas for a cloud database)
- Git
- A code editor like [VS Code]

Verify installations:
```bash
node -v
npm -v
mongo --version
```

---

## Installation

### 1. Clone the Repository
Clone the repository to your local machine:
```bash
git clone <repository-url>
cd <repository-folder>
```

### 2. Set Up the Backend
1. Navigate to the `backend` directory:
   ```bash
   cd backend
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Create a `.env` file and configure environment variables:
   ```
   MONGO_URI=mongodb://localhost:27017/<database_name>
   PORT=5000
   ```

4. Start the backend server:
   ```bash
   npm run dev
   ```
   The backend server will run on `http://localhost:5000`.

### 3. Set Up the Frontend
1. Navigate to the `frontend` directory:
   ```bash
   cd ../frontend
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Configure the API base URL (if needed) in `.env` or a config file:
   ```
   REACT_APP_API_URL=http://localhost:5000
   ```

4. Start the React development server:
   ```bash
   npm start
   ```
   The frontend will run on `http://localhost:3000`.

---

## Verify Setup

1. Open your browser and navigate to `http://localhost:3000` to access the frontend.
2. Ensure the frontend communicates with the backend API (`http://localhost:5000`) and interacts with MongoDB.

---


## Technologies Used

- **MongoDB**: Database
- **Express.js**: Backend framework
- **React.js**: Frontend library
- **Node.js**: Runtime environment

---

