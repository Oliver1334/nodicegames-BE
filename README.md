# No Dice Games - Backend

No Dice Games is a RESTful API built for a board game review aggregation platform. This backend service provides endpoints for managing reviews, comments, categories, and user interactions.

**[View the live API here](https://nc-games-2kfx.onrender.com/api)**

This project was developed as part of the **Northcoders Full-Stack Software Developer Bootcamp**.

## Features

- View all reviews with filtering, sorting, and ordering capabilities
- Retrieve individual reviews by ID
- Filter, sort and order reviews via query parameters
- View, post and delete comments on reviews
- Upvote or downvote reviews
- View all users
- Browse reviews by category

## Tech Stack

- **Node.js**
- **Express.js**
- **PostgreSQL**
- **Jest**
- **Supertest**

## Frontend Repository

The corresponding frontend application can be found here: [No Dice Games Frontend](https://github.com/Oliver1334/nodicegames-FE.git)

**[View the live frontend deployment](https://nodicegames.netlify.app/)**

## Installation & Setup

### Prerequisites

- Node.js (minimum version 6.0.0)
- PostgreSQL (minimum version 8.7.3)

### Steps

1. Clone this repository:
```bash
git clone https://github.com/Oliver1334/nodicegames-BE.git
```

2. Navigate to the project directory:
```bash
cd nodicegames-BE
```

3. Install dependencies:
```bash
npm install
```

4. Set up environment variables:

Create a `.env.development` file in the root directory:
```
PGDATABASE=nc_games
```

Create a `.env.test` file in the root directory:
```
PGDATABASE=nc_games_test
```

Ensure both files are added to `.gitignore`

5. Set up the database:
```bash
npm run setup-dbs
npm run seed
```

6. Start the development server:
```bash
npm start
```

The server will run on `localhost:9090`

## API Documentation

A summary of all available endpoints can be viewed at the [/api](https://nc-games-2kfx.onrender.com/api) endpoint.

When running locally, navigate to `localhost:9090/api` for a complete list of endpoints, request formats, and example responses.

## Testing

This application has been fully tested using Jest and Supertest. To run the test suite:

```bash
npm test
```





