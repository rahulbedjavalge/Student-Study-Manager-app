# Student Study Manager Web App

A modern web application for students to manage their study materials, assignments, and academic tasks with AI assistance.

## Features
- Dashboard with study statistics
- Study material management
- Assignment tracking
- AI-powered assistance
- Modern, responsive UI

## Tech Stack
- Frontend: React.js with Vite
- Backend: Node.js + Express.js
- Database: MongoDB
- AI Integration: OpenAI GPT-4
- Styling: Tailwind CSS

## Prerequisites
- Node.js (v14 or higher)
- MongoDB (local installation or MongoDB Atlas account)
- OpenAI API key

## Setup Instructions

1. Clone the repository
2. Set up the backend:
   ```bash
   npm install
   # Create a .env file with:
   # PORT=5000
   # MONGODB_URI=your_mongodb_uri
   # OPENAI_API_KEY=your_openai_api_key
   node server.js
   ```

3. Set up the frontend:
   ```bash
   npm install
   npm run dev
   ```

4. Access the application:
   - Frontend: http://localhost:5173
   - Backend API: http://localhost:5000

## Environment Variables

### .env
```
PORT=5000
MONGODB_URI=mongodb://localhost:27017/student-manager
OPENAI_API_KEY=your_openai_api_key
```

## Development
- Backend API runs on port 5000
- Frontend development server runs on port 5173
- Make sure MongoDB is running locally or use MongoDB Atlas

## License
MIT
