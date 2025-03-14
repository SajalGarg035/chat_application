# Anonymous Chat Application

## Overview

Anonymous Chat is a real-time messaging application that allows users to communicate with each other while having the option to remain anonymous. The application supports text messages with emoji support, file sharing, and real-time updates through WebSocket connections.

## Features

- **User Authentication**: Secure login and registration system
- **Anonymous Messaging**: Option to send messages anonymously
- **Real-time Communication**: Instant message delivery using Socket.IO
- **File Sharing**: Support for uploading and sharing various file types (images, documents, etc.)
- **Emoji Support**: Built-in emoji picker for expressive messaging
- **Responsive Design**: Works across desktop and mobile devices
- **User Status**: See when users are online or offline

## Technology Stack

### Frontend
- React.js
- Context API for state management
- Socket.IO Client for real-time communication
- TailwindCSS for styling
- Emoji Picker React for emoji selection

### Backend
- Node.js with Express.js
- MongoDB with Mongoose ORM
- Socket.IO for WebSocket connections
- JWT for authentication
- Cloudinary for file storage
- Multer for file upload handling

## Installation and Setup

### Prerequisites
- Node.js (v16 or higher)
- MongoDB database
- Cloudinary account for file storage
