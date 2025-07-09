# User Authentication with React + Vite + Back4App

This project is a simple and secure user authentication system built with React (via Vite) and JavaScript. It includes user registration, login, password reset, and homepage routing. The app connects to [Back4App](https://www.back4app.com/) as the backend service for user management. This was developed as a school project to demonstrate core concepts in cybersecurity and frontend authentication flow.

---

## Features

- Sign up with email and password
- Secure login functionality
- Password reset via email
- Auth-based routing (home/login/signup)
- Error handling and validation
- Responsive layout

---

## Technologies Used

- React + Vite
- JavaScript
- Back4App (Parse)
- React Router
- Tailwind CSS (optional, if used)
- ESLint (basic rules included)

---

## Getting Started

### Prerequisites

- Node.js (v16+ recommended)
- A Back4App account and app created

### Setup Instructions

```bash
# Clone the repository
git clone https://github.com/Gledis-Hoxha/user-authentication.git
cd user-authentication

# Install dependencies
npm install

# Start the development server
npm run dev

Parse.initialize("YOUR_APP_ID", "YOUR_JS_KEY");
Parse.serverURL = "https://parseapi.back4app.com/";

