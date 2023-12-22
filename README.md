# MERN Blog

**MERN Blog** is a full-stack open-source blogging application built with MongoDB, Express, React, and Node.js (MERN stack).

## Configuration and Setup

To run this project locally, follow these steps:

1. Fork and clone the repository or download it as a zip file and unzip it on your machine.
2. Open the project in your preferred code editor.
3. Open a terminal and split it into two:

   - In the first terminal:

     ```bash
     $ cd Frontend
     $ npm install # Install frontend-side dependencies
     $ npm run start # Start the frontend
     ```

   - In the second terminal:

     ```bash
     $ cd Backend
     $ npm install # Install backend-side dependencies
     $ npm start # Start the backend
     ```

4. Set environment variables in `config.env` under `./config`. Create your MongoDB connection URL (`MONGO_URI`) and supply other required credentials as follows:

   **Config.env:**
   ```env
   NODE_ENV = development
   PORT = 5000
   URI = http://localhost:3000
   MONGO_URI = your_mongo_db_connection_url
   JWT_SECRET_KEY = your_jwt_secret_key
   JWT_EXPIRE = 60m
   RESET_PASSWORD_EXPIRE = 3600000

   # Nodemailer
   SMTP_HOST = smtp.gmail.com
   SMTP_PORT = 587
   EMAIL_USERNAME = example@gmail.com
   EMAIL_PASS = your_password

###### Key Features
-User registration and login
-Authentication using JWT Tokens
-Story searching and pagination
CRUD operations (Story create, read, update, and delete)
-Upload user images and story images to the server
-Liking stories and adding stories to the Reading list
-Commenting on the story
-Skeleton loading effect
-Responsive Design

###### Technologies Used
Frontend
React.js - JavaScript library for building user interfaces
React Hooks - For managing and centralizing application state
react-router-dom - Handling routing
axios - For making API calls
Css - For User Interface
CK-Editor - Rich Text Editor
uuid - For random ID generation
React icons - Library for adding icons to React apps

Backend
Node.js - Runtime environment for building fast server applications using JS
Express.js - Server for handling and routing HTTP requests
Mongoose - For modeling and mapping MongoDB data to JavaScript
express-async-handler - Middleware for handling exceptions inside async express routes
jsonwebtoken - For authentication
Bcryptjs - For data encryption
Nodemailer - Sending emails from Node.js
Dotenv - Loading environment variables
multer - Node.js middleware for uploading files
slugify - For encoding titles into a URL-friendly format
cors - Provides Connect/Express middleware

Database
MongoDB - NoSQL database providing a free cloud service to store MongoDB collections
