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

## Key Features
--User Registration and Login: Allow users to create accounts and log in.
--Authentication using JWT Tokens: Secure user authentication using JSON Web Tokens.
--Story Searching and Pagination: Easily find stories with search functionality and pagination.
--CRUD Operations: Perform create, read, update, and delete operations on stories.
--Image Uploads: Upload user images and story images to the server.
--Liking Stories and Reading List: Users can like stories and add them to their reading list.
--Comments: Enable users to leave comments on stories.
--Skeleton Loading Effect: Improve user experience with skeleton loading for smoother transitions.
--Responsive Design: Ensure a seamless experience across various devices.
## Technologies Used
Frontend
React.js: JavaScript library for building user interfaces.
React Hooks: Manage and centralize application state.
react-router-dom: Handle routing in the application.
axios: Make API calls from the frontend.
CSS: Style the User Interface.
CK-Editor: Rich Text Editor for enhanced content creation.
uuid: Generate random IDs.
React icons: Library for adding icons to React apps.
Backend
Node.js: Runtime environment for building fast server applications using JavaScript.
Express.js: Server for handling and routing HTTP requests.
Mongoose: Model and map MongoDB data to JavaScript.
express-async-handler: Middleware for handling exceptions inside async express routes.
jsonwebtoken: Authentication using JSON Web Tokens.
Bcryptjs: Data encryption for security.
Nodemailer: Send emails from Node.js.
Dotenv: Load environment variables.
multer: Node.js middleware for uploading files.
slugify: Encode titles into a URL-friendly format.
cors: Provides Connect/Express middleware.
Database
MongoDB: NoSQL database providing a free cloud service to store MongoDB collections.
Screenshots


Author
[Your Name]
