# Pet-Friendly Web Map of Seattle

## Project Description
The Pet-Friendly Web Map of Seattle is a comprehensive and easily accessible resource to aid pet owners, future pet owners, as well as the general public who are interested in exploring and navigating information on pets in the Seattle area. The map overall is a dynamic and interactive web mapping tool designed for pet owners interested in pet adoption in Seattle. This web map displays the various pet resources in Seattle such as pet shops, pet-friendly parks, and veterinary clinics, based on the user's location and can help users discover the recources available to them by displaying the pet shops, dog parks, and vet clinics within their selected travel range. The map facilitates the exploration of pet-friendly services and amenities within the city, enhancing the pet ownership experience.

## Project Goals
The overarching aim of this web map is to enhance the pet-friendly environment of Seattle by providing a comprehensive and easy-accessible tool. Our map encourages pet owners and enthusiasts to explore and engage with different areas of Seattle, promoting a broader understanding and appreciation of the city's pet-friendly offerings. Our project also serves as a decision-making tool, providing pet owners with valuable information about pet resources, such as the proximity of parks, pet stores, and veterinary clinics. Such details are not only vital for day-to-day pet care but also imperative in emergencies. Through these resources, we aim to assist individuals considering pet adoption in making informed decisions. By showcasing available resources and services, we provide a clearer picture of what pet ownership in Seattle entails, thereby facilitating responsible and well-informed pet adoption. By providing detailed information about each pet service, we aim to inform users about various aspects of pet care and the availability of resources in their area. Overall, this map helps us encourage responsible pet ownership, in Seattle, by making it easier for owners to access the services and information they need to care for their pets properly. This map can also help the local government explore the topic of transportation accessibility for pet resources and areas that could use improvement.

## Application URL
[Pet-Friendly Web Map of Seattle](https://risan03-2165658.github.io/geog328_pet_friendly/index.html)

## Screenshots
1. Map View:
<img width="1250" alt="Screen Shot 2023-12-11 at 10 25 12 PM" src="https://github.com/risan03-2165658/geog328_pet_friendly/assets/77130958/b34c2e9f-76f6-417e-935e-44032b1c0408">


2. Detailed View:
<img width="1250" alt="Screen Shot 2023-12-11 at 10 25 26 PM" src="https://github.com/risan03-2165658/geog328_pet_friendly/assets/77130958/90a01e4a-5a15-4fd4-9289-0f747cc9fbe2">

## Main functions
* The main function of the web app is its ability to map an isochrone polygon based on the provided travel and time options in the widget. The isochrone polygon represents the areas that a person could travel to using the selected mode of transportation within the selected time limit. When the Toggle Travel Distance button is selected in the widget only pet shops, vets, and parks within the isochrone are displayed on the map. This shows the user what recources they could reach using their selected mode of transportation and available time. When the Toggle Travel Distance button is not selected, an isochrone is not shown on the map, however all available recources are mapped. We utilized turf.js booleanIntersect to filter which data points are within the isochrone.

* Customizable Widget: The widget, crafted with HTML and CSS, allows users to select their preferred mode of transportation and travel time as well as select which pet recources are visible on the map. JavaScript event listeners handle user input, adjusting the map polygon display accordingly.

* Interactive Map Interface: Implemented using Mapbox GL JS, providing a smooth and responsive user experience. Users can pan and zoom to explore different areas of Seattle.

* Location-Based Services: Utilizes GeoJSON data to pinpoint pet resources like shops and clinics on the map. The JavaScript fetch API is used to load GeoJSON files containing locations of pet resources.

* Dynamic Information Display: Click events on the map trigger pop-ups that display information about each pet resource. This is achieved by attaching event listeners to map elements, fetching data from the GeoJSON files.

* User Location Detection: The web map leverages the Geolocation API to fetch the user's current location, offering personalized resource suggestions based on their position and making this a much more useful web map. 

## Data Sources
The project leverages various datasets, including city park data from the Seattle City GIS, and pet shops and veterinary clinics location data created from Google My Maps, to provide a comprehensive view of pet-friendly locations in Seattle.

* [Seattle park boundaries](https://data-seattlecitygis.opendata.arcgis.com/datasets/SeattleCityGIS::parks-boundary-outline/explore?location=47.608377%2C-122.280278%2C12.00)
* [Seattle off-leash dog areas](https://data-seattlecitygis.opendata.arcgis.com/datasets/dog-off-leash-areas-1/explore)
* [Pet shops - Google My Maps](https://www.google.com/maps/d/u/0/edit?mid=1eDPuo2T36thtHkV4CE8EL_pauCu43SM&ll=4.537245984383745%2C0&z=2)
* [Veterinary Clinics - Google My Maps](https://www.google.com/maps/d/edit?mid=1wJgkO4OJPB-rFPqS7VMlA6bZTvt7eyI&usp=sharing)

## Applied Libraries and Web Services
This project is built using these several key technologies:

* Mapbox GL JS: For creating and manipulating the interactive map.
* Mapbox Isochrone API.
* GitHub: For hosting and version control.
* Google My Maps: For custom mapping data.
* Turf.js: For GIS data processing and spatial analysis.

## Limitations
While the Pet-Friendly Web Map of Seattle offers numerous benefits, it's important to acknowledge the limitations of our project and data. Firstly, we believe the map is highly dependent on the accuracy of its current data sources. Any changes when updating information about pet resources, such as new pet shops or changes in store policies, might lead to outdated or incomplete information. Secondly, the map's functionality and user experience rely heavily on the user's internet connectivity and device capabilities. Users with slower internet connections or less advanced devices may face challenges in accessing or navigating the map effectively. Additionally, the map primarily caters to the Seattle area, potentially limiting its usefulness for visitors or new residents unfamiliar with the city's geography. Lastly, while the map provides location-based services, it doesn't account for the quality or reputation of the listed pet resources, which can be crucial for users making decisions about pet care. These limitations, while not undermining the project's overall value, are important considerations for users and developers alike in optimizing and utilizing the web map effectively.

## Acknowledgements
Special thanks to Professor Zhao and TA Liz Peng for their guidance and support in the GEOG 328 course. Appreciation is also extended to the creators of the 'Pet Resource Web Map' for their inspirational work in the field of pet-friendly mapping in Seattle.

Additionally, we acknowledge the [Pet Resource Web Map](https://www.arcgis.com/apps/webappviewer/index.html?id=7639a0ab24cb49138bd4bf9995b1c193) that offers a detailed representation of pet resources in the Michigan area using ArcGIS. This resource inspired our decision to incorporate a similar mapping approach in our final deliverable, aiming to showcase pet-related amenities such as pet shops and healthcare institutions within the Seattle region. These resources were instrumental in shaping our project methodology and presentation, and we are grateful for the valuable insights they provided."

## Additional Notes
This project was collaboratively developed by Anthony Kim, Eli Henry Lockard, Franck Kepnang, Matthew Joon Ro, and Risa Nabari. Our aim is not just to provide information but to enhance the pet-friendly community in Seattle.
