
# MERN Stack Coding Challenge - V2

## Description
This project is a solution to the MERN Stack Coding Challenge. The goal is to build a web application that leverages the full MERN stack (MongoDB, Express, React, and Node.js). The application adheres to the requirements specified in the challenge document. This includes user authentication, data management, and providing a responsive interface for interacting with the data.

## Features
- **User Authentication**: Secure authentication using JWT (JSON Web Tokens) to protect routes and manage sessions.
- **CRUD Operations**: Full Create, Read, Update, Delete functionality for managing resources (e.g., posts, comments).
- **Responsive Frontend**: Built with React to provide a dynamic, responsive user experience across various devices.
- **State Management**: Utilizes Redux (if applicable) to manage application state across the frontend.
- **Error Handling & Validation**: Proper error handling on both frontend and backend, with validation for user inputs.

## Technologies Used
- **Frontend**: React, React Router, Redux (if applicable)
- **Backend**: Node.js, Express.js
- **Database**: MongoDB, Mongoose
- **Additional Tools**: Axios (for API requests), JWT (for authentication), Bcrypt (for password hashing), dotenv (for managing environment variables)

## Setup Instructions
Follow these steps to set up the project locally:

1. Clone the repository:
    ```bash
    git clone [repository-url]
    ```

2. Navigate to the project directory:
    ```bash
    cd [project-directory]
    ```

3. Install dependencies for both the backend and frontend:
    ```bash
    cd backend
    npm install

    cd ../frontend
    npm install
    ```

4. Create a `.env` file in the backend directory and add the following environment variables:
    ```
    PORT=5000
    MONGO_URI=your-mongodb-uri
    JWT_SECRET=your-jwt-secret
    ```

5. Start the development servers:
    ```bash
    cd backend
    npm run dev

    cd ../frontend
    npm start
    ```

6. Open your browser and navigate to `http://localhost:3000` to access the application.

## Usage
1. **Register an Account**: Navigate to the registration page and fill out the form to create an account.
2. **Login**: Once registered, log in using your credentials to access the protected routes.
3. **Perform CRUD Operations**: After logging in, you can create, view, edit, and delete resources (e.g., posts or comments).
4. **Logout**: Use the logout functionality to safely exit the application.

## Contributing
Contributions are welcome! Follow these steps:
1. Fork the repository.
2. Create a new branch (`git checkout -b feature/your-feature-name`).
3. Commit your changes (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature/your-feature-name`).
5. Open a pull request.

## License
This project is licensed under the [MIT License](LICENSE).
