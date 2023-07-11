# MERNandGraphQL

This is a MERN (MongoDB, Express.js, React.js, Node.js) project that allows users to manage projects. It utilizes GraphQL for querying and mutating data, and includes features like user and project management, CRUD operations, and smooth data flow.

## Technologies Used

- MongoDB
- Mongoose
- GraphQL
- GraphiQL
- cors
- dotenv
- Apollo Client
- react-router
- Bootstrap

## Project Structure

The project follows a typical MERN project structure:

- `backend`: Contains the server-side code.
  - `models`: Includes Mongoose schemas and models for projects and users.
  - `schema`: Defines the GraphQL schema.
  - `index.js`: Sets up the Express.js server and connects to the MongoDB database.

- `frontend`: Contains the client-side code.
  - `components`: Includes React components for the home page, project information page, and other UI elements.
  - `pages`: Contains React components that represent different pages of the application.
  - `graphql`: Includes GraphQL queries and mutations defined using Apollo Client.
  - `App.js`: The main component that sets up the routes and Apollo Client.
--------------------------------------------
### MORE POINTS
*  Used the GraphQL API in GraphiQL at http://localhost:PORT/graphql to test queries and mutations for adding, deleting, and updating users/projects.
*  The application includes a home page that lists all the projects and a project information page that displays details about a specific project.
*  When adding or deleting a user/project, we made sure to use refetchQueries in Apollo Client to update the data and maintain a smooth flow.
*  The application uses a spinner component to indicate loading states, ensuring a better user experience.
---------------------------------------------
## Getting Started

1. Clone the repository and navigate to the project root directory.

2. Create a `.env` file in the `backend` directory and provide the necessary environment variables:

  PORT,MONGODB_URI and NODE_ENV

3. Install the dependencies for both the backend and frontend:

```bash
cd backend
npm install

cd ../frontend
npm install
```

4. Start the Development Server:
```bash
cd backend
npm start

cd ../frontend
npm start
```

5. Open your browser and navigate to http://localhost:3000 to access the application.
---------------------------------------------------------------------------------------------
Looking forward to add more stuff and update this website! 


