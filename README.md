# MERN_Project
# Sociopedia

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

## Tech Stack

### Frontend
- React.js
- Modern UI libraries
- State management
- Responsive design principles

### Backend
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

# Install dependencies for backend
cd backend
npm install

# Install dependencies for frontend
cd ../frontend
npm install

# Create .env file in backend directory
touch .env

# Add the following variables to .env
MONGODB_URI=your_mongodb_uri
JWT_SECRET=your_jwt_secret
PORT=3001

# Start the backend server
cd backend
npm start

# Start the frontend development server
cd frontend
npm start
```

## Environment Variables

Create a `.env` file in the backend directory with the following variables:

```
MONGODB_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret_key
PORT=3001
```
