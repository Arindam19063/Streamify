# Streamify
The project Streamify – A Web-Based Movie Streaming Application Using React.js and Firebase effectively illustrates how cloud technologies and modern frontend frameworks can be integrated to build dynamic and scalable web applications.
##Overview

Streamify is a web-based movie streaming application inspired by Netflix.
It demonstrates how to build a responsive, cloud-connected OTT platform using React.js for the frontend and Firebase for backend services like authentication, database, and hosting.
The app allows users to log in securely, view movie categories, and fetch real movie data dynamically using the TMDB API.

🚀 Features

🎥 Dynamic movie data fetched using TMDB API

🔐 Secure user authentication (Login/Signup) with Firebase Authentication

☁️ Real-time hosting and database via Firebase Hosting & Firestore

💻 Responsive UI design built with React.js, HTML, CSS, and JavaScript

🧭 Smooth navigation using React Router

📱 Works across all devices (desktop, tablet, and mobile)

🧩 System Architecture

Streamify is based on a three-layer architecture:

Frontend Layer: React.js components for UI and interaction

Backend Layer: Firebase for authentication, hosting, and database

Integration Layer: Axios/Firebase SDK connects React components with TMDB API and Firebase

🛠️ Technologies Used
Component	Technology
Frontend	React.js, HTML, CSS, JavaScript
Backend	Firebase (Authentication, Firestore, Hosting)
API	TMDB API
Tools	Node.js, Vite, Visual Studio Code, Git & GitHub
⚙️ Installation and Setup
1️⃣ Clone the Repository
git clone https://github.com/yourusername/streamify.git
cd streamify

2️⃣ Install Dependencies
npm install

3️⃣ Configure Firebase

Create a Firebase project on Firebase Console

Enable Authentication (Email/Password)

Set up Firestore Database and Hosting

Copy your Firebase configuration keys into a .env file:

REACT_APP_FIREBASE_API_KEY=your_api_key
REACT_APP_FIREBASE_AUTH_DOMAIN=your_auth_domain
REACT_APP_FIREBASE_PROJECT_ID=your_project_id
REACT_APP_FIREBASE_STORAGE_BUCKET=your_storage_bucket
REACT_APP_FIREBASE_MESSAGING_SENDER_ID=your_sender_id
REACT_APP_FIREBASE_APP_ID=your_app_id
REACT_APP_TMDB_API_KEY=your_tmdb_api_key

4️⃣ Run the Application
npm run dev


Visit http://localhost:5173/
 in your browser.

🧪 Testing

The following tests were performed:

✅ Firebase Authentication (Login, Signup, Logout)

✅ API Fetching from TMDB

✅ Responsive design on multiple devices

✅ Smooth navigation using React Router

✅ Firebase hosting deployment verification

📊 Results

Real-time movie data fetched successfully

Smooth navigation between pages

Secure login/logout operations

Fast loading via Firebase Hosting

Responsive layout across devices

🔮 Future Scope

Add user profiles and personalized movie recommendations

Implement search and filter functionality

Add watchlist or favourite movies feature

Create an admin panel for movie management

Integrate real-time video streaming APIs

Build a mobile app version using React Native

⚠️ Limitations

Currently supports only trailer previews, not full-length video playback

No admin control panel for adding or updating content

Dependent on TMDB API for movie data

Free-tier Firebase limits performance and storage
