# iNotebook

A full-stack note-taking application built with React and Node.js. Create, edit, and manage your notes with ease.

## Features

-  Create, read, update, and delete notes
-  User authentication and authorization
-  Organized note management
-  Real-time updates
-  Responsive design

## Tech Stack

### Frontend
- React.js
- Context API for state management
- CSS for styling

### Backend
- Node.js
- Express.js
- MongoDB for database
- JWT for authentication

## Project Structure

`
iNotebook/
 src/                    # React frontend code
    components/         # Reusable React components
    context/            # Context API setup
    App.js
 backend/                # Node.js backend
    routes/             # API routes
    models/             # Database models
    middleware/         # Custom middleware
    db.js               # Database connection
    index.js            # Server entry point
 package.json
`

## Getting Started

### Prerequisites
- Node.js (v14 or higher)
- MongoDB

### Installation

1. Install frontend dependencies:
`bash
npm install --legacy-peer-deps
`

2. Install backend dependencies:
`bash
cd backend
npm install
`

### Running the Application

1. Start the backend server:
`bash
cd backend
npm start
`

2. Start the frontend development server (from root):
`bash
npm start
`

Open [http://localhost:3000](http://localhost:3000) to view the app in your browser.

## Available Scripts

### Frontend
- 
npm start - Start development server
- 
npm run build - Build for production
- 
npm test - Run tests

### Backend
- 
npm start - Start the Node.js server
- 
npm test - Run backend tests

## API Endpoints

- POST /api/auth/register - Register a new user
- POST /api/auth/login - Login user
- GET /api/notes - Get all notes
- POST /api/notes - Create a new note
- PUT /api/notes/:id - Update a note
- DELETE /api/notes/:id - Delete a note

## Environment Variables

Create a .env file in the backend directory:
`
PORT=5000
MONGODB_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret_key
`

## Contributing

Feel free to fork this project and submit pull requests.

## License

This project is open source and available under the MIT License.
