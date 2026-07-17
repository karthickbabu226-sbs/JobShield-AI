# JobShield AI - System Architecture

## Workflow

User

↓

React Frontend

↓

FastAPI Backend

↓

Gemini AI

↓

Analysis Result

↓

React displays the result

---

## Components

### Frontend (React)
- User Interface
- Job Description Input
- Screenshot Upload
- Display Results

### Backend (FastAPI)
- Receives user request
- Sends prompt to Gemini AI
- Processes AI response
- Returns result to frontend

### AI Engine (Gemini)
- Detects scam indicators
- Calculates Trust Score
- Generates Risk Level
- Explains evidence
- Suggests questions for HR
- Gives safety advice
