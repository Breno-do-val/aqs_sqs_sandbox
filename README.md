# Products-api
Application for training the development of distributed systems using AWS.

## Table of Content
* [General info](#general-info)
* [Technologies and Dependencies](#technologies-&-dependencies)
* [Author](#author)
* [License and copyright](#license-and-copyright)
* [Acknowledgements](#acknowledgements)

## Screenshots
![](/src/main/resources/static/architecture.png)

## General info
The application will receive a product to be purchased and then will send a message to a SNS topic with payment information to be proceeded by another microservice.

###Technologies and dependencies
* CORS - It allows communication between different domains and used for any http request method;
* Express - Node.js library;
* Mongoose - ODM library for MongoDB and Node.js;
* Multer - A middleware for Express and Node.js that makes it easy to handle multipart/form-data for file uploading;
* Sharp - For high performance Node.js image processing;
* Socket.IO - Library for real-time communication;

###Setup
**_For development_**
In the project directory, you can run:
`npm start`
Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

**_For deployment_**
- The application has not been deployed yet.

####Author
Breno Ribeiro do Val - Following the instructions provided.

####License and copyright
MIT.

####Acknowledgments
Thanks to Diego Fernandes from Rocketseat who provided this bootcamp.
