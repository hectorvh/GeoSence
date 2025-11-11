
  # GeoFenceSense Web Dashboard Design

GeoFenceSense is a smart geofencing platform that helps farmers and pet owners create virtual boundaries on a map and receive instant alerts when a tagged animal leaves a safe zone.
Each boundary is stored as a GeoJSON polygon, and tracking data is streamed in real time via GSM or LoRaWAN to a cloud-based backend for monitoring and analytics.

Problem

Farmers managing livestock in open or semi-open environments often lack continuous monitoring systems to track animal movement and behavior.
The absence of real-time geospatial data leads to inefficient herd management, increased operational costs, and difficulties in ensuring animal welfare and safety.
This limitation reduces productivity and prevents farmers from adopting data-driven decision-making practices for sustainable livestock management.

Solution

GeoFenceSense provides an easy-to-use web and mobile interface to draw geofences, link low-power GPS devices, and receive real-time alerts whenever an animal crosses predefined boundaries.

Key Features

Custom Geofences: Draw and edit virtual boundaries (point/line/polygon) directly on a map — stored as GeoJSON.

Smart Alerts: Instant exit/entry notifications (push/email/SMS) with a configurable debounce and grace period.

Live Tracking: Real-time position updates, trails, and last-seen timestamps.

Energy Efficiency: Configurable low-power profiles (e.g., 5/10/30-minute intervals or motion-based wake).


This is a code bundle for GeoFenceSense Web Dashboard Design. 
The original project is available at https://www.figma.com/design/D54WGrF3VHpHudpIL1l6LN/GeoFenceSense-Web-Dashboard-Design.

  ## Running the code

  Run `npm i` to install the dependencies.

  Run `npm run dev` to start the development server.
