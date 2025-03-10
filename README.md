# Recov Backend

Recov is a lost and found tracking web application built with the MERN stack. This repository contains the backend services responsible for handling authentication, report management, and database operations.

## Tech Stack

- **Node.js** with **Express.js** - Backend framework
- **MongoDB** - NoSQL database for storing reports and user data
- **Mongoose** - ODM for MongoDB
- **JWT (JSON Web Tokens)** - Authentication
- **Cloudinary** - Media storage for images

##  Features

- User authentication (JWT-based login/signup)
- Report lost and found items
- View and manage reported items
- Image upload and storage using Cloudinary
- Email notifications for updates on reported items
- Admin dashboard for managing reports

##  Setup Instructions

### Prerequisites
Make sure you have the following installed:
- [Node.js](https://nodejs.org/)

### Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/recov-backend.git
   cd recov-backend
   ```

2. Install dependencies:
   ```sh
   npm install
   ```

3. Create a `.env` file in the root directory and add the following environment variables:
   ```env
   MONGO_URI=your_mongodb_connection_string
   JWT_SECRET=your_jwt_secret
   CLOUDINARY_CLOUD_NAME=your_cloudinary_name
   CLOUDINARY_API_KEY=your_cloudinary_api_key
   CLOUDINARY_API_SECRET=your_cloudinary_api_secret
   ```

4. Start the server:
   ```sh
   npm start
   ```



