# UniBridge

UniBridge is an AI-powered student networking and academic resource platform that connects students across universities, enables collaborative learning, and gives smart access to shared academic resources — built to bridge the gap between students through meaningful peer connections and AI-driven academic support.

## Core Features
- **AI-Powered Student Matching** — connects students by shared courses, interests, and goals
- **Academic Resource Hub** — centralized library for notes, past papers, and project reports
- **Smart Study Groups** — subject-specific groups with scheduling and collaborative tools
- **Personalized Dashboard** — tailored feed of resources, sessions, and connections
- **AI Academic Assistant** — chatbot for on-demand academic support
- **Events & Opportunities Board** — curated hackathons, internships, and competitions
- **Secure Messaging** — encrypted direct and group chat
- **Reputation & Contribution System** — gamified points for quality contributions

## Tech Stack
**Frontend:** React.js, Tailwind CSS, Axios, Zustand  
**Backend:** Node.js, Express.js, Socket.IO, JWT, Bcrypt.js  
**Database:** MongoDB, Mongoose  
**AI & ML:** Google Gemini API (planned)

## Project Structure
unibridge/

├── client/     # React frontend

├── server/     # Node/Express backend

└── README.md

## Setup

### Frontend
```bash
cd client
npm install
npm run dev
```

### Backend
```bash
cd server
npm install
node src/index.js
```

Create a `.env` file inside `server/`:
MONGO_URI=mongodb://localhost:27017/unibridge

PORT=5000

## Status
🚧 Week 1 — project scaffolding and environment setup complete.
