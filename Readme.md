🛰️ Real-Time Tracker

A real-time device location tracking app built using Node.js, Express, Socket.io, and Leaflet.js.
It allows multiple connected clients to share and view each other's live locations on an interactive map.

🚀 Features

📡 Live Tracking: Instantly broadcast and visualize device location updates using Socket.io.

🌍 Map Integration: Real-time map rendering powered by Leaflet.js
and OpenStreetMap.

🧭 Multiple Users: Each connected user is represented by a marker on the map.

⚡ Low Latency: Efficient, event-driven WebSocket communication ensures minimal delay.

🔄 Auto Cleanup: Removes disconnected users’ markers from the map.

🧱 Modular Code: Organized backend and frontend structure for scalability.

🧰 Tech Stack

Backend: Node.js, Express.js, Socket.io

Frontend: EJS, Leaflet.js, HTML, CSS, JavaScript

Tools: Nodemon, Git, Postman

🏗️ Installation & Setup

Clone the repository

git clone https://github.com/sunny-raj-sah/Real-time-device-tracker.git
cd real-time-tracker

Install dependencies

npm install

Start the server

node app.js

or (for auto-reload during development)

npx nodemon app.js

Open the app

http://localhost:3000

Allow browser location access to start live tracking.

🧭 How It Works

Each connected client emits its geolocation via navigator.geolocation.

The backend uses Socket.io to broadcast this data to all connected clients.

Leaflet.js displays each user’s position on an interactive OpenStreetMap.

When a user disconnects, their marker is automatically removed.

🧩 Folder Structure
real-time-tracker/
├── public/
│ ├── css/
│ │ └── style.css
│ ├── js/
│ │ └── script.js
├── views/
│ └── index.ejs
├── app.js
├── package.json
└── README.md

🌱 Future Enhancements

Here are some ideas to extend the project further:

🔐 User Authentication: Use JWT or OAuth for secure user sessions.

🗺️ Custom Map UI: Add user avatars, routes, and historical movement tracking.

💾 Database Integration: Store and retrieve location history using MongoDB or PostgreSQL.

🚘 Fleet/Delivery Mode: Assign custom markers and tracking groups (e.g., delivery agents).

📱 Progressive Web App (PWA): Enable mobile tracking and offline support.

⚙️ Deployment: Deploy on Render, Vercel, or AWS EC2 for live tracking.

👨‍💻 Author

Sunny Raj
📧 sunnyraj01000@gmail.com

🔗 GitHub https://github.com/sunny-raj-sah
| LinkedIn https://www.linkedin.com/in/sunny-raj-885588313/
