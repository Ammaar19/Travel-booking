Travel Planner Pro - Web Application
Travel Planner Pro

Travel Planner Pro is a web application that allows users to efficiently plan their trips, discover new destinations, and make the most of their travel experiences. The application provides various features such as destination search, itinerary planning, user authentication, personalized dashboard, interactive maps, reviews, and social sharing options.

Tech Stack
Front-End: HTML, CSS, JavaScript, React.js
Back-End: Node.js with Express.js
Database: MongoDB
Map Integration: Mapbox or Google Maps API
User Authentication: JSON Web Tokens (JWT)
Setup
Follow the instructions below to set up and run the Travel Planner Pro web application locally.

Prerequisites
Node.js and npm (Node Package Manager) should be installed on your system.
MongoDB should be installed and running.
Installation


Navigate to the project directory.
bash

cd travel-planner-pro

Install the required dependencies for both the client (front-end) and server (back-end).
bash

# Install client dependencies
cd client
npm install

# Install server dependencies
cd ../server
npm install
Configure Environment Variables

Create a .env file in the server directory and add the following variables:

makefile

PORT=5000           # Port on which the server will run
DATABASE_URL=<YOUR_MONGODB_CONNECTION_STRING>
JWT_SECRET=<YOUR_JWT_SECRET_KEY>
Running the Application

Start the server.
bash

cd server
npm start

Start the client.
bash

cd client
npm start

The application will be available at http://localhost:3000/.
