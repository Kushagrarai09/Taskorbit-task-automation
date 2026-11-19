# TaskOrbit

A full-stack recurring task automation platform with role-based dashboards, employee evidence submission, manager acknowledgement, SLA monitoring, leadership escalation, notifications and audit logs.

## Stack
- React + Vite
- Node.js + Express
- MongoDB + Mongoose
- JWT authentication and bcrypt
- node-cron scheduler
- Docker Compose

## Quick start
1. Start MongoDB: `docker compose up -d`
2. Copy `server/.env.example` to `server/.env` and configure `JWT_SECRET`.
3. From the project root, run `npm install`.
4. Seed demo data: `npm run seed`.
5. Start the app: `npm run dev`.
6. Open the frontend at `http://localhost:5173`; the API is at `http://localhost:4000`.

Keep `EMAIL_MODE=console` for local development. Configure SMTP only when email delivery is needed. Change all demo passwords and secrets before any deployment.

See [TEST_AND_DEMO.md](TEST_AND_DEMO.md) for demo accounts and [docs/API.md](docs/API.md) for API notes.
