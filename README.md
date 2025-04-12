Textura: Text-to-Image Generator
 
Textura is a user-friendly and powerful text-to-image generator that allows users to transform their ideas into stunning visuals. By integrating the Clipdrop Web API and offering flexible credit plans, it is ideal for both casual creators and professionals.


Features

 Text-to-Image Generation:
 Transform any text input into visually compelling graphics using Clipdrop's SaaS platform.

User Authentication:
 Secure signup and login system with JWT-based authentication.

Credit System:

    Free 10 credits for new users.
    Flexible paid plans: Basic, Advanced, and Business.

Secure Payment Gateway:
 Integrated with Razorpay for smooth and secure credit purchases.

Database:
 MongoDB is used for storing user data, credit information, and more.

Steps to Use the Project

Prerequisites
 Before running the project, make sure you have the following installed:

   Node.js
   MongoDB
   Razorpay Account
   Clipdrop API Access
   Setup Instructions

Clone the Repository

    git clone git@github.com:devashish16/textura.git
   cd textura
   
Install Dependencies
npm install

Create Environment Variables
 Set up a .env file in the project root directory with the following variables:


# MongoDB URI

MONGO_URI=your_mongodb_connection_string

# JWT Secret

JWT_SECRET=your_jwt_secret_key

# Clipdrop API Key

CLIPDROP_API=your_clipdrop_api_key

# Razorpay Keys

RAZORPAY_KEY_ID=your_razorpay_key_id
RAZORPAY_KEY_SECRET=your_razorpay_key_secret
Start the Server
Run the development server:


npm start
Access the Application
 Open your browser and navigate to http://localhost:3000.

How It Works

Sign Up & Login
 Users must create an account to access the features.

Text-to-Image Generation
 After logging in, users can input text to generate stunning visuals powered by Clipdrop.

Free Credits
 New users receive 10 free credits upon signup to try out the tool.

Purchase Additional Credits
 Users can buy credits via Razorpay, choosing from flexible plans: Basic, Advanced, or Business.

Dependencies

 These are the libraries required for the application to function in production.

Backend Libraries

 axios: HTTP client for making API requests (used for interacting with the Clipdrop API).

 bcrypt: For hashing and securely storing user passwords.

 cors: Middleware to handle Cross-Origin Resource Sharing for 
 API security.

 dotenv: For managing environment variables securely.

 express: Web framework for building the backend REST API.

 form-data: Handles form submissions in API requests (often used with file uploads).

 jsonwebtoken: For generating and verifying JWTs for user authentication.

 mongoose: ODM library to connect and manage MongoDB database interactions.

Utility Libraries

 razorpay: Official Razorpay SDK for integrating payment gateway functionality.

Development Tool
 nodemon: Development utility to automatically restart the server on file changes.

DevDependencies
These are tools and libraries used during development but not required in production.

 Frontend Libraries

  @types/react & @types/react-dom: TypeScript type definitions for React and React DOM.
  @vitejs/plugin-react: Vite plugin to support React development.

Styling Tools

 autoprefixer: PostCSS plugin to automatically add vendor prefixes to CSS.
 postcss: Tool for processing CSS, often used with Tailwind CSS.
 tailwindcss: Utility-first CSS framework for designing responsive and modern UIs.
Linting and Formatting

 eslint: Linting tool to enforce code quality and consistency.
 @eslint/js, eslint-plugin-react, eslint-plugin-react-hooks, eslint-plugin-react-refresh: ESLint plugins for React-specific linting.


 globals: Provides globally recognized variables for ESLint.

Development Environment

 vite: Next-generation frontend tooling to build and serve your React application efficiently.

Contribution
 Contributions are welcome! Feel free to fork the repository, make changes, and submit a pull request.

License
 This project is licensed under the MIT License.
