# Healthify - Personalized Health Recommendations App 🏥

Healthify is a full-stack web application aimed at helping users maintain a healthy lifestyle by providing **personalized health recommendations**. This project integrates **MongoDB Atlas Vector Search** for AI-powered suggestions, **Cosmocloud** for authentication, and **Firebase Genkit** for real-time notifications. 

---

## 🚀 Features
- **User Authentication:** Secure login and registration using Cosmocloud.
- **AI-powered Health Suggestions:** Personalized recommendations with MongoDB Atlas Vector Search.
- **Real-time Notifications:** Stay on track with reminders through Firebase Genkit.
- **Decentralized Storage:** Option to store health data securely with Google IDX.

---

## 🛠️ Tech Stack
- **Frontend:** React.js  
- **Backend:** Node.js + Express.js  
- **Database:** MongoDB Atlas (Vector Search enabled)  
- **Authentication & Cloud:** Cosmocloud  
- **Real-time Notifications:** Firebase Genkit  
- **Decentralized Storage:** Google IDX (Optional)

---

## 📁 Project Structure

---

## 🛠️ Installation and Setup

### Step 1: Clone the Repository  

git clone <your-repository-url>
cd healthify
healthify/ ├── client/ # React frontend │ ├── public/ │ └── src/ │ ├── components/ # UI components │ ├── pages/ # Login, Dashboard, etc. │ ├── firebaseConfig.js │ └── App.js ├── server/ # Node.js backend │ ├── routes/ # API routes │ ├── models/ # MongoDB models │ └── server.js ├── .env # Environment variables ├── README.md └── package.json # Dependencies


---

## 🔧 Setup Instructions  

### Step 1: Clone the Repository  

git clone https://github.com/YOUR_USERNAME/healthify.git
cd healthify

Here’s the complete GitHub-ready README.md file for your project. You can copy-paste the entire content, including code blocks and formatting directly into your repository.

markdown
Copy code
# Healthify - Personalized Health Recommendations App 🏥  

Healthify is a full-stack web application that provides personalized health recommendations. This project demonstrates real-time features using Firebase Genkit, AI-powered recommendations with MongoDB Atlas Vector Search, and user authentication via Cosmocloud.

---

## 🚀 Features
- **User Authentication**: Secure login with Cosmocloud.  
- **Real-time Notifications**: Enabled through Firebase Genkit.  
- **AI-Powered Health Recommendations**: MongoDB Atlas Vector Search powers personalized suggestions.  

---

## 🛠️ Tech Stack
- **Frontend**: React.js  
- **Backend**: Node.js + Express.js  
- **Database**: MongoDB Atlas (with Vector Search)  
- **Authentication**: Cosmocloud  
- **Notifications**: Firebase Genkit  

---

## 📂 Project Structure
healthify/ ├── client/ # React frontend │ ├── public/ │ └── src/ │ ├── components/ # UI components │ ├── pages/ # Login, Dashboard, etc. │ ├── firebaseConfig.js │ └── App.js ├── server/ # Node.js backend │ ├── routes/ # API routes │ ├── models/ # MongoDB models │ └── server.js ├── .env # Environment variables ├── README.md └── package.json # Dependencies

yaml
Copy code

---

## 🔧 Setup Instructions  

### Step 1: Clone the Repository  

git clone https://github.com/YOUR_USERNAME/healthify.git
cd healthify
Step 2: Install Dependencies
Open two terminals (for client and server).

For Client (React):
cd client
npm install axios firebase react-scripts
npm start


For Server (Node.js):
Copy code
cd server
npm install express mongoose cors dotenv
npm start

Step 3: Environment Variables
Create a .env file in the root directory and add the following:
php
MONGO_URI=mongodb+srv://<username>:<password>@cluster.mongodb.net/healthify  
COSMOCLOUD_ORG_ID=<your-org-id>  
COSMOCLOUD_APP_NAME=<your-app-name> 



Here’s the complete GitHub-ready README.md file for your project. You can copy-paste the entire content, including code blocks and formatting directly into your repository.

markdown
Copy code
# Healthify - Personalized Health Recommendations App 🏥  

Healthify is a full-stack web application that provides personalized health recommendations. This project demonstrates real-time features using Firebase Genkit, AI-powered recommendations with MongoDB Atlas Vector Search, and user authentication via Cosmocloud.

---

