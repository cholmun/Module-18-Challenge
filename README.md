```markdown
# Book Search and Save Application

## Description

This application allows users to search for books using the Google Books API and save their favorite books to their profile. Users can also view and remove saved books. The application is built with a React front-end and an Express/Node.js back-end, using Apollo Server for GraphQL API integration and MongoDB for data storage.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Technologies](#technologies)
- [Features](#features)
- [License](#license)
- [Contributing](#contributing)

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/Module-18-Challenge.git
   ```

2. Navigate to the project directory:

3. Install dependencies for both the client and server:
   ```bash
   npm install
   cd client
   npm install
   cd ..
   cd server
   npm install
   ```

4. Create a `.env` file in the `server` directory and add your environment variables:
   ```env
   JWT_SECRET_KEY=your_jwt_secret_key
   MONGODB_URI=your_mongodb_uri
   ```

5. Start the development server:
   ```bash
   cd server
   npm run dev
   ```

6. Start the client:
   ```bash
   cd client
   npm start
   ```

## Usage

1. Open your browser and navigate to `http://localhost:3000`.
2. Sign up for a new account or log in with an existing account.
3. Use the search bar to find books using the Google Books API.
4. Save books to your profile by clicking the "Save this Book!" button.
5. View your saved books on the "Saved Books" page.
6. Remove books from your saved list by clicking the "Delete this Book!" button.

## Technologies

- React
- Apollo Client
- GraphQL
- Express
- Node.js
- MongoDB
- Mongoose
- JWT (JSON Web Token)
- Bootstrap

## Features

- User authentication with JWT
- Search for books using the Google Books API
- Save books to user profile
- View and remove saved books
- Responsive design with Bootstrap

## License

This project is licensed under the MIT License.

## Contributing

Contributions are welcome! Please fork the repository and create a pull request with your changes.
