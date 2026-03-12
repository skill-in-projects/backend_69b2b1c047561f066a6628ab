# SafePath - Backend API

## Application Database

**Application DB Connection String:** `postgresql://db_appdb_69b2b1c047561f066a6628ab_user:22%24YqV8SP1l%2AtaP%263Z%2AZRj%2AFBBzyh0HH@ep-crimson-king-adgztkil.c-2.us-east-1.aws.neon.tech:5432/AppDB_69b2b1c047561f066a6628ab?sslmode=require`

**Swagger API Tester URL:** /swagger

## Google APIs (Gemini, Maps, Speech-to-Text)

The backend can use a Google API key provided via the **GOOGLE_API_KEY** environment variable (set on Railway). Use it for Gemini LLM, Maps, and Speech-to-Text. Check **GET /api/google/status** and **GET /api/google/health** to verify the key is set and reachable.

## Recommended Tools

**Recommended SQL Editor tool (Free):** [pgAdmin](https://www.pgadmin.org/download/)

## Deployment

This backend is configured for Railway deployment using nixpacks.toml.
