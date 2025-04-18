# ♻️ eWaste Facility Locator

## A web application to help users find nearby electronic waste recycling facilities and promote responsible e-waste disposal.

Welcome to the **eWaste Facility Locator**, a Node.js-based application designed to help users locate and interact with electronic waste disposal or recycling facilities. 
This project leverages MongoDB for data management and provides a robust backend API to support user interaction and pin-based mapping.

---

## 🚀 Features

- 🔐 User Authentication
- 📍 Add and View eWaste Facility Pins on a Map
- 🗃️ MongoDB-based Data Models for Facilities and Users
- 🌐 RESTful APIs for integration with frontend apps
- 🛠️ Easy setup and development with Node.js and Express
#**
- **Responsive Design** - Mobile-friendly interface for on-the-go access
- **User Submissions** - Crowdsourced facility additions and updates
- **Environmental Impact Calculator** - Estimate your e-waste reduction impact

---

## 🧰 Tech Stack
- **Frontend**: React.js, React Router, React Leaflet, Tailwind CSS, Axios
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **ORM**: Mongoose
- **Authentication**: Custom/JWT-based (based on your actual implementation)
- **Environment Management**: dotenv
- **APIs**: Google Maps JavaScript API, Geolocation API

---

## 📁 Project Structure

eWasteFacility-main/
├── Backend/                     # Backend server (Node.js + Express)
│   ├── models/                 # Mongoose models (e.g., Users, Pins)
│   ├── routes/                 # API routes
│   ├── .env                    # Environment variables
│   ├── index.js                # Server entry point
│   ├── package.json            # Backend dependencies
│   └── hey.txt                 # (Optional/test file)
│
├── frontend/                   # Frontend client (Vite + React + Tailwind)
│   ├── src/                   # React source code
│   ├── index.html             # HTML template
│   ├── tailwind.config.js     # TailwindCSS configuration
│   ├── vite.config.ts         # Vite configuration
│   ├── postcss.config.js      # PostCSS setup
│   ├── package.json           # Frontend dependencies
│   ├── tsconfig.*.json        # TypeScript configurations
│   ├── eslint.config.js       # ESLint setup
│   └── vercel.json            # Deployment configuration
│
└── README.md                  # Project documentation

---

## 📖 Usage

### 🔍 Search for Facilities
- Enter your location manually or use device geolocation.
- Browse through a list of nearby e-waste recycling centers.

### 🗺️ Map Interaction
- Zoom in/out on the interactive map.
- Click on map markers to view facility details.
- Get directions using integrated maps (Google Maps or OpenStreetMap).

### 🏢 Facility Details
- View operating hours and contact information.
- Check accepted materials (e.g., batteries, appliances).
- See user ratings and reviews.

### ✍️ Contribute
- Submit new facilities via a user-friendly form.
- Update details of existing facilities.
- Report incorrect or outdated listings.

---

## 📦 Installation

## 🚀 Getting Started with SetUp

### Prerequisites
- Node.js (v14 or higher)
- npm (v6 or higher)
- MongoDB (Local or Atlas)
- npm or yarn
- Google Maps API key

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/YashwanthDevagudi/ewasteFacility.git
   cd ewasteFacility

## Install dependencies
npm install

## Create .env file in root directory:env
REACT_APP_GOOGLE_MAPS_API_KEY=your_api_key_here
REACT_APP_BACKEND_URL=your_backend_url_here
MONGO_URI=your_mongo_connection_string
PORT=5000

## Start development server:
npm start

## The server will start on http://localhost:5000.

---

## 🛠️ Configuration
Configure these environment variables in your .env file:

Variable Name              -->                	Description
--------------                               ------------
REACT_APP_GOOGLE_MAPS_API_KEY   -->       	    Google Maps JavaScript API key
REACT_APP_BACKEND_URL           -->      	    API endpoint for facility data
REACT_APP_GEOCODING_API_KEY     -->        	  (Optional) Geocoding service API key

## 🧪 API Endpoints
Example routes (adjust depending on your actual routes)
- GET /api/pins - Fetch all facility pins
- POST /api/pins - Create a new pin
- POST /api/users/register - Register a new user
- POST /api/users/login - Authenticate a user

## 🙌 Contributing
Contributions are welcome! Feel free to fork the repository and submit pull requests.

## 📧 Contact
- Yashwanth Devagudi - GitHub Profile
- Project Link: https://github.com/YashwanthDevagudi/ewasteFacility
- Live Demo: https://ecorecycle-e.vercel.app/













   
