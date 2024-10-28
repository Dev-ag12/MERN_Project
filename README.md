# MERN_Project

## Overview
Sociopedia is a modern social media platform built using the MERN (MongoDB, Express.js, React.js, Node.js) stack. It provides users with a familiar social networking experience while incorporating essential features for user engagement and interaction.

## Features

### Authentication & Security
- Secure user registration and login system
- Protected routes and user sessions
- Password encryption

### User Interface
- Clean and intuitive design
- Dark/Light mode toggle for better user experience
- Responsive layout for all devices
- Modern UI components

### Core Functionality
- User Profile Management
  - Profile picture upload
  - Personal information updates
  - Location and occupation details
  - Profile view counter
  - Post impression tracking

### Social Features
- Friend management system
- Post creation and sharing
  - Multiple media types support (Image, Clip, Audio, Attachments)
  - Post engagement metrics
- Social profile linking (Twitter, LinkedIn)

## Project Structure
```
sociopedia/
├── client/                 # React frontend
│   ├── public/
│   ├── src/
│   └── package.json
│
└── server/                 # Node.js backend
    ├── controllers/
    ├── models/
    ├── routes/
    └── package.json
```

## Tech Stack

### Frontend (client/)
- React.js
- Modern UI libraries
- State management
- Responsive design principles

### Backend (server/)
- Node.js
- Express.js
- MongoDB
- RESTful API architecture

### Authentication
- JWT (JSON Web Tokens)
- Secure password hashing
- Session management

## Installation

```bash
# Clone the repository
git clone https://github.com/yourusername/sociopedia.git

# Install server dependencies
cd server
npm install

# Install client dependencies
cd ../client
npm install

# Create .env file in server directory
touch .env

# Add the following variables to .env
MONGODB_URI=your_mongodb_uri
JWT_SECRET=your_jwt_secret
PORT=3001

# Start the server
cd server
nodemon index.js

# Start the client development server
cd client
npm start
```

## Environment Variables

Create a `.env` file in the server directory with the following variables:

```
MONGODB_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret_key
PORT=3001
```
