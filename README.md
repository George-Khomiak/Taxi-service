# Taxi-service
### A simple service to navigate user through a taxi driver application, allowing to manipulate their data using site and store it in the database.

## Usage:
First navigate to _http://localhost:8080/driver/add_ to register a new user, then you will be redirected to a login page.
After registration user is able to assign a driver to a car choosing between manufacturers, or to create a new one.
User can track what cars drivers have in use, change them or remove (with corresponding database changes).

## Structure
Project is created according to SOLID principles, easy to maintain and to add functionality if needed.
The internal structure is separated between 3 layers: Data access layer, Application layer, and Presentation layer.

## Technologies used:
***Apache Tomcat (v9.0.50)***, ***MySQL***, ***Jakarta Servlet***, ***JSP*** ***JSTL***, ***JDBC***,
***HTML***, ***CSS***;

## Requirements:

Installed MySQL linked to IDE (use init_db.sql in resources folder to create a schema and fill the required
information in ConnectionUtil class to link to the database);

### Enjoy!

