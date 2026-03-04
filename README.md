# Wanna Bet Application

## Overview
Wanna Bet is an innovative betting application that allows users to place bets on various events with ease. With a user-friendly interface and robust backend, users can track their bets, view statistics, and manage their accounts seamlessly.

## Tech Stack
- **Frontend**: React, TypeScript
- **Backend**: Node.js, Express
- **Database**: PostgreSQL
- **Authentication**: JWT

## Features
- User registration and authentication
- Bets listing and creation
- Real-time updates on betting results
- User account management
- Comprehensive API for integration

## Setup Instructions
1. Clone the repository: `git clone https://github.com/Lysidious/wanna-bet.git`
2. Navigate to the project directory: `cd wanna-bet`
3. Install dependencies for the backend:
   ```bash
   cd backend
   npm install
   ```
4. Install dependencies for the frontend:
   ```bash
   cd ../frontend
   npm install
   ```
5. Set up environment variables in a `.env` file based on the provided `.env.example` file.
6. Run the backend server:
   ```bash
   cd backend
   npm start
   ```
7. Run the frontend application:
   ```bash
   cd frontend
   npm start
   ```

## API Documentation
### Authentication
- **POST** `/api/auth/register` - Register a new user
- **POST** `/api/auth/login` - Authenticate user

### Bets
- **GET** `/api/bets` - Retrieve all bets
- **POST** `/api/bets` - Create a new bet