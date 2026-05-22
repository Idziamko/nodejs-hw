# nodejs-hw

Homework: Express app for notes collection

## What was done

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