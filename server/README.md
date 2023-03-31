.1.1 Frontend
React as a framework
React router for navigation
Formik and Yup for form and Form validation
Redux toolkit for state management
Redux with persistent for storage
React Dropzone for image uploads

.1.2 Backend
Node js as the runtime
Create directory name server
Install nodemon
Npm i –g nodemon
npm i express body-parser bcrypt cors dotenv gridfs-stream multer multer-gridfs-storage helmet morgan jsonwebtoken mongoose
npm init -y

Express js for backend management
Mongoose for managing Mongo Database
JSON web Token for authentication
Multer for File upload

//The cofiguration settings are in the github repos for the specific imported assets

The backend is running on port 3001 while frontend running on port 3000

AUTHENTICATION AND AUTHORIZATION
Authentication is allowing user to login
Authorization is allowing a user to access features which they must be logged in to see

netstat -ano | findstr :3001
use it in cmd to find other apps using the same port and search pip id over on task manager under details to stop it.

client created by
npx create-react-app client

run
server
npm run start

client
nodemon index.js
