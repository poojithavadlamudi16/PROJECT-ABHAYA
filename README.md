# 🛡 Abhaya — Safe Journey Engine

**Abhaya** is a women-focused safety navigation prototype that recommends safer travel routes instead of simply suggesting the shortest path. The system analyzes nearby safety infrastructure such as police stations, hospitals, pharmacies, transit points, and time-of-day conditions to generate a **Dynamic Safety Index (DSI)** for available routes.

Developed as a hackathon project by **Team ByteSized Army**.

---

## 🚀 Problem Statement

Most navigation systems optimize for:

* Shortest distance
* Fastest travel time
* Lowest traffic

However, personal safety is often ignored.

Abhaya addresses this gap by helping users choose routes that provide better access to emergency services and public infrastructure, especially during late-night travel.

---

## ✨ Features

### 🗺 Safe Route Planning

* Enter origin and destination.
* Generates multiple route options.
* Highlights the safest available route.

### 📊 Dynamic Safety Index (DSI)

Routes are scored using:

* Police station proximity
* Hospital proximity
* Pharmacy availability
* Public transit accessibility
* Route density
* Time-of-day risk weighting

### 🚔 Nearby Safe Spots

Displays nearby:

* Police Stations
* Hospitals
* Clinics
* Pharmacies
* Fuel Stations
* ATMs
* Bus Stops
* Bus Stations

### 🚨 SOS Module

* One-click emergency trigger
* Simulates alerting trusted contacts
* Designed for future integration with real notification systems

### 🌙 Time-Aware Safety Analysis

Safety scores adjust according to:

* Morning commute
* Afternoon travel
* Night-time travel

### 📱 Responsive Interface

Optimized for:

* Desktop
* Tablet
* Mobile devices

### 🌡 Safety Heatmap

Visual representation of:

* Higher-risk zones
* Safer route corridors

---

## 🛠 Technology Stack

### Frontend

* HTML5
* CSS3
* JavaScript (Vanilla JS)

### Mapping & Geospatial Services

* Leaflet.js
* OpenStreetMap
* Nominatim Geocoding API
* OSRM Routing Engine
* Overpass API

---

## 🏗 System Workflow

1. User enters start and destination locations.
2. Nominatim converts locations into coordinates.
3. OSRM generates route alternatives.
4. Overpass API retrieves nearby safety-related infrastructure.
5. Dynamic Safety Index is calculated for each route.
6. Routes are ranked by safety score.
7. User receives:

   * Route comparison
   * Safety score
   * Nearby safe spots
   * Emergency access information

---

## 📈 Dynamic Safety Index (DSI)

The Dynamic Safety Index is a custom scoring mechanism that evaluates route safety using:

* Proximity-based scoring
* Infrastructure density
* Emergency service availability
* Time-sensitive weighting
* Route accessibility

Higher DSI values indicate safer travel conditions.

| DSI Score | Safety Level  |
| --------- | ------------- |
| 0 – 3     | High Risk     |
| 4 – 6     | Moderate Risk |
| 7 – 8     | Safe          |
| 9 – 10    | Highly Safe   |

---

## 🎯 Future Enhancements

* Real-time crime data integration
* Guardian live tracking
* GPS-based emergency alerts
* AI-powered risk prediction
* Public transport safety analytics
* Voice-activated SOS
* Mobile application deployment

---

## ⚠ Disclaimer

This project is a hackathon prototype developed for educational and demonstration purposes.

The SOS feature currently simulates emergency notifications and does not contact emergency services or trusted contacts in real time.

Route safety scores are estimates based on publicly available geographic data and should not be treated as guarantees of personal safety.

---

## 👥 Team

**Team ByteSized Army**

Project: **Abhaya — Safe Journey Engine**

Women Safety & Urban Mobility Hackathon Project

---

## 📄 License

This project is intended for educational and hackathon use.

