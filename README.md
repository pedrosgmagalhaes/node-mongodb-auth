# Node.js Authentication with MongoDB

This is a simple Node.js authentication system using MongoDB, Express, and JSON Web Tokens. The application is designed with clean code practices and the MVC pattern.

## Features

- User signup and login
- Secure password hashing with bcryptjs
- JSON Web Token (JWT) authentication
- Express and Mongoose for easy API development

## Prerequisites

- Node.js v14.x or higher
- MongoDB v4.x or higher

## Getting Started

1. Clone the repository:
´´git clone https://github.com/yourusername/node-mongodb-auth.git´´
´´cd node-mongodb-auth´´

2. Install dependencies:
´´yarn install´´


3. Create a `.env` file in the root of the project directory and add the following environment variables:
´´JWT_SECRET=your_jwt_secret´´
´´JWT_EXPIRES_IN=1d´´

4. Start the development server:
´´yarn dev´´

5. Access the API endpoints with a tool like Postman or curl:

- Signup: `POST http://localhost:3000/auth/signup`
- Login: `POST http://localhost:3000/auth/login`

## Contributing

Please feel free to open issues or submit pull requests to contribute to this project.

## License

This project is licensed under the MIT License.

## Video Tutorial
Portuguese: https://youtu.be/acMVKrqn7nI