###Healthify - Personalized Health Recommendations App

Healthify is a full-stack web application aimed at helping users maintain a healthy lifestyle by providing personalized health recommendations. This project uses MongoDB Atlas Vector Search to suggest relevant health tips, Cosmocloud for user authentication, and Firebase Genkit to send real-time notifications.

Features
User Authentication: Login and registration with Cosmocloud.
Personalized Recommendations: AI-powered suggestions using MongoDB Atlas Vector Search.
Real-time Notifications: Health reminders and tips via Firebase Genkit.
Decentralized Storage: Option to store personal health data with Google IDX.
Tech Stack
Frontend: React.js
Backend: Node.js + Express.js
Database: MongoDB Atlas (Vector Search enabled)
Authentication & Cloud: Cosmocloud
Real-time Notifications: Firebase Genkit
Decentralized Storage: Google IDX (Optional)
Project Structure
bash
Copy code
healthify/
├── client/                # React frontend
│   ├── public/
│   └── src/
│       ├── components/    # React components
│       ├── pages/         # Login, Dashboard, etc.
│       └── App.js
├── server/                # Node.js backend
│   ├── routes/            # API routes
│   ├── models/            # MongoDB models
│   └── server.js
├── .env                   # Environment variables
├── README.md
└── package.json           # Dependencies
Installation and Setup
Step 1: Clone the Repository
bash
Copy code
git clone <your-repository-url>
cd healthify
Step 2: Install Dependencies
bash
Copy code
# Server dependencies
cd server
npm install

# Client dependencies
cd ../client
npm install
Step 3: Configure MongoDB Atlas
Create a cluster in MongoDB Atlas and enable Vector Search.
Create a recommendations collection with sample data.
Add your MongoDB connection string to the .env file:
bash
Copy code
MONGO_URI=mongodb+srv://<username>:<password>@cluster.mongodb.net/healthify
Step 4: Configure Firebase Genkit
Create a Firebase project.
Add your Firebase configuration to client/src/firebaseConfig.js:
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
Step 5: Set Up Cosmocloud Authentication
Register your app on Cosmocloud.
Add your Organization ID and App Name to the .env file:
bash
Copy code
COSMOCLOUD_ORG_ID=<your-org-id>
COSMOCLOUD_APP_NAME=<your-app-name>
Step 6: Run the Application
Open two terminals:

Backend:

bash
Copy code
cd server
npm start
Frontend:

bash
Copy code
cd client
npm start
Visit the app at: http://localhost:3000

API Endpoints
POST /api/login: User login
POST /api/register: User registration
GET /api/recommendations: Get personalized health recommendations
Usage
Register or log in with Cosmocloud authentication.
Input your health data and preferences on the dashboard.
Receive personalized recommendations using MongoDB Atlas Vector Search.
Get real-time notifications via Firebase Genkit.
Optionally store user data in Google IDX for decentralized storage.
Contributing
Feel free to open issues or submit pull requests to contribute.

License
This project is licensed under the MIT License.
