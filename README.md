# Real Estate Application

This is a real estate application built with React and Node.js. It allows users to browse, search, and manage real estate listings.

## Features

- User authentication and authorization using Auth0
- Browse and search real estate listings
- View detailed information about each property
- Book visits to properties
- Save favorite properties
- Property owners can manage their listings
- Responsive and user-friendly UI

## Technologies Used

- Frontend:
  - React
  - Vite
  - Mantine UI library
  - React Router
  - React Query
  - Leaflet for maps
  - Swiper for image carousels
  - Framer Motion for animations
  - Axios for API requests

- Backend:
  - Node.js
  - Express
  - Prisma ORM
  - MongoDB database
  - JWT authentication with Auth0

## Getting Started

### Prerequisites

- Node.js (v14 or higher)
- MongoDB database
- Auth0 account for authentication

### Installation

1. Clone the repository:

```git clone https://github.com/your-username/real-estate.git```

2. Install dependencies for the frontend and backend:

```bash
cd real-estate/client
yarn install

cd ../server
yarn install
```

3. Set up environment variables:
- Create a `.env` file in the `server` directory and provide the necessary environment variables (e.g., `DATABASE_URL`, `AUTH0_DOMAIN`, `AUTH0_CLIENT_ID`, etc.).

4. Set up the database:
- Ensure you have a running MongoDB instance.
- Update the `DATABASE_URL` in the `.env` file with your MongoDB connection URL.
- Run the database migrations:

```bash
  cd server
  npx prisma migrate dev
```

5. Start the development servers:
- For the frontend:
  
```bash
  cd client
  yarn dev
```

- For the backend:

```bash
  cd server
  yarn start
```

1. Open your browser and visit `http://localhost:5173` to access the application.

## Deployment

The application can be deployed to various hosting platforms. Here are a few options:

- Frontend:
  - Netlify
  - Vercel
  - AWS S3

- Backend:
  - Heroku
  - AWS EC2
  - DigitalOcean

Make sure to set up the necessary environment variables and configure the database connection in the production environment.