## 🚀 Features
- **User Authentication**: Secure login with Cosmocloud.  
- **Real-time Notifications**: Enabled through Firebase Genkit.  
- **AI-Powered Health Recommendations**: MongoDB Atlas Vector Search powers personalized suggestions.  

---

## 🛠️ Tech Stack
- **Frontend**: React.js  
- **Backend**: Node.js + Express.js  
- **Database**: MongoDB Atlas (with Vector Search)  
- **Authentication**: Cosmocloud  
- **Notifications**: Firebase Genkit  

---

## 📂 Project Structure
healthify/ ├── client/ # React frontend │ ├── public/ │ └── src/ │ ├── components/ # UI components │ ├── pages/ # Login, Dashboard, etc. │ ├── firebaseConfig.js │ └── App.js ├── server/ # Node.js backend │ ├── routes/ # API routes │ ├── models/ # MongoDB models │ └── server.js ├── .env # Environment variables ├── README.md └── package.json # Dependencies

yaml
Copy code

---

## 🔧 Setup Instructions  

### Step 1: Clone the Repository  
git clone https://github.com/YOUR_USERNAME/healthify.git
cd healthify
Step 2: Install Dependencies
Open two terminals (for client and server).

For Client (React):

bash
Copy code
cd client
npm install axios firebase react-scripts
npm start
For Server (Node.js):

bash
Copy code
cd server
npm install express mongoose cors dotenv
npm start
Step 3: Environment Variables
Create a .env file in the root directory and add the following:
php
MONGO_URI=mongodb+srv://<username>:<password>@cluster.mongodb.net/healthify  
COSMOCLOUD_ORG_ID=<your-org-id>  
COSMOCLOUD_APP_NAME=<your-app-name>  

Step 4: Firebase Setup
Create a Firebase project and enable Cloud Messaging.
Replace the contents of firebaseConfig.js with your Firebase configuration:
const firebaseConfig = {
  apiKey: "YOUR_API_KEY",
  authDomain: "YOUR_AUTH_DOMAIN",
  projectId: "YOUR_PROJECT_ID",
  storageBucket: "YOUR_STORAGE_BUCKET",
  messagingSenderId: "YOUR_SENDER_ID",
  appId: "YOUR_APP_ID",
};

export default firebaseConfig;

Step 5: MongoDB Atlas Setup
Create a cluster on MongoDB Atlas.
Enable Vector Search.
Create a recommendations collection and insert the following sample documents:
{ "text": "Drink 8 glasses of water every day." }
{ "text": "Exercise for at least 30 minutes." }
{ "text": "Get at least 7 hours of sleep." }



Here’s the complete GitHub-ready README.md file for your project. You can copy-paste the entire content, including code blocks and formatting directly into your repository.

markdown
Copy code
# Healthify - Personalized Health Recommendations App 🏥  

Healthify is a full-stack web application that provides personalized health recommendations. This project demonstrates real-time features using Firebase Genkit, AI-powered recommendations with MongoDB Atlas Vector Search, and user authentication via Cosmocloud.

---

## 🚀 Features
- **User Authentication**: Secure login with Cosmocloud.  
- **Real-time Notifications**: Enabled through Firebase Genkit.  
- **AI-Powered Health Recommendations**: MongoDB Atlas Vector Search powers personalized suggestions.  

---

## 🛠️ Tech Stack
- **Frontend**: React.js  
- **Backend**: Node.js + Express.js  
- **Database**: MongoDB Atlas (with Vector Search)  
- **Authentication**: Cosmocloud  
- **Notifications**: Firebase Genkit  

---

## 📂 Project Structure
healthify/ ├── client/ # React frontend │ ├── public/ │ └── src/ │ ├── components/ # UI components │ ├── pages/ # Login, Dashboard, etc. │ ├── firebaseConfig.js │ └── App.js ├── server/ # Node.js backend │ ├── routes/ # API routes │ ├── models/ # MongoDB models │ └── server.js ├── .env # Environment variables ├── README.md └── package.json # Dependencies

yaml
Copy code

---

## 🔧 Setup Instructions  

### Step 1: Clone the Repository  
git clone https://github.com/YOUR_USERNAME/healthify.git
cd healthify
Step 2: Install Dependencies
Open two terminals (for client and server).

For Client (React):

bash
Copy code
cd client
npm install axios firebase react-scripts
npm start
For Server (Node.js):

bash
Copy code
cd server
npm install express mongoose cors dotenv
npm start
Step 3: Environment Variables
Create a .env file in the root directory and add the following:

