# Pet-Friendly Web Map of Seattle

## Project Description
The Pet-Friendly Web Map of Seattle is a comprehensive and easily accessible resource to aid pet owners, future pet owners, as well as the general public who are interested in exploring and navigating information on pets in the Seattle area. The map overall is a dynamic and interactive web mapping tool designed for pet owners who may be interested in considering pet adoption in Seattle. It displays various pet resources such as pet shops, parks, and veterinary clinics, based on the user's location. The map facilitates the exploration of pet-friendly services and amenities within the city, enhancing the pet ownership experience.

## Project Goals
The overarching aim of this web map is to enhance the pet-friendly environment of Seattle by providing a comprehensive and easy-accesible tool. Our map encourages pet owners and enthusiasts to explore and engage with different areas of Seattle, promoting a broader understanding and appreciation of the city's pet-friendly offerings. Our project also serves as a decision-making tool, providing pet owners with valuable information about pet resources, such as the proximity of parks, pet stores, and veterinary clinics. Such details are not only vital for day-to-day pet care but also imperative in emergency situations. Through these resources, we aim to assist individuals considering pet adoption in making informed decisions. By showcasing available resources and services, we provide a clearer picture of what pet ownership in Seattle entails, thereby facilitating responsible and well-informed pet adoption. By providing detailed information about each pet service, we aim to inform users about various aspects of pet care and the availability of resources in their area. Overall, this map helps us encourage responsible pet ownership, in Seattle, by making it easier for owners to access the services and information they need to care for their pets properly.

## Application URL
[Pet-Friendly Web Map of Seattle](https://risan03-2165658.github.io/geog328_pet_friendly/index.html)

## Screenshots
1. <img width="1439" alt="Screen Shot 2023-12-11 at 3 22 05 AM" src="https://github.com/risan03-2165658/geog328_pet_friendly/assets/77130958/f91f5e5e-af52-43cd-a5ea-231d6b3424c5">

2. <img width="1439" alt="Screen Shot 2023-12-11 at 3 22 20 AM" src="https://github.com/risan03-2165658/geog328_pet_friendly/assets/77130958/994abcb2-8342-4945-a185-c7c16a9f8ebf">

## Main functions
The main features of the map include:

* Customizable Widget: The widget, crafted with HTML and CSS, allows users to select their preferred mode of transportation and travel time. JavaScript event listeners handle user input, adjusting the map polygon display accordingly.

* Interactive Map Interface: Implemented using Mapbox GL JS, providing a smooth and responsive user experience. Users can pan and zoom to explore different areas of Seattle.

* Location-Based Services: Utilizes GeoJSON data to pinpoint pet resources like shops and clinics on the map. The JavaScript fetch API is used to load GeoJSON files containing locations of pet resources.

* Dynamic Information Display: Click events on the map trigger pop-ups that display detailed information about each pet resource. This is achieved by attaching event listeners to map elements, fetching data from the GeoJSON files.

* User Location Detection: The web map leverages the Geolocation API to fetch the user's current location, offering personalized resource suggestions based on their position.

## Data Sources
The project leverages various datasets, including city park data from the Seattle City GIS, pet shops and veterinary clinics data from Google My Maps, and more, to provide a comprehensive view of pet-friendly locations.

## Applied Libraries and Web Services
This project is built using several key technologies:

* Mapbox GL JS: For creating and manipulating the interactive map.
* GitHub: For hosting and version control.
* Google My Maps: For custom mapping data.
* Turf.js: For GIS data processing and spatial analysis.

## Acknowledgements
Special thanks to Professor Zhao and TA Liz Peng for their guidance and support in the GEOG 328 course. Appreciation is also extended to the creators of the 'Pet Resource Web Map' for their inspirational work in the field of pet-friendly mapping in Seattle.

## Additional Notes
This project was collaboratively developed by Anthony Kim, Eli Henry Lockard, Franck Kepnang, Matthew Joon Ro, and Risa Nabari. Our aim is not just to provide information but to enhance the pet-friendly community in Seattle.
