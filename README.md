## Airline E-Commerce website using Java Spring boot and thymeleaf
- Created a website where users can login/register(using spring security) as well as search and book flights.
- Created Integration layer(REST API) for flight checkin microservice to check in passengers
  with reservations. Developed a microservice where users can check in to their existing flight.
- Added Spring Data JPA(hibernate) as an ORM to interact with the MYSQL database.
- Designed front end templates using thymeleaf, html,css,bootstrap
- Added Logging feature and custom log rotation policies.




#### Details
- Created a web application where logged in users as well as search and book flights.
- Added feature to register new users and implement login.
- Used Spring Data JPA(hibernate) as an ORM to interact with the MYSQL database.
- Designed front end templates using thymeleaf and styled them using Bootstrap and Css.
- Used bower.js to install jquery and bootstrap dependencies.
- Created Integration layer(REST API) for flight checkin microservice to check in passengers
with reservations. 



#### Microservice for checking in passengers

https://github.com/deepanshululla/flight-checkin

#### Database Model

There are 4 tables

- FLIGHT
- RESERVATION
- USER
- PASSENGER

There is one to one mapping assumed between reservation and passenger as well as reservation
and flight.