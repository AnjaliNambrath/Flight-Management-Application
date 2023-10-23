# Flight-Management-Application
===============================
Application Purpose: Web Application developed for flight management with a booking bot assist which is built using Kore.ai XO platform. The effective online airline application management system which enables the end users for selecting preferred flight.

Personas:
=========
ADMIN – Add, Update, delete Flights and its capacity. Add, Update, delete route and price details to 
each flight. 
USER – Get available flights for the given route and book tickets.

Tasks:
======
ADMIN:
- Add, update, delete Flights, seating capacity and status.
- Add, update, delete Route details and price.
USER:
- Search flights for the provided routes.
- User can book preferred flight.
- User can view, cancel and save ticket.

Endpoints:
==========
ADMIN: http://localhost:3000/adminlogin
Add flights:
POST/ http://localhost:5000/flight
Get flights:
GET/ http://localhost:5000/flight
Update flights:
PUT/ http://localhost:5000/flight/:_id
Delete flights:
DELETE/ http://localhost:5000/flight/:_id
Show routes:
GET/ http://localhost:5000/routes
Update routes:
PUT/ http://localhost:5000/routes
Delete routes:
DELETE/ http://localhost:3000/routes/:_id
Search routes:
GET/ http://localhost:3000/flight/ : source/ :destination
USER: http://localhost:3000/userlogin
Add Passenger:
 POST / http://localhost:5000/customer
Get Passenger:
 GET / http://localhost:5000/searchcustomers/:id
Delete Passenger:
 DELETE /http://localhost:5000/customer/:id
