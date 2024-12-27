###YOUTUBE CLONE


Project Overview
This project is a YouTube clone built using React for the front-end and Node.js with Express for the back-end. The application allows users to register, log in, view videos, create channels, comment on videos, and more. The back-end is connected to a MongoDB database to store user data, video metadata, and comments.

Features
Front-End (React)
Home Page:

YouTube Header with a static sidebar toggled via a top hamburger menu.
Filter buttons at the top.
Grid display of video thumbnails with each card showing:
Title
Thumbnail
Channel Name
Views
User Authentication:

Register and log in with:
Username
Email
Password
JWT for authentication.
Header shows a sign-in button before login, and user's name after login.
Redirect to a Google form for login and registration.
Search and Filter Functionality:

Search bar on the homepage to filter videos based on the title.
Filter buttons based on categories.
Video Player Page:

Display selected video with:
Video player
Title and description
Channel name
Like and dislike buttons
Comment section (add, edit, delete comments)
Channel Page:

Option to create a channel (available only for signed-in users).
Display a list of videos belonging to the channel.
Allow users to edit or delete their videos.
Responsive Design:

Fully responsive across all devices.
Back-End (Node.js, Express)
API Endpoints:

#User Authentication:
Sign up, login, and token-based authentication using JWT.
#Channel Management:
Create new channels and fetch channel information.
#Video Management:
Fetch, update, and delete videos.
#Comments:
Add and fetch comments.
#Database (MongoDB):
Collections for users, videos, channels, and comments.
Store video URLs and thumbnail URLs.

#Getting Started
Prerequisites
Node.js
MongoDB
npm (Node Package Manager)

#Installation:

Clone the repository:
git clone https://github.com/yourusername/youtube-clone.git
cd youtube-clone

Install dependencies for both front-end and back-end:
cd client
npm install
cd ../server
npm install

Set up environment variables:
Create a .env file in the server directory with the following variables:
MONGO_URI=your_mongodb_uri
JWT_SECRET=your_jwt_secret

Start the development server:

For the back-end:
cd server
npm run dev

For the front-end:
cd client
npm start

Running the Tests
Run tests for back-end:
cd server
npm test

#Usage
Open the application in your browser.
Register or log in to access all features.
Use the search bar and filter buttons to find videos.
Watch videos and interact with the comment section.
Create and manage your own channels and videos.

#Contributing
Fork the repository.
Create a new branch (git checkout -b feature/YourFeature).
Commit your changes (git commit -m 'Add some feature').
Push to the branch (git push origin feature/YourFeature).
Open a pull request.

#License
This project is licensed under Dev Vishnoi.
