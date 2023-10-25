# WEC-Recruitments-LeetCode-Clone
FireCode is the name of my LeetCode clone, and can be used as a platform for developers to practice coding problems and improve their skills. This project was created as a full-stack project using Express, MongoDB, Mongoose, TypeScript,TypeScript React (TSX), CSS3, and Tailwind CSS.

# Demo

You can see the live demo of website at https://fire-code.vercel.app.
Video - https://drive.google.com/file/d/1-d5uUOTuIyk4YiOlJ5rYNs_h_V6ylLfS/view?usp=sharing

# Installation

### Clone the repository and install server and client dependencies:

```bash
git clone https://github.com/ManiGhazaee/FireCode.git
cd FireCode/server
npm install
cd ../client
npm install
```

### Start the client in the `client` directory:

```bash
npm start
```

### Configure the MongoDB Database and JWT Secret:

Before starting the server, make sure to configure the following environment variables in the `server/.env` file:

-   `MONGODB_URI`: Set this variable to your MongoDB connection string.
-   `ACCESS_TOKEN_SECRET`: Set this variable to a secret key for JWT access tokens.

### Configure the API URL:

To use your own API, open the `client/src/App.tsx` file and find the `API_URL` constant. Update its value to match the URL of your deployed server (`http://localhost:80`).

### Start the server in the `server` directory:

```bash
npm start
```

# Features

-   User authentication: Users can create an account, log in, and log out, delete account.
-   Coding problems: Users can browse coding problems, submit solutions.
-   User profile: Users can view their profile, including their solved problems and submissions.

# Technologies Used

-   Express: A web framework for Node.js
-   MongoDB: A NoSQL database
-   Mongoose: A MongoDB object modeling tool
-   TypeScript: A typed superset of JavaScript
-   TypeScript React: A JavaScript library for building user interfaces with TypeScript
-   Tailwind CSS: A utility-first CSS framework
-   CSS: A stylesheet language used to describe the presentation of a document written in HTML or XML



