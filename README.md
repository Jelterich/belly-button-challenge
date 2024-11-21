### Earthquake Visualization with Leaflet and GeoJSON
This project is a web application that dynamically visualizes earthquake data from the USGS Earthquake GeoJSON API using Leaflet.js, an open-source JavaScript library for interactive maps. It combines modern web technologies like Leaflet, D3.js, and GeoJSON to display earthquake data with interactive styling and informative popups.

## Features
Dynamic Earthquake Data: Displays earthquake information (location, magnitude, and time) from the USGS GeoJSON feed for the past week.
Interactive Map:
Styled circle markers based on earthquake magnitude.
Popups showing earthquake details such as location, magnitude, and timestamp.
Real-Time Visualization: Fetches the latest earthquake data from the USGS API.
Scalable and Responsive: Fully responsive design using Leaflet and custom CSS for map styling.
Installation
Prerequisites
Basic knowledge of HTML, CSS, and JavaScript.
A text editor (e.g., Visual Studio Code).
A live server to handle external API calls (e.g., via Live Server extension).
Steps
Clone the Repository:

bash
Copy code
git clone https://github.com/your-repo-name/earthquake-visualization.git
cd earthquake-visualization
File Structure:

bash
Copy code
/static
  /css
    style.css
  /js
    logic.js
index.html
Run the Application:

Open the index.html in a live server or browser.
Ensure internet access for fetching the Leaflet library and USGS data.
Technologies Used
Leaflet.js: Provides the map rendering and interactivity.
Reference: Leaflet Official Documentation
D3.js: Used for fetching and parsing GeoJSON data.
Reference: D3.js Documentation
GeoJSON: Standardized format for representing geographical features.
Reference: GeoJSON Specification
USGS Earthquake API: Supplies real-time earthquake data in GeoJSON format.
Reference: USGS Earthquake API
How It Works
Map Initialization:

The map is initialized using Leaflet and centered on San Francisco (default).
Tile layers from OpenStreetMap provide the map’s visual foundation.
Styling Earthquake Data:

Circle markers’ size and color are determined by earthquake magnitude.
Color Scheme:
Magnitude > 5: Red
Magnitude 4-5: Orange
Magnitude 3-4: Yellow
Magnitude 2-3: Green
Magnitude < 2: Light Green
Popups:

Each marker includes a popup with details such as location, magnitude, and time.
Dynamic Data Loading:

The application fetches earthquake data using D3.js from the USGS API.
Learning References
Official Documentation
Leaflet Documentation
D3.js Documentation
USGS Earthquake GeoJSON Documentation
Learning Platforms
ChatGPT: Used to generate and refine the logic.js file and project descriptions.
W3Schools: Guided the foundational understanding of HTML, CSS, and JavaScript basics.
Reference: W3Schools
Khan Academy: Strengthened the understanding of JavaScript and interactive programming.
Reference: Khan Academy JavaScript Tutorials
Udemy: For in-depth tutorials on Leaflet.js and D3.js for data visualization.
Reference: Udemy - JavaScript and Data Visualization Courses
Future Improvements
Enhanced Styling: Add more customization options for marker animations and map themes.
Filters: Allow users to filter earthquakes by magnitude, location, or time range.
Heatmap: Visualize earthquake density using a heatmap layer.
Offline Support: Implement caching for offline data visualization.
