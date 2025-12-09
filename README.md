# CRUD App (Express + MongoDB)

## Description
A basic CRUD API built with Express and MongoDB. Users can create, read, update, and delete items. Uses dotenv for environment variables and Morgan for logging.

## Folder Structure
models/       - Database schemas
controllers/  - CRUD logic
routes/       - API endpoints
server.js     - Entry point
.env          - Environment variables (not pushed)

## Environment Variables
Create a .env file:
PORT=5000
MONGODB_URI=mongodb://localhost:27017/cruddb

## Run Locally
1. npm install
2. Start MongoDB
3. npm run dev
4. API: http://localhost:5000/api/items

## Challenges
Connecting MongoDB and organizing models/controllers/routes caused initial errors. Async mistakes crashed the app until proper error handling was added.

## Assumptions
Used local MongoDB, no authentication, basic error handling to keep it functional.