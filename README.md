# FitFlow Redesign

FitFlow is a fitness tracking application redesigned using
Human Computer Interaction principles.

## Features

- AI personalised workouts
- Nutrition tracking
- Progress tracking
- Social challenges
- Fitness achievements

## Technology Stack

- Frontend: Flutter
- Backend: NestJS
- AI Service: FastAPI
- Database: PostgreSQL
- Authentication: Firebase Authentication
- Cache: Redis
- Real-time: WebSockets

## Repository Structure

- `frontend/` – Flutter application
- `backend/` – NestJS API
- `ai-service/` – FastAPI AI service
- `docs/` – Project documentation
- `screenshots/` – Prototype and project screenshots

## Architecture

Flutter communicates with the NestJS backend. NestJS manages
the main application data through PostgreSQL and uses Redis
for caching and real-time support. AI requests are sent from
NestJS to the FastAPI AI service, which communicates with
AI/ML models.

## Documentation

See the `docs/` folder for:

- Technology comparison
- Weighted decision matrix
- System architecture
- Architecture Decision Record
