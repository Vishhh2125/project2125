# EV Charge Finder

## Description
EV Charge Finder is a web application that allows users to locate, add, and manage electric vehicle charging stations on an interactive map. Users can register, log in, add new stations, view their own stations, and see live locations.

## Technologies Used
- **Frontend:** React, Redux Toolkit, React Router, Tailwind CSS, React-Leaflet (for maps)  
- **Backend:** Node.js, Express.js  
- **Database:** MongoDB  
- **Other:** JWT Authentication, REST API  

## Features
- User registration and login with JWT authentication  
- Interactive map to view charging stations  
- Add new charging stations to the map  
- View and manage user's own charging stations  
- Live location updates  

## Installation & Setup

### Prerequisites
- Node.js and npm installed  
- MongoDB instance running (local or cloud)

### Backend Setup
1. Navigate to the backend folder:  
   ```bash
   cd backend

2. Install dependencies:npm install
3. Create a .env file with your environment variables (e.g., MongoDB URI, JWT secret).
 PORT=
MONGODB_URI=
ACCESS_TOKEN_SECRET=
ACCESS_TOKEN_EXPIRY=
REFRESH_TOKEN_SECRET=
REFRESH_TOKEN_EXPIRY=
DB_NAME=

4. Run the backend server: npm start or npm run dev (if have nodemon )

###How to Use the Project
Register/Login: Create a new account or log in with existing credentials.

View Map: Browse all available electric vehicle charging stations on the interactive map.

Add Station: Click on the "Add Station" button to add a new charging station.

Manage Stations: Edit or delete your own stations via the sidebar panel.

Profile: View your profile details and log out using the top-right menu.



###Live Demo:-
live link of deployed project :https://project-2125-frontend.vercel.app






