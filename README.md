# Etsy Clone Backend

## 📌 Project Overview

This is a Node.js-based backend for a multi-vendor eCommerce platform inspired by Etsy. It provides APIs for authentication, product management, and vendor-based operations.

[Step by Step Guide to Build an ETSY Clone with NodeJs.](https://www.sevensquaretech.com/develop-etsy-clone-nodejs-with-code/)

## 🚀 Features

- User authentication with JWT
- Secure password hashing using bcrypt
- MongoDB database integration with Mongoose
- Input validation using Zod
- Cloud image upload via Cloudinary
- Environment-based configuration using dotenv
- Middleware support with Express and CORS
- Passport.js integration for authentication strategies

## 🛠️ Tech Stack

- Node.js
- Express.js
- MongoDB (Mongoose)
- Zod
- Passport.js
- Cloudinary

## 📂 Project Structure (Basic)

- index.js - Entry point of the application
- .env - Environment variables
- models/ - Mongoose schemas
- routes/ - API routes
- controllers/ - Business logic
- middleware/ - Custom middlewares

## ⚙️ Installation

1. Clone the repository:
   git clone https://github.com/SevenSquare-Tech/etsy-clone.git

2. Navigate to the project directory:
   cd etsy-clone

3. Install dependencies:
   npm install

## ▶️ Running the Project

Development mode:
npm run dev

Production mode:
npm start

## 🔐 Environment Variables

Create a .env file in the root directory and add the following:

PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret

## 📦 Scripts

- npm run dev → Run server in development mode using nodemon
- npm start → Run server in production mode

## 📌 Dependencies

- express
- mongoose
- bcrypt
- jsonwebtoken
- cors
- dotenv
- passport
- cloudinary
- zod
- nodemon
- cross-env
