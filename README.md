# MERN Stack Project: Build and Deploy a Twitter Clone From Scratch | JWT, Socket.io

![Demo App](https://i.ibb.co/f8y9vGS/Group-82.png)

[Video Tutorial on Youtube](https://youtu.be/4GUVz2psWUg)

Some Features:

-   ⚛️ Tech Stack: React.js, MongoDB, Node.js, Express, Tailwind.css
-   🔐 Authentication with JSONWEBTOKENS (JWT)
-   🔥 React Query for Data Fetching, Caching etc.
-   👥 Suggested Users to Follow
-   ✍️ Creating Posts
-   🗑️ Deleting Posts
-   💬 Commenting on Posts
-   ❤️ Liking Posts
-   🔒 Delete Posts (if you are the owner)
-   📝 Edit Profile Info
-   🖼️ Edit Cover Image and Profile Image
-   📷 Image Uploads using Cloudinary
-   🔔 Send Notifications
-   🌐 Deployment
-   ⏳ And much more!

### Setup .env file

```js
MONGO_URI=...
PORT=...
JWT_SECRET=...
NODE_ENV=...
CLOUDINARY_CLOUD_NAME=...
CLOUDINARY_API_KEY=...
CLOUDINARY_API_SECRET=...
```

### Build the app

```shell
npm run build
```

### Start the app

Twitter Clone (MERN Stack)
Table of Contents
Introduction
Features
Tech Stack
Installation
Environment Variables
Running the Application
API Endpoints
Frontend Structure
Backend Structure
Testing
Contributing
License
Contact
Introduction
This project is a Twitter clone built using the MERN stack. It replicates core functionalities of Twitter such as tweeting, following/unfollowing users, liking tweets, and more. The purpose of this project is to demonstrate the use of MongoDB, Express.js, React, and Node.js in building a full-stack web application.

Features
User Authentication: Sign up, login, and logout functionalities.
Profile Management: Update profile information including bio, profile picture, etc.
Tweeting: Create, read, update, and delete tweets.
Follow System: Follow and unfollow users.
Like Tweets: Like and unlike tweets.
Search: Search for users and tweets.
Real-Time Updates: Real-time updates using WebSockets.
Responsive Design: Optimized for mobile and desktop viewing.
Tech Stack
Frontend:
React.js: JavaScript library for building user interfaces.
Redux: State management for React applications.
Tailwind CSS: Utility-first CSS framework for styling.
Backend:
Node.js: JavaScript runtime environment.
Express.js: Web framework for Node.js.
MongoDB: NoSQL database for storing user and tweet data.
Mongoose: ODM for MongoDB to manage database connections and schemas.
JWT: JSON Web Token for authentication.
Socket.io: Real-time communication between client and server.
Installation
To get started with the project, follow these steps:

Prerequisites
Node.js (v14 or higher)
npm or yarn
MongoDB installed locally or access to a MongoDB cloud instance

API Endpoints
Here are some of the key API endpoints available in the backend:

Auth
POST /api/auth/register: Register a new user.
POST /api/auth/login: Login a user and receive a token.
Users
GET /api/users/:id: Get a user's profile by ID.
PUT /api/users/:id: Update a user's profile.
Tweets
POST /api/tweets: Create a new tweet.
GET /api/tweets: Get all tweets.
GET /api/tweets/:id: Get a specific tweet by ID.
DELETE /api/tweets/:id: Delete a tweet.
Follow
PUT /api/users/:id/follow: Follow a user.
PUT /api/users/:id/unfollow: Unfollow a user.
Frontend Structure
The frontend is organized into the following structure:

bash
Copy code
frontend/
│
├── public/             # Static files
├── src/
│   ├── assets/         # Images, icons, etc.
│   ├── components/     # Reusable components
│   ├── pages/          # Page components
│   ├── redux/          # Redux slices and store
│   ├── services/       # API service functions
│   ├── styles/         # Global and component-specific styles
│   ├── utils/          # Utility functions
│   └── App.js          # Main App component
│
└── .env                # Environment variables
Backend Structure
The backend is organized into the following structure:

bash
Copy code
backend/
│
├── config/             # Configuration files (e.g., database)
├── controllers/        # Controller functions
├── models/             # Mongoose schemas and models
├── routes/             # Express routes
├── middleware/         # Custom middleware functions
├── utils/              # Utility functions
├── server.js           # Entry point of the server
│
└── .env                # Environment variables

```shell
npm start
```
#   M C T 
 
 
