
 Vehicle Tracking Application

This project is a vehicle tracking application that visualizes a vehicle's movement on a map. The application utilizes the Leaflet library for interactive mapping and routing, with options for predefined routes or custom locations.

 Features

- Interactive Map:Displays an initial view of Agra and allows for zooming and panning.
- Vehicle Marker: A custom vehicle icon that represents the vehicle on the map.
- Routing: Ability to show routes between specified start and end points using the Mapbox routing service.
- Geocoding:  Converts place names to geographic coordinates using the OpenStreetMap Nominatim API.
-  Custom Routes: Users can select predefined trips or input custom locations for routing.
- Vehicle Movement Simulation: Simulates the movement of the vehicle along the defined route.

## Prerequisites

- Basic knowledge of HTML, CSS, and JavaScript.
- A web browser for testing the application.

## Technologies Used

- [Leaflet](https://leafletjs.com/): A JavaScript library for interactive maps.
- [Font Awesome](https://fontawesome.com/): For the vehicle icon.
- [OpenStreetMap Nominatim API](https://nominatim.org/): For geocoding place names.
- [Mapbox](https://www.mapbox.com/): For routing services.

## Setup

1.  Clone the repository:
   ```bash
   git clone https://github.com/your-username/vehicle.git
   cd vehicle
   ```

2. Open the `index.html` file in a web browser.

Usage

1. Select a Trip:
   - Choose a predefined trip (e.g., today, yesterday, last week) or select "custom" to enter specific start and end locations.
   
2. Enter Custom Locations (if applicable):
   - If "custom" is selected, input the start and end locations in the provided fields.

3. Show Route:
   - Click the "Show Route" button to display the route on the map.

4. Start Vehicle Movement:
   - Click the "Start Movement" button to simulate the vehicle's movement along the route.

## Code Structure

- `index.html`: The main HTML file containing the structure of the application.
- `style.css`: The CSS file for styling the application.
- `script.js`: The JavaScript file containing the logic for the application, including map initialization, routing, and vehicle movement.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Thanks to the developers of Leaflet and the OpenStreetMap community for providing excellent tools for mapping and routing.

---

Feel free to customize any sections according to your project's specifics or preferences!
