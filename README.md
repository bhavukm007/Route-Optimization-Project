# 🗺️ Route Optimization System

This project is a **map-based route optimization system** built using **Python, OSMnx, NetworkX, and Folium**.  
The system finds the **shortest path and second shortest path** between two locations, calculates **distance, fuel cost, and estimated travel time**, and visualizes the routes on an interactive map.

The user can also select the **type of transport (car, bus, two-wheeler, walking)** and input **fuel price and speed** to estimate the total cost and travel time.

---

## 🏗️ Tech Stack

- **Language:** Python  
- **Graph Data:** OpenStreetMap (via OSMnx)  
- **Graph Algorithm:** Dijkstra / Uniform Cost Search (via NetworkX)  
- **Map Visualization:** Folium  
- **Geolocation:** OSMnx Geocoder  

---

## 🚀 Features

### 📍 Location-Based Routing
- Enter **start and destination locations by name**
- Automatically converts locations into coordinates
- Builds a road network graph from OpenStreetMap

---

### 🧭 Route Optimization
- Calculates **Shortest Path**
- Calculates **Second Shortest Path**
- Uses graph-based pathfinding

---

### ⛽ Travel Analytics
The system calculates:

- Total **Distance**
- **Estimated Time**
- **Fuel Cost**
- **Second Best Route Distance**

---

### 🚗 Transport Mode Selection

Users can choose the type of ride:

- Car
- Bus
- Two-wheeler
- Walking

Each mode has a different speed and affects **travel time and fuel cost calculation**.

---

## Application Screens

### Home Page

<img width="1274" height="755" alt="Screenshot 2026-03-08 090504" src="https://github.com/user-attachments/assets/c0436d9f-19a1-4155-94e7-3f5c69049572" />

The homepage allows users to enter the **starting location and destination** for route optimization.

---

### Resultant Optimized Map

<img width="1067" height="591" alt="image" src="https://github.com/user-attachments/assets/e37f7543-1457-4a29-9244-48e913b0ba50" />

Displays the **shortest path (green)** and **second shortest path (red)** on an interactive map.

---

### Original Map Data

<img width="1073" height="597" alt="image" src="https://github.com/user-attachments/assets/a4522005-a723-42f7-8ad1-d4d77d8934da" />

The map data is generated using **OpenStreetMap road network graphs**, showing the underlying road structure used for route computation.

---

### Route Details Output

<img width="1546" height="474" alt="image" src="https://github.com/user-attachments/assets/b3f146ee-a45b-46a8-a677-27ab6aac8ea0" />

The system outputs:

- Shortest route distance  
- Second shortest route distance  
- Estimated travel time  
- Fuel cost based on user input  
- Transport mode used  

---

## How It Works

1. The user enters **start and end locations**.
2. The system converts the location names into **latitude and longitude coordinates**.
3. A **road network graph** is downloaded from OpenStreetMap.
4. The nearest nodes in the graph are found.
5. **Shortest and second shortest paths** are computed using graph algorithms.
6. Distance, time, and fuel cost are calculated.
7. Routes are displayed on an **interactive map**.

---

## Author

**Bhavuk Mahajan**  
Computer Engineering Student  
Thapar Institute of Engineering and Technology
