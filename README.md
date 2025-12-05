🚍 SUCA — Smart Urban Commute Assistant
Real-time Public Transport + Shared Mobility + AI Predictions
SUCA (Smart Urban Commute Assistant) is a unified smart mobility platform designed to reduce travel uncertainty in urban cities by combining:

✅ Real-time public transport tracking
✅ Nearby sharable autos / cabs / bikes
✅ Hybrid route planning
✅ AI-based crowd & delay prediction
✅ Fare & ETA optimization
✅ Live map with buses + metro simulation

Built using React (frontend), Node/Express (backend), OpenStreetMap, and AI logic, SUCA provides a seamless travel planning experience for daily commuters.

⭐ Features
🚍 1. Real-Time Public Transport Tracking
Live bus location simulation

ETA updates every 5 seconds

On-time vs delayed status indicators

BMTC & Namma Metro live train simulation

🚇 2. Metro & BMTC Integration
Moving metro trains (Green & Purple lines)

Moving BMTC buses with status, delay & ETA

Map markers update automatically

🛺 3. Nearby Share Mobility
Autos, cabs, bikes, e-scooters

Distance, fare rate, rating

Heatmap showing congestion zones

🧠 4. AI-Based Predictions
Crowd estimation based on time

Delay risk probability

Additional wait-time prediction

Fare + ETA optimizer:

💰 Cheapest

⚡ Fastest

🤝 Balanced Smart

🗺 5. Interactive Map (React-Leaflet)
OpenStreetMap tiles (no API key needed)

Start & destination markers

Live bus & metro movements

Heatmap overlay

🏗 Tech Stack
🎨 Frontend
React.js

React-Leaflet

Leaflet.js

heatmap overlay

⚙️ Backend
Node.js

Express.js

Simulated live transit models

REST APIs

🗺 Mapping
OpenStreetMap

Leaflet Heatmaps

Real-time marker updates

📁 Project Structure
SUCA_Project/
│
├── frontend/
│   ├── src/
│   │   ├── App.js
│   │   ├── MapView.js
│   │   └── components/…
│   └── public/
│
└── backend/
    ├── index.js
    ├── package.json
    └── data/
🚀 How to Run the Project
1️⃣ Start Backend
cd backend
npm install
node index.js
Runs on → 

2️⃣ Start Frontend
cd frontend
npm install
npm start
Runs on → 

🔥 API Endpoints (Backend)
Endpoint	Description
/stops	Get all bus/metro stops
/route?from=X&to=Y	Show best routes
/nearby?lat=&lng=	Nearby autos/cabs/bikes
/hybrid	Hybrid route recommendation
/ai	AI crowd + delay prediction
/optimize?type=	Fare/ETA AI optimizer
/live-buses	Live bus tracking
/bmtc-live	BMTC tracking
/metro-live	Namma Metro tracking
🎯 One-Line Project Summary
“SUCA integrates public transport, shared mobility, and AI prediction into one platform to reduce urban travel uncertainty and improve commuter experience.”

🏆 Why This Project Stands Out (Hackathon Ready)
Combines 5 smart-city features into one system

Real-time map with animations

AI-powered decision making

Scalability for actual smart city deployment

Clean, modular codebase

📜 License
This project is for educational and hackathon usage only.
