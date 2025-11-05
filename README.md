# Mapty

Mapty is a JavaScript application inspired by the course of Jonas Schmedtmann.  
It allows users to **log workouts (running or cycling)** on an interactive map, visualize their routes, and store the data locally for future sessions.  

---

## Description

Mapty combines the **Geolocation API** and **Leaflet.js** to create a simple yet powerful workout tracker.  
The app detects your location, lets you click anywhere on the map to add a workout, and records details such as distance, duration, cadence, and elevation gain.

All workouts are stored in **localStorage**, so your data remains available even after reloading the page.

**Main features:**
-  View your real-time location on a map  
-  Add running or cycling workouts by clicking on the map  
-  Display workout details and stats  
-  Persist workouts in localStorage  
-  Re-center the map to any saved workout location  

---

##  Tools & Technologies

- **Language:** JavaScript (ES6+)
- **Map Library:** [Leaflet.js](https://leafletjs.com/)
- **Browser APIs:** Geolocation API, localStorage
- **Styling:** CSS3, custom layout
