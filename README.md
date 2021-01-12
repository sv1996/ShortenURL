# ShortenURL
This is a URL Shortening Project (Backend) Build on Nodejs Express.js and Firebase

## Technology Used 

- HTML
- Node.js
- Express.js
- Firebase Authentication
- Axios.JS


# Installation

- npm init
- npm i express firebase admin 
- npm install body-parser

# Usage 

- First Install all npm packages 
- create account in firestore with email and password
- used all firestore deatils service account Initialize App

admin.initializeApp({
  credential: admin.credential.cert(serviceAccount),
});

- Then used local server localhost:3000/(url shortening route (ws))
- used complete URL in bootstrap form 
- start the server by Command Node Index.js 
