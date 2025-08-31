Note-taking App
A full-stack, production-ready note-taking application with React 18, Vite, TailwindCSS frontend and Express.js, TypeScript, MongoDB backend. Features JWT & Google OAuth authentication, monorepo structure, and robust testing.

Features
Modern React 18 + Vite + TailwindCSS frontend
Express.js + TypeScript backend with MongoDB
JWT & Google OAuth authentication
Modular monorepo with shared types
Comprehensive error handling, validation, and accessibility
Production build scripts and cloud deployment ready
Full test coverage (Jest, React Testing Library)
Getting Started
Prerequisites
Node.js v20+
npm v10+
MongoDB (local or cloud)
Environment Variables
Frontend (client/.env)
Backend (backend/.env)
Setup & Development
Production Build & Deployment
Deployment
Deploy backend to platforms like Heroku, Render, Railway, or AWS
Deploy frontend to Vercel, Netlify, or static hosting
Set environment variables in your cloud provider
API Documentation
Auth Endpoints
POST /api/auth/signup — Signup user
POST /api/auth/login — Login user
POST /api/auth/verify-otp — Verify OTP
GET /api/auth/google — Google OAuth
Notes Endpoints
GET /api/notes — List notes
POST /api/notes — Create note
PUT /api/notes/:id — Update note
DELETE /api/notes/:id — Delete note
Example: Create Note
Testing
Backend
Frontend
Development Workflow
Use feature branches for new features
Write tests for all new code
Use Prettier and ESLint for code style
Commit with conventional messages
Troubleshooting
Check .env files for correct values
Ensure MongoDB is running
Use npm run dev for local development
See logs for error details
Contributing
Fork the repo and create a feature branch
Add/modify code with clear comments and JSDoc
Write or update tests
Open a pull request with a clear description
License
MIT

