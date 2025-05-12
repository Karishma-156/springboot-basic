# Spring Boot with MongoDB

This project is a basic Spring Boot application integrated with MongoDB. It provides a simple REST API to manage books, offering CRUD (Create, Read, Update, Delete) operations.

## Features

- Spring Boot backend framework.
- MongoDB as the database.
- RESTful API for CRUD operations.
- Easy-to-understand code structure for beginners.

## Prerequisites

To run this project, make sure you have the following installed:

- Java 11 or later
- Maven
- MongoDB (either local or remote)
  
### MongoDB Setup

Ensure MongoDB is running locally or provide the appropriate MongoDB URI in the `application.properties` file:

```properties
spring.data.mongodb.uri=mongodb://localhost:27017/mydatabase
```

### Set Up MongoDB
Ensure MongoDB is running locally or provide the appropriate MongoDB URI in the application.properties file:

```properties
spring.data.mongodb.uri=mongodb://localhost:27017/mydatabase
```

### Build and Run the Application
You can build and run the Spring Boot application using the following command:

```bash
mvn spring-boot:run
```

Or you can create a JAR file:

```bash
mvn clean package
```

Then run the JAR:

```bash
java -jar target/bookapi-0.0.1-SNAPSHOT.jar
```

### API Endpoints
```GET /books: Fetch all books.

GET /books/{id}: Fetch a specific book by ID.

POST /books: Add a new book.

PUT /books/{id}: Update an existing book.

DELETE /books/{id}: Delete a book.
```

### 3. **Save the File**

After making your changes, save the `README.md` file and close your editor.

### OUTPUT:

## EMPTY GET POST (INITIALLY):

![Postman Screenshot](https://github.com/Karishma-156/springboot-basic/blob/main/postman1.png?raw=true)

## FIRST POST REQUEST:

![Postman Screenshot](https://github.com/Karishma-156/springboot-basic/blob/main/postman2.png?raw=true)

## DELETE REQUEST:

![Postman Screenshot](https://github.com/Karishma-156/springboot-basic/blob/main/delete.png?raw=true)

## GET REQUEST AFTER DELETE:

![Postman Screenshot](https://github.com/Karishma-156/springboot-basic/blob/main/get.png?raw=true)

## MongoDB Compass DATABASE:

![Postman Screenshot](https://github.com/Karishma-156/springboot-basic/blob/main/mongodbcompass.png?raw=true)

## ENDPOINT :

![Postman Screenshot](https://github.com/Karishma-156/springboot-basic/blob/main/webpic.png?raw=true)
