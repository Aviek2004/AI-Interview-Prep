# InterviewAI

An AI-powered interview preparation platform that analyzes your resume and target job description to generate a personalized interview strategy.

InterviewAI helps candidates prepare for technical and behavioral interviews by combining resume analysis, job-description analysis, AI-generated questions, skill-gap identification, and personalized preparation plans.

## Features

- Resume upload and PDF parsing
- Job description analysis
- Personalized interview strategy
- AI-generated technical questions
- AI-generated behavioral questions
- Skill-gap analysis
- Personalized preparation plan
- AI-powered resume optimization
- Downloadable AI-generated resume PDF
- User authentication
- Interview report history
- MongoDB-based data persistence
- Responsive React frontend

## Tech Stack

### Frontend

- React
- Vite
- Axios
- SCSS

### Backend

- Node.js
- Express.js
- MongoDB
- Mongoose
- JWT Authentication
- Multer
- PDF parsing

### AI

- Google Gemini API

### Other

- Puppeteer
- Git & GitHub

---

# How It Works

```text
                    ┌─────────────────────┐
                    │     User uploads    │
                    │ Resume + Job Role   │
                    └──────────┬──────────┘
                               │
                               ▼
                    ┌─────────────────────┐
                    │   React Frontend    │
                    └──────────┬──────────┘
                               │
                               ▼
                    ┌─────────────────────┐
                    │  Express Backend    │
                    └──────────┬──────────┘
                               │
                    ┌──────────┴──────────┐
                    ▼                     ▼
             ┌─────────────┐       ┌─────────────┐
             │ Resume      │       │ Job         │
             │ Parser      │       │ Description │
             └──────┬──────┘       └──────┬──────┘
                    │                     │
                    └──────────┬──────────┘
                               ▼
                    ┌─────────────────────┐
                    │    Gemini AI        │
                    │     Analysis        │
                    └──────────┬──────────┘
                               ▼
                    ┌─────────────────────┐
                    │ Interview Strategy  │
                    │ Technical Questions │
                    │ Behavioral Questions│
                    │ Skill Gaps          │
                    │ Preparation Plan    │
                    └──────────┬──────────┘
                               ▼
                    ┌─────────────────────┐
                    │      MongoDB        │
                    │   Save Interview    │
                    │      Reports        │
                    └─────────────────────┘
