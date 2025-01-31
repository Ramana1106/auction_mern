# Online Auction Platform

A real-time auction platform built with the MERN stack (MongoDB, Express, React, Node.js).

## Features

- User authentication (signup/login)
- Create and manage auctions
- Real-time bidding using Socket.IO
- Browse active auctions
- Place bids on items
- Search and filter auctions
- User dashboard

## Setup Instructions

1. Install dependencies:
   ```bash
   npm install
   cd frontend
   npm install
   ```

2. Create a .env file in the root directory with:
   ```
   MONGODB_URI=your_mongodb_connection_string
   JWT_SECRET=your_jwt_secret
   PORT=5000
   ```

3. Run the development server:
   ```bash
   npm run dev
   ```

The frontend will run on http://localhost:3000 and the backend on http://localhost:5000
