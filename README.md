# Web Application using RESTful APIs

This web application finds restuarants based on a desired meal-type and adrress. 

On a POST requrest, the application geocodes the location, finds a nearby restaurant, stores it in a database and returns a JSON object of the restaurant to the user. 

On a GET request, the JSON object returns with the name, ID number, address and image of the restaurant. 

On an UPDATE request, along with the name or any other related information about an existing restaurant, it updates the restaurant information in the database.

### Technologies:

APIs - Google's Geocode, FourSquare, SQLite

Web Development Environment - Python and Flask
