# RoadSOS

RoadSOS is a user-facing emergency assistance application that provides real-time location detection, emergency profile management, incident tracking, and live discovery of nearby emergency services.

## Features

- **Clean Emergency Profile Setup**: New users start completely clean with zero demo data. User profile details, active incident parameters, emergency contacts, and customizable safety tips are stored safely in `localStorage`.
- **Real Location Detection**: Integrates with the browser's Geolocation API (`navigator.geolocation`) and OpenStreetMap reverse geocoding to determine your actual street and coordinates.
- **Live Nearby Emergency Services**: Discovers real hospitals, ambulance facilities, police stations, and vehicle recovery services around your real coordinates via OpenStreetMap / Overpass services.
- **Dynamic Haversine Distance**: All service distances are computed in real time from your live GPS position.
- **Accidental Trigger Protection**: The SOS action includes a confirmation dialog and countdown flow before entering Emergency Mode.
- **Emergency Mode**: Displays your real saved details, location coordinates, primary emergency contact, and the nearest verified responders with quick call and location-sharing options.
- **Emergency First Aid Assistant**: Built-in interactive guidance for critical scenarios (bleeding, fractures, CPR, collisions, breakdowns) aware of your actual saved incident details.

## How to Run

Open `index.html` directly in any modern web browser or serve it using a local static web server (such as VS Code Live Server or Python `http.server`).
