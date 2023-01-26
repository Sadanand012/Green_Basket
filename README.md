#Green Basket

#E-R Diagram


![E-R Diagram](https://user-images.githubusercontent.com/107461052/212683690-1910c6e2-cb10-409e-b1ee-d94c6c18f246.png)

<br>
<br>
#WorkFlow
<br>

![WorkFlow](https://user-images.githubusercontent.com/107461052/212683750-11c64541-9c01-4137-9e1f-539b31994b85.png)




# GreenBasket (Online Vegetable Sales Application)
# FrontEnd And BackEnd(REST API)for an Online Vegetable Sales Application
<br>
<br>
<img src="https://user-images.githubusercontent.com/107461052/212683987-3cf29572-7af3-4b84-bc8d-57c594f8a75e.png"  width="300" height="200" position="center">

<br>
<br>


- An online vegetable sales application allows customers to easily purchase fresh, locally sourced produce from their phone or computer.
- The application features a user-friendly interface, allowing customers to browse and select from a wide variety of fruits and vegetables.
- Customers can customize their order and choose a delivery or pickup option that works for them.
- The backend of the application is built using Java and Spring Framework.
- The backend handles all the business logic and communicates with the database (MySQL).
- The backend exposes RESTful endpoints for the frontend to consume.
- The code follows best practices for maintainability and scalability.
- The application is continuously integrated and deployed.
- This repository is open-source and contributions are welcome.
- The application is built using modern technologies such as Spring Boot.
- It includes a swagger documentation for the endpoints.
- The application follows best practices for security in terms of input validation and access control.

<br>

* This project is developed by team of 5 Aspiring Developers . 

## Tech Stack

* Java
* Spring Framework
* Spring Boot
* Spring Data JPA
* Hibernate
* MySQL
* HTML
* CSS
* JavaScript

------------------------------------------------------------------------------
## Modules
------------------------------------------------------------------------------
* Login, Logout Module
* Customer Module
* Admin Module
* AddToCart Module
* Order Module
* Vegetable Stock Module

---------------------------------------------------------------------------------
## Features

---------------------------------------------------------------------------------
* Customer and Admin authentication & validation with usersession's sessionid.
* Admin Features:
    * Administrator Role of the entire application
    * Only registered admins with valid sessionid can add/update/delete Vegetable in the database.
    * Admin can access the details of orders, bill details, customer list.
* Customer Features:
    * Registering themselves with application, and logging in to get the valid sessionid.
    * Customer can add vegetables into the cart
    * Only logged in user can access their all order history.

--------------------------------------------------------------------------------
## Contributors
--------------------------------------------------------------------------------
*<a href="https://github.com/mynkgupta22">Mayank Gupta</a>
<br>
*<a href="https://github.com/kieransahoo">Kieran Sahoo</a>
<br>
*<a href="https://github.com/mynkgupta22">Nitesh Pal</a>
<br>
*<a href="https://github.com/mynkgupta22">Sadanand Mare</a>
<br>
*<a href="https://github.com/mynkgupta22">Santosh Kumar</a>


## Installation & Run

* Before running the API server, you should update the database config inside the [application.properties](GrennBasket\src\main\resources\application.properties) file. 
* Update the port number, username and password as per your local database config.

```
    server.port=8088
    spring.datasource.url=jdbc:mysql://localhost:3306/greenBasket;
    spring.datasource.driver-class-name=com.mysql.cj.jdbc.Driver
    spring.datasource.username=root
    spring.datasource.password=root
```

## API Root Endpoint

`https://localhost:8082/`

`http://localhost:8082/swagger-ui.html`


## API Module Endpoints

### Customer Module


* `POST /customer` : Register customer by providing valid details






