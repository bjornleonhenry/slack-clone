# Slack Clone - Team Communication Platform

A comprehensive team communication platform with real-time messaging, video calls, file sharing, and advanced collaboration features.

## Features

- 💬 Real-time messaging with threads and reactions
- 📂 File sharing and document collaboration
- 📊 Polls and surveys with anonymous voting
- 🔐 Secure authentication and user management
- 📨 Direct messages and private channels
- 📹 Video calls with screen sharing
- 🎯 Advanced team collaboration tools
- 🚀 Scalable architecture for growing teams

## Tech Stack

- **Node.js + Express** - Backend API
- **React + Vite** - Frontend framework
- **MongoDB** - Database
- **Socket.io** - Real-time communication
- **WebRTC** - Video calling capabilities
- **File upload services** - Document management

## Getting Started

### Prerequisites

- Node.js (v16 or higher)
- MongoDB database
- npm or yarn or pnpm

### Installation

1. **Backend Setup:**
```bash
cd backend
npm install
# Set up your MongoDB connection and environment variables
npm run dev
```

2. **Frontend Setup:**
```bash
cd frontend
npm install
npm run dev
```

3. Access the application:
   - Frontend: `http://localhost:5173`
   - Backend API: `http://localhost:5001`

## Environment Variables

### Backend (.env)
```env
PORT=5001
MONGO_URI=your_mongodb_connection_string
NODE_ENV=development
# Add other required API keys for services
CLIENT_URL=http://localhost:5173
```

### Frontend (.env)
```env
VITE_API_BASE_URL=http://localhost:5001/api
# Add other required API keys
```

## Deployment

- **Frontend**: Deploy to Vercel, Netlify, or any modern hosting platform
- **Backend**: Deploy to VPS, Railway, Render, or similar Node.js hosting
- **Database**: MongoDB Atlas or self-hosted MongoDB instance
