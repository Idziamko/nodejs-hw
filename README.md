# nodejs-hw

## Homework 1: Express app for notes collection

**What was done**
- Initialized project with npm init
- Installed express, cors, pino-http, dotenv
- Installed nodemon and eslint as dev dependencies
- Created src/server.js with express server
- PORT is loaded from .env using dotenv
- Added cors middleware
- Added express.json() middleware
- Set up pino-http logger
- Implemented GET /notes route
- Implemented GET /notes/:noteId route
- Implemented GET /test-error route
- Added 404 middleware for undefined routes
- Added 500 error handling middleware
- Deployed to render.com

## Homework 2: MongoDB connection

**What was added (Update)**
- Connected to MongoDB using Mongoose
- Moved connection string to .env (MONGO_URL)
- Created Mongoose schema and model for Notes
- Added POST /notes route to create notes
- Added PATCH /notes/:noteId route to update notes
- Added DELETE /notes/:noteId route to delete notes
- Removed the old /test-error route