php
Copy code
MONGO_URI=mongodb+srv://<username>:<password>@cluster.mongodb.net/healthify  
COSMOCLOUD_ORG_ID=<your-org-id>  
COSMOCLOUD_APP_NAME=<your-app-name>  
Step 4: Firebase Setup
Create a Firebase project and enable Cloud Messaging.
Replace the contents of firebaseConfig.js with your Firebase configuration:
javascript
Copy code
const firebaseConfig = {
  apiKey: "YOUR_API_KEY",
  authDomain: "YOUR_AUTH_DOMAIN",
  projectId: "YOUR_PROJECT_ID",
  storageBucket: "YOUR_STORAGE_BUCKET",
  messagingSenderId: "YOUR_SENDER_ID",
  appId: "YOUR_APP_ID",
};

export default firebaseConfig;
Step 5: MongoDB Atlas Setup
Create a cluster on MongoDB Atlas.
Enable Vector Search.
Create a recommendations collection and insert the following sample documents:
json
Copy code
{ "text": "Drink 8 glasses of water every day." }
{ "text": "Exercise for at least 30 minutes." }
{ "text": "Get at least 7 hours of sleep." }

Step 6: Code Overview
1. React Frontend (client/src/App.js).
2. import React, { useEffect, useState } from "react";
import axios from "axios";
import firebase from "firebase/compat/app";
import "firebase/compat/messaging";
import firebaseConfig from "./firebaseConfig";

firebase.initializeApp(firebaseConfig);

function App() {
  const [recommendations, setRecommendations] = useState([]);

  useEffect(() => {
    // Fetch personalized recommendations from backend
    axios.get("http://localhost:5000/api/recommendations")
      .then(response => setRecommendations(response.data))
      .catch(err => console.error("Error fetching recommendations:", err));
  }, []);

  return (
    <div className="App">
      <h1>Welcome to Healthify</h1>
      <h2>Your Personalized Health Recommendations:</h2>
      <ul>
        {recommendations.map((rec, index) => (
          <li key={index}>{rec}</li>
        ))}
      </ul>
    </div>
  );
}

export default App;


2. Node.js Backend (server/server.js)
const express = require("express");
const mongoose = require("mongoose");
const cors = require("cors");
require("dotenv").config();

const app = express();
app.use(cors());
app.use(express.json());

// Connect to MongoDB Atlas
mongoose.connect(process.env.MONGO_URI, { useNewUrlParser: true, useUnifiedTopology: true })
  .then(() => console.log("Connected to MongoDB Atlas"))
  .catch(err => console.error("MongoDB connection error:", err));

// Routes
const recommendationsRoute = require("./routes/recommendations");
app.use("/api/recommendations", recommendationsRoute);

const PORT = process.env.PORT || 5000;
app.listen(PORT, () => console.log(`Server running on port ${PORT}`));

3. Recommendations Route (server/routes/recommendations.js)
const express = require("express");
const Recommendation = require("../models/Recommendation");
const router = express.Router();

// Get all recommendations
router.get("/", async (req, res) => {
  try {
    const recommendations = await Recommendation.find();
    res.json(recommendations);
  } catch (err) {
    res.status(500).json({ error: "Failed to fetch recommendations" });
  }
});

module.exports = router;

4. Recommendation Model (server/models/Recommendation.js)
const mongoose = require("mongoose");

const recommendationSchema = new mongoose.Schema({
  text: String,
});

module.exports = mongoose.model("Recommendation", recommendationSchema);

🏃 Run the Application
Open two terminals to run the frontend and backend.

Terminal 1 (Backend)
cd server
npm start
Terminal 2 (Frontend)
cd client
npm start
📝 Project Demo
When both servers are running, visit http://localhost:3000 to see the React frontend.

You can access the backend API at http://localhost:5000/api/recommendations.

🔑 Authentication with Cosmocloud
Make sure your Cosmocloud Org ID and App Name are correctly set in the .env file.

🛡️ Real-Time Notifications with Firebase Genkit
Ensure that your Firebase project has Cloud Messaging enabled. You can send push notifications from the Firebase Console.

🤝 Contributing
Feel free to submit a pull request if you find any issues or improvements!

📜 License
This project is licensed under the MIT License.

💬 Contact
For any queries or issues, reach out at anadigupta55555@gmail.com

---

This **`README.md`** file is ready for **direct copy-pasting** into your GitHub repository. It contains all the relevant code, project setup, and instructions required for a clean and well-documented project. Let me know if you need further assistance! 🚀

