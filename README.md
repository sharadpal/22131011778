React URL Shortener
A simple URL shortener web application built with React. This app allows users to input a long URL and receive a shortened version, potentially with authentication and notifications. It uses modern React libraries and supports form handling, notifications, and JWT-based token handling.

Features
URL shortening

Form handling with validation using react-hook-form

Notifications with react-toastify

JWT authentication support

Responsive user interface

Deployed with serve for production builds

Tech Stack
React (^16.13.1)

React Router (^5.2.0)

Axios (^0.19.2)

JWT Decode (^2.2.0)

Node Sass (^4.14.1)

React Hook Form (^6.1.0)

React Toastify (^6.0.8)

Getting Started
Prerequisites
Node.js (>=12)

npm or yarn

Installation
bash
Copy
Edit
git clone https://github.com/yourusername/react-url-shortener.git
cd react-url-shortener
npm install
Development
bash
Copy
Edit
npm run dev
Runs the app in development mode. Open http://localhost:3000 to view it in the browser.

Build
bash
Copy
Edit
npm run build
Builds the app for production to the build folder.

Production
bash
Copy
Edit
npm start
Serves the production build using serve.

Project Structure
java
Copy
Edit
react-url-shortener/
├── public/
├── src/
│   ├── components/
│   ├── pages/
│   ├── services/
│   └── App.js
├── .gitignore
├── package.json
└── README.md
