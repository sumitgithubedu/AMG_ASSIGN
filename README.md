# Install project

- `npm install`
- Create a .env file in the root directory take reference some `.env.sample`
- Create DB
    - `CREATE DATABASE your_database_name;`
- Run migrations to create tables:
    - `npx knex migrate:latest`
- To start the server, run:
    - `npm start`

# API Endpoints

- Register: POST /api/auth/register
- Login: POST /api/auth/login
- Send Notification: POST /api/notifications/send
- Fetch Notifications: GET /api/notifications
- Mark Notification as Read: PUT /api/notifications/:id/read
