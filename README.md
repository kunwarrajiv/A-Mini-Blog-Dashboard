# A-Mini-Blog-Dashboard
Blogify – A Mini Blog Dashboard:


| Feature        | Details                                            |
| -------------- | -------------------------------------------------- |
| Backend        | Node.js + Apollo Server                            |
| Database       | In-memory array or MongoDB (optional for now)      |
| Entities       | `User`, `Post`, `Comment`                          |
| Operations     | Create/read posts, users, and comments via GraphQL |
| Frontend Ready | You can plug in React + Apollo Client later        |


🗂️ Project Structure

blogify-graphql/
│
├── src/
│   ├── schema/         # GraphQL type definitions
│   │   └── typeDefs.js
│   ├── resolvers/      # GraphQL resolvers
│   │   └── resolvers.js
│   ├── data/           # Mock data source (or real DB)
│   │   └── db.js
│   ├── index.js        # Apollo Server setup
│
├── package.json
├── .gitignore
└── README.md
