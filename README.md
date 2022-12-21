# CINEMA APPLICATION
**Description** 📄

This project is a simple web application of the cinema that supports such functions:
- new user registration and login for registered users
- add and remove movie, movie session and cinema hall
- add the tickets to the shopping cart and complete the order

**Features** 📡

|  Role   | Endpoint                                                                                                                                                                                                                                                                    |
|:-------:|:----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `ADMIN` | POST: `/register` <br/> GET: `/cinema-halls`<br/>POST:`/cinema-halls`<br/>GET: `/movies`<br/>POST: `/movies`<br/>GET: `/movie-sessions/available`<br/>POST: `/movie-sessions`<br/>PUT: `/movie-sessions/{id}`<br/>DELETE: `/movie-sessions/{id}`<br/>GET: `/users/by-email` |
| `USER`  | POST: `/register` <br/> GET: `/cinema-halls`<br/>GET: `/movies`<br/>GET: `/movie-sessions/available`<br/>GET: `/orders`<br/>POST: `/orders/complete`<br/>PUT: `/shopping-carts/movie-sessions`<br/>GET: `/shopping-carts/by-user`                                           |


**Project structure** 📄

The project based on N-Tier architecture:
- DAO layer - CRUD operations with database entities
- DTO layer - representing models on UI layer
- Service layer - business logic of the application
- Controllers - accept requests from the clients and send responses

**Technologies** 📡
- JDK
- Hibernate ORM
- Spring Framework
- Tomcat
- MySQL
- Maven


**Instruction to run the project** 📄
1. Fork this repository
2. Clone your repository to IDE
3. Configure - [/resources/db.properties](https://github.com/vov4ik89/cinema-app/blob/main/src/main/resources/db.properties)
4. Install Tomcat
5. Configure Tomcat Server
6. Run the project (You can log in using username = admin@i.ua and password = admin)


![whole schema_1](uml.jpg)
