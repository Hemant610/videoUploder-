# Video Upload Application

## Overview
This is a simple web application for uploading and managing videos. It uses the MERN stack (MongoDB, Express, React, Node.js) and includes features like 
form validation, dynamic video listing, and RESTful API endpoints.

## Features
- Upload videos with title and description
- View a list of uploaded videos
- Delete videos
- RESTful API for CRUD operations

## Setup Instructions
1. Clone the repository
2. Install dependencies:
   ```
   npm install
   ```
3. Start the server:
   ```
   npm start
   ```
4. Open your browser and navigate to `http://localhost:3000`

## API Endpoints
- `GET /`: Render the main page
- `POST /upload`: Upload a new video
- `GET /videos`: Get all videos
- `GET /videos/:id`: Get a specific video by ID
- `DELETE /videos/:id`: Delete a video by ID

## Technologies Used
- Node.js
- Express
- MongoDB
- EJS
- Bootstrap
- JavaScript

## License
ISC 
