<div align="center">
  <h1>TalkSphere</h1>
  <p><em>Modern Chat & Video Calling Platform</em></p>
</div>

TalkSphere is a feature-rich communication platform designed to revolutionize how people connect and collaborate online. Whether you're a remote team looking for seamless collaboration, a group of friends staying in touch, or an educational institution needing a robust communication solution, TalkSphere has you covered.

Our platform combines powerful real-time chat capabilities with high-quality video calling functionality, creating an all-in-one communication hub. With features like instant messaging, group video calls, screen sharing, and customizable themes, TalkSphere adapts to both professional and personal use cases.

Key use cases include:

- 💼 **Remote Work**: Foster team collaboration with instant messaging and video meetings
- 🎓 **Virtual Education**: Enable interactive learning through screen sharing and group discussions
- 👥 **Social Networking**: Keep friends and family connected with personal chat rooms and video calls
- 🤝 **Professional Networking**: Build and maintain professional relationships through secure communication channels

Built using modern web technologies, TalkSphere prioritizes security, performance, and user experience to deliver a reliable and engaging communication platform.

## ⭐ Key Features

- **Real-time Communication**

  - Instant messaging with typing indicators
  - Message reactions and emoji support
  - Real-time message delivery status

- **Video Calling**

  - 1-on-1 and group video calls
  - Screen sharing capabilities
  - Video call recording
  - High-quality audio and video

- **User Experience**

  - 32 customizable UI themes
  - Responsive design for all devices
  - Intuitive user interface
  - Friend request system

- **Security**
  - JWT authentication
  - Protected routes
  - Secure API endpoints
  - Input validation

## 🛠️ Tech Stack

- **Frontend**

  - React.js with Vite
  - TailwindCSS for styling
  - TanStack Query for data fetching
  - Zustand for state management

- **Backend**
  - Express.js
  - MongoDB
  - Stream API for real-time features
  - JWT for authentication

## 🚀 Getting Started

### Prerequisites

- Node.js (v14 or higher)
- MongoDB instance
- Stream API credentials

### Environment Setup

1. **Backend Configuration** (`/backend/.env`)

   ```env
   PORT=5001
   MONGO_URI=your_mongo_uri
   STEAM_API_KEY=your_steam_api_key
   STEAM_API_SECRET=your_steam_api_secret
   JWT_SECRET_KEY=your_jwt_secret
   NODE_ENV=development
   ```

2. **Frontend Configuration** (`/frontend/.env`)
   ```env
   VITE_STREAM_API_KEY=your_stream_api_key
   ```

### Installation & Running

1. **Start the Backend**

   ```bash
   cd backend
   npm install
   npm run dev
   ```

2. **Launch the Frontend**
   ```bash
   cd frontend
   npm install
   npm run dev
   ```

## 🏗️ Project Structure

```
├── frontend/          # React frontend application
│   ├── src/
│   │   ├── components/  # Reusable UI components
│   │   ├── pages/      # Application pages
│   │   ├── hooks/      # Custom React hooks
│   │   └── store/      # Zustand store
│
└── backend/           # Express backend server
    ├── src/
    │   ├── controllers/  # Route controllers
    │   ├── models/      # Database models
    │   ├── routes/      # API routes
    │   └── middleware/  # Custom middleware
```

## 📝 License

This project is MIT licensed.

---
