# Backend README (server)

## Live link :- https://weather-webiste-mern-frontend-mfa.vercel.app/

```markdown
# Weather Website Backend

This is the backend server for the Weather Website, providing API endpoints for user registration, login,
 OTP verification, password reset, and weather data retrieval.

## Features

- User Registration and Login
- OTP Verification
- Password Reset Functionality
- Weather Data Retrieval as per location

## Technologies Used

- Node.js
- Express.js
- MongoDB
- Mongoose
- Nodemailer
- JWT (JSON Web Token)
- Randomatic
- dotenv

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/NALLAPUNENIVAMSIKRISHNA/Weather_webiste_mern_backend_mfa/tree/main
   cd serer
   ```

2. Install the dependencies:
   ```bash
   npm install
   ```

3. Create a `.env` file in the root directory and add the following environment variables:
   ```env
   MONGODB_URL=your_mongodb_connection_string
   EMAIL=your_email_address
   EMAIL_PASSWORD=your_email_password
   RESET_TOKEN_SECRET=your_jwt_secret
   ```

## Running the Server

Start the server:
```bash
node server.js
```

The server will be running on `http://localhost:3001`.

## API Endpoints

- `POST /auth/register` - User Registration
- `POST /auth/login` - User Login
- `POST /auth/verify-otp` - OTP Verification
- `POST /auth/request-reset` - Request Password Reset
- `POST /auth/reset-password` - Reset Password
