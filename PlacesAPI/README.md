
Steps

1) create api key
2) import script  with src and replace your key

    <script src="https://maps.googleapis.com/maps/api/js?key=YOUR-KEY&libraries=places&callback=initAutocomplete"
        async defer></script>

3) pass a callback function (initAutocomplete)

4)


************************************************************************************
Caution: 
If you don't call Autocomplete.setFields(), then all of the available place data fields for a place result are returned,
 and you are billed for all of them.
************************************************************************************

Diferent parameters

// Set initial restrict to the greater list of countries.
autocomplete.setComponentRestrictions({'country': ['us', 'pr', 'vi', 'gu', 'mp']});

// Specify only the data fields that are needed.
autocomplete.setFields(['address_components', 'geometry', 'icon', 'name']);





Descripción general
Get data from the same database used by Google Maps. Places features over 100 million businesses and points of interest that are updated frequently through owner-verified listings and user-moderated contributions.

Place search  Return a list of places based on a user’s location or search string.

Place details  Return detailed information about a specific place, including user reviews.

Place autocomplete  can be used to automatically fill in the name and/or address of a place as you type.

Query autocomplete  can be used to provide a query prediction service for text-based geographic searches, by returning suggested queries as you type.

Place photos  gives you access to the millions of Place related photos stored in Google's Place database.

Places SDK for Android  and Places SDK for iOS  allow you to build location-aware apps that respond contextually to the local businesses and other places near the device.


Acerca de Google
Google's mission is to organize the world's information and make it universally accessible and useful. Through products and platforms like Search, Maps, Gmail, Android, Google Play, Chrome and YouTube, Google plays a meaningful role in the daily lives of billions of people.

Instructivos y documentación
Documentation  
Pricing  
Mantenimiento y asistencia
Más información  
Condiciones del servicio
Si usas este producto, confirmas que aceptas los términos y condiciones de las siguientes licencias: Google Maps Platform 

more info
https://developers.google.com/maps/documentation/javascript/examples/places-autocomplete-addressform
