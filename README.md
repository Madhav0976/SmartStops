# SmartStops 🚗🛣️

SmartStops is an intelligent route planning and navigation platform designed to help travelers discover optimal pitstops during long-distance journeys. Instead of simply finding the shortest route, SmartStops enhances the travel experience by recommending useful stops such as fuel stations, restaurants, rest areas, and scenic locations along the route.

The platform uses real-time route generation and location-based recommendations to assist users in planning safer, smarter, and more comfortable trips.

---

## 📌 Problem Statement

Long-distance travelers often struggle to identify essential facilities such as fuel stations, food outlets, rest areas, and emergency stops while traveling.

Traditional navigation systems mainly focus on route guidance and provide limited support for personalized stop recommendations.

SmartStops addresses this problem by providing intelligent pitstop suggestions along the selected route, helping users travel more efficiently and comfortably.

---

## 🎯 Objectives

* Provide smart route planning for travelers.
* Recommend useful pitstops along a journey.
* Improve travel convenience and safety.
* Help users locate fuel stations, restaurants, and rest areas.
* Offer a simple and user-friendly navigation experience.

---

## ✨ Key Features

### 🗺️ Smart Route Planning

* Interactive route generation between source and destination.
* Real-time map visualization using OpenStreetMap.

### ⛽ Fuel Station Recommendations

* Suggests nearby fuel stations along the route.
* Displays optimal pitstops based on route progression.

### 🍔 Food Recommendations

* Recommends restaurants and cafes near the travel route.

### ☕ Rest Stops

* Helps travelers identify suitable break locations.

### 📸 Scenic Locations

* Highlights attractive viewpoints and scenic stops.

### 📍 Live Location Support

* Allows users to use their current location as the starting point.

### 🚘 Navigation Assistance

* Provides route visualization and travel planning support.

---

## 🛠️ Tech Stack

### Frontend

* React.js
* Vite
* React Leaflet
* Leaflet Maps

### Backend

* Node.js
* Express.js

### Database

* MongoDB
* Mongoose

### APIs & Services

* OpenStreetMap
* OSRM Routing Engine

---

## 🏗️ Project Structure

```text
smartstops/
│
├── client/
│   ├── src/
│   ├── public/
│   └── vite.config.js
│
├── models/
├── routes/
├── server.js
├── package.json
└── .env
```

---

## ⚙️ Installation & Setup

### Clone Repository

```bash
git clone https://github.com/Madhav0976/SmartStops.git
cd SmartStops
```

### Install Backend Dependencies

```bash
npm install
```

### Install Frontend Dependencies

```bash
cd client
npm install
```

### Configure Environment Variables

Create a `.env` file in the root directory and add the required environment variables.

Example:

```env
PORT=5000
MONGODB_URI=your_mongodb_connection_string
```

### Run Backend

```bash
npm start
```

### Run Frontend

```bash
cd client
npm run dev
```

---

## 🚀 Future Enhancements

* AI-powered route recommendations.
* Traffic-aware dynamic route optimization.
* Weather-based travel suggestions.
* Emergency service recommendations.
* Personalized travel preferences.
* Mobile application support.

---

## 👥 Team

Build-A-Thon Project Team

* Venkata Bindu Madhav Tanguturi
* Abhishek Sonti
* Divya Sri Teku

---

## 📄 License

This project was developed for educational and hackathon purposes.

```
```
