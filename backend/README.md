# Web Calendar API Server

A backend REST API server for a Web Calendar application built with **Express.js** and **Firebase**. This server provides authentication and CRUD operations for calendar events.


## ✨ Features

- **User Authentication**: Sign up, sign in, and sign out with Firebase Authentication
- **Event CRUD Operations**: Create, read, update, and delete calendar events
- **User-specific Events**: Events are scoped to individual users via UID
- **CORS Support**: Cross-origin resource sharing enabled for frontend integration
- **Environment Configuration**: Secure configuration via environment variables

## 🛠 Tech Stack

- **Runtime**: Node.js
- **Framework**: Express.js
- **Database**: Firebase Firestore
- **Authentication**: Firebase Auth
- **Dev Tools**: Nodemon (hot reloading), Prettier (code formatting)
- **Environment**: dotenv for configuration management

## 📁 Project Structure

```
app/
├── src/
│   ├── config/
│   │   ├── firebase.js            # Firebase initialization & Firestore setup
│   │   └── firebaseService.json   # Firebase service account credentials (gitignored)
│   ├── controllers/
│   │   ├── auth-controller.js     # Authentication logic (signup, signin, signout)
│   │   └── crud-controller.js     # Event CRUD operations
│   └── routes/
│       └── manipulateRoutes.js    # API route definitions
├── .env                           # Environment variables
├── .gitignore                     # Git ignore rules
├── .prettierignore                # Prettier ignore patterns
├── index.js                       # Application entry point
├── package.json                   # Dependencies & scripts
└── README.md                      # Project documentation
```
**Important**: The `firebaseService.json` file contains sensitive credentials and should **never** be committed to version control.

## 📖 Usage

Once the server is running, you can interact with the API using tools like Postman, curl, or integrate it with a frontend application.



If you have run out of energy or time for your project, put a note at the top of the README saying that development has slowed down or stopped completely. Someone may choose to fork your project or volunteer to step in as a maintainer or owner, allowing your project to keep going. You can also make an explicit request for maintainers.
