# AI Firebase Dashboard

A full-stack AI Dashboard integrated with Firebase 
for Authentication and Storage, connected to a 
custom Python AI Engine.

## Tech Stack
- **Language:** TypeScript
- **Frontend:** Vite + CSS
- **Backend:** Firebase (Auth & Storage)
- **AI Integration:** Google Gemini API
- **Database:** Firestore

## Features
- Firebase Authentication for secure user login
- Cloud Storage integration
- Real-time AI responses via Gemini API
- Firestore database with security rules
- Environment variable protection for API keys

## Getting Started
1. Clone the repository
2. Install dependencies: `npm install`
3. Set `GEMINI_API_KEY` in `.env.local`
4. Run: `npm run dev`

## Security
- Firebase config secured via environment variables
- Firestore security rules implemented
- API keys excluded from version control via `.gitignore`
