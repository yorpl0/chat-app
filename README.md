# Full Stack Realtime Chat Application

## Overview
This is a full stack realtime chat application built with the following technologies:

- MERN stack (MongoDB, Express.js, React.js, Node.js)
- Socket.io for real-time communication
- Tailwind CSS with DaisyUI for responsive UI design
- JWT-based authentication and authorization
- Zustand for global state management

## Features

- Real-time messaging with Socket.io
- User authentication and authorization using JWT
- Online user status indicators
- Global state management with Zustand
- Comprehensive error handling on both server and client sides
- Production-ready deployment configuration


# Team Members
1) Karan Malik (Team Leader)
2) Avneesh Kumar
3) Gokul Raj M
4) Yash Mohan
5) Sanmit Sarkar
6) Nishtha Garg


## Environment Variables

Create a `.env` file in the root directory with the following content:

```env
MONGODB_URI=your_mongodb_connection_string
PORT=5001
JWT_SECRET=your_jwt_secret

CLOUDINARY_CLOUD_NAME=your_cloudinary_cloud_name
CLOUDINARY_API_KEY=your_cloudinary_api_key
CLOUDINARY_API_SECRET=your_cloudinary_api_secret

NODE_ENV=development
```

## Build the Application

```bash
npm run build
```

## Start the Application

```bash
npm start
```
