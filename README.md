# Snowi

Real-time snow reporting app to improve community safety and accessibility during winter conditions.

Snowi is a community-driven web application that enables users to report and track snow-related issues in real time. Built during a 36-hour hackathon, the platform connects residents, volunteers, and professionals through an interactive map to improve coordination for snow removal—especially important in Canadian winters.

---

## Features

- Real-time issue reporting
  - Users can report snow-related problems instantly
  - Location-based submissions using interactive maps

- Interactive map interface
  - Visualize reports using Leaflet.js
  - Integrated OpenStreetMap for accurate location tracking

- Community-driven coordination
  - Connects residents, volunteers, and responders
  - Helps improve response time for snow clearance

- Category-based filtering
  - Filter reports based on issue type or severity

---

## Tech Stack

- Frontend: React.js, Leaflet.js, HTML, CSS  
- Backend & Database: Firebase (Firestore, Real-time Database)  
- Maps & Location Services: OpenStreetMap API  
- Version Control: Git & GitHub  

---

## Project Structure

Snowi/
├── src/
│ ├── components/ # UI components (Map, forms, etc.)
│ ├── pages/ # Application pages
│ ├── services/ # Firebase & API logic
│ ├── utils/ # Helper functions
│ ├── App.js
│ └── index.js
├── public/
├── package.json
└── README.md

---

## Getting Started

### 1. Clone the repository
bash
git clone https://github.com/AnshikaP-06/Snowi.git
cd Snowi

### 2. Clone the repository
npm install

### 3. Set up environment variables
Create a .env file in the root directory and add your Firebase configuration:

REACT_APP_FIREBASE_API_KEY=your_api_key
REACT_APP_FIREBASE_AUTH_DOMAIN=your_auth_domain
REACT_APP_FIREBASE_PROJECT_ID=your_project_id
REACT_APP_FIREBASE_STORAGE_BUCKET=your_storage_bucket
REACT_APP_FIREBASE_MESSAGING_SENDER_ID=your_sender_id
REACT_APP_FIREBASE_APP_ID=your_app_id

### 4. Run the project
npm start

The app will run at:
http://localhost:3000

