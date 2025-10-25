# AI Innovation Summit Fall 2025 Backend

This repository is based on the Capstone II Starting Point repository supplied for the Summer 2025 TTPR Bootcamp.

## Getting Started

This project uses Express.js to serve up an API server, and Sequelize to connect to a PostgreSQL database. It uses JWTs for authentication with username and password.

You will also need to create the database: by default it is called `innovation-summit`, but you are welcome to rename it in `database/db.js`

After that, you can get started with these commands

```
npm install # 📦 To install the packages
npm run seed # 🌱 To seed the database
npm run start-dev # 🚀 To start the server in development mode
```

This project runs in the Node.js runtime environment. We're not using Webpack here, but we are using a tool called nodemon, which re-runs our app whenever we save a file. You should see a message in the terminal telling you that the server is running on port 8080.

When an error occurs on the backend (Express), you'll see a message in the terminal. When an error occurs on the frontend (React), you'll see that error in the browser.

## Deployment

This project has a vercel.json file, which will make it easier to deploy this project to Vercel. Neon can be used to host your database and can done directly through Vercel. Just like for the Frontend, if you are using Web Sockets, Render is a better option, though you can still use Neon for the database.
