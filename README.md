# Gym_Website
Gym Website
This project is a full-stack web application developed using the MERN stack (MongoDB, Express, React, and Node.js). It is designed to showcase a modern, responsive gym website with various features such as membership details, class schedules, and contact information.

# Table of Contents
Features
Technologies Used
Installation
Usage
Folder Structure
API Routes
Deployment
Contributing
License
# Features
Home Page: A landing page showcasing the gym's facilities, services, and testimonials.
Membership Plans: Information about different membership packages.
Class Schedules: Display of available classes and their schedules.
Trainer Profiles: Information about gym trainers, their expertise, and qualifications.
Contact Form: Users can send inquiries to the gym via an integrated contact form.
Login & Registration: User authentication for members.
Admin Dashboard: Allows admins to manage classes, trainers, and memberships.
# Technologies Used
Frontend: React, CSS
Backend: Node.js, Express
Database: MongoDB
Email Service: Nodemailer (for contact form and notifications)
Tools & Libraries:
Axios (for API requests)
Mongoose (for MongoDB object modeling)
JWT (for authentication)
React Router (for navigation)
# Installation
Clone the repository:
bash
Copy code
git clone https://github.com/your-username/gym-website.git
# Navigate to the project directory:
bash
Copy code
cd gym-website
# Install server dependencies:
bash
Copy code
npm install
# Install client dependencies:
bash
Copy code
cd client
npm install
Usage
Set up environment variables:
Create a .env file in the root directory with the following details:
bash
Copy code
PORT=5000
MONGO_URI=your_mongoDB_uri
JWT_SECRET=your_jwt_secret
EMAIL_SERVICE=your_email_service
EMAIL_USER=your_email_user
EMAIL_PASS=your_email_password
Run the backend:
bash
Copy code
npm run server
Run the frontend:
bash
Copy code
cd client
npm start
Folder Structure
php
Copy code
# gym-website/
│
├── client/                # React frontend
│   ├── public/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── styles/
│   │   └── App.js
│   └── package.json
│
├── models/                # MongoDB models (e.g., User, Membership)
├── routes/                # Express API routes
├── controllers/           # Route controllers for handling logic
├── config/                # Configuration files (e.g., database connection)
├── server.js              # Entry point for the backend server
└── package.json           # Backend dependencies
API Routes
/api/users: Handles user registration and login.
/api/memberships: CRUD operations for gym memberships.
/api/classes: CRUD operations for class schedules.
/api/contact: Send contact form details to the gym's email.
Deployment
To deploy the application on platforms like Heroku, Netlify, or Vercel:

Set up your environment variables for production.
Ensure MongoDB is connected through a cloud service like MongoDB Atlas.
Deploy the frontend and backend separately or together.
Contributing
If you would like to contribute, please fork the repository and submit a pull request.

License
This project is licensed under the MIT License.

