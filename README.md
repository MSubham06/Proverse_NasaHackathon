# Proverse: Community Mapping System

**Proverse** is a project I built to explore how geospatial technology can help communities better understand and solve local issues. It’s a GIS-powered mapping system that visualizes things like traffic congestion, pollution, and access to public services in a user-friendly and interactive way. I’ve integrated tools like voice recognition, weather APIs, and custom GeoJSON data to make the experience both powerful and easy to use—for urban planners, decision-makers, and everyday citizens alike.

![Proverse Overview](https://github.com/user-attachments/assets/b31e9272-2da9-417c-a567-deec90df878c)  
## Link : https://drive.google.com/file/d/1rvVKlbbjYqCAO1rbg7ZYw_YAmKE0OsV8/view?usp=sharing

## Table of Contents
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation and Setup](#installation-and-setup)
- [Usage Guide](#usage-guide)
- [Open-Source Libraries and Tools](#open-source-libraries-and-tools)
- [How It Works](#how-it-works)
- [Contributing](#contributing)
- [License](#license)
- [Links](#links)

## Features

![Community Mapping](https://github.com/user-attachments/assets/b9052fb7-a57e-4f5f-95e7-fc7b32969fb3)

Here are some key features I focused on while building Proverse:

1. **Dynamic Map with Multiple Layers**  
   - The map, powered by Leaflet.js, supports multiple views (Street & Satellite).
   - You can toggle between data layers for:
     - Traffic congestion
     - Land pollution
     - Drainage systems
     - Custom GeoJSON datasets for local issues like air quality and traffic flow

2. **Voice-Controlled Interaction**  
   - Using the browser’s SpeechRecognition API, you can navigate the map hands-free.
   - Say commands like “Go to [location]” or “Show traffic data,” and Proverse responds with TTS feedback.

3. **Turn-by-Turn Routing**  
   - Thanks to Leaflet Routing Machine, you can get real-time directions between locations.

4. **Weather Integration**  
   - Pulls in live weather data from OpenWeatherMap, based on the user’s location.
   - Weather info is displayed in a mini-overlay with temperature updates.

5. **Interactive Sidebars**  
   - Easily control different views like:
     - Traffic data
     - Pollution levels
     - Weather reports
     - Education and healthcare facilities

6. **Mobile-Responsive Design**  
   - The layout works seamlessly across devices—mobile, tablet, and desktop.

7. **Ready-to-Go Use Case Prototypes**  
   - Includes sample setups for mapping vegetation, air quality, traffic, and civic services.
   - Uses custom icons for highlighting local problems like drainage and pollution.

![Screenshot 2024-10-06 192128](https://github.com/user-attachments/assets/059daae9-7db1-4d88-b667-eef56179e90f)

## Technologies Used
- **HTML5**, **CSS3**, **JavaScript**
- **Leaflet.js** – Mapping and interaction
- **GeoJSON** – Community data visualization
- **SpeechRecognition API** – For voice commands
- **OpenWeatherMap API** – Weather data
- **Leaflet Routing Machine** – Navigation and routing
- **Bootstrap** – Responsive layout

## Installation and Setup

1. **Install Dependencies**  
   Make sure Node.js is installed, then run:  
   ```bash
   npm install
