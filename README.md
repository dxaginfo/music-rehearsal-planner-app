# Music Rehearsal Planner App

Automatically schedules band rehearsals, sends reminders, tracks attendance, and suggests optimal rehearsal times for musicians and groups.

## Features
- Manage rehearsal space and band scheduling
- Conflict-free calendar and notifications
- RSVP and attendance tracking
- Equipment and resource management
- Admin and musician portal
- Google Calendar integration
- Mobile responsive interface

## Technology
- Front-end: ReactJS
- Back-end: Node.js/Express
- Database: PostgreSQL
- Notifications: Twilio/SendGrid
- Deployment: Docker, GitHub Actions, Vercel

## Setup
1. Clone the repository
2. Set up .env with database and 3rd-party API keys
3. `npm install` in both /client and /server directories
4. Run migrations: `npm run migrate` in /server
5. Start backend and frontend development servers

## Deployment
- Edit Dockerfile and deployment files for production environment
- Push to main to trigger GitHub Actions/Vercel deploy

## Security
- Make sure environment credentials are kept safe; sensitive data never committed

## License
MIT